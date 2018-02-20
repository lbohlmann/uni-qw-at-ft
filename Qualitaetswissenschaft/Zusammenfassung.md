# Qualitätswissenschaft
## Zusammenfassung

### House of Quality

Das HoQ ist das Ergebnis des Quality Function Deployment und stellt Beziehungen zwischen Produktmerkmalen und Kundenerwartungen auf einen Blick grafisch dar.

### Quality Function Deployment

Das QFD ist eine Methode aus dem Projektmanagement. Es dient dazu, zu erarbeiten welche Aspekte eines neuen oder bestehenden Produkt besonders wichtig sind und auch im HInblick auf Konkurrenzprodukte verbessert werden sollten.

<center> 

##### Schritt 1:
**Kundenanforderungen** ermitteln und in Begriffe fassen (Kundenbefragungen). Diese werden im HoQ auf der linken Seite eingetragen.
##### Schritt 2:
Die Kundenanforderungen werden **gewichtet** und zu jeder Anforderungen wird eine Maßzahl notiert (z.B. 0-10).
##### Schritt 3:
Ein vorhandener Prototyp des eigenen Produkts und entsprechende Konkurrenzprodukte werden ein einer **Kundenbewertung** verglichen und auf der rechten Seite des HoQ notiert.
##### Schritt 4:
Die **Produktmerkmale** werden festgelegt und oben unter dem Dach des HoQ eingetragen.
##### Schritt 5:
Bestimmung der **Optimierungsrichtung** es wird für jedes Produktmerkmal festgelegt, in welche Richtung eine Veränderung hinsichtlich der Kundenerwartung vorteilhaft ist (Größer, Kleiner, Idealwert).
##### Schritt 6:
In der Mitte des HoQ werden die **Wechselwirkungen zwischen Produktmerkmalen und Kundenanforderungen** wie in einer Matrix quantitativ eingeschätzt (Schwache Beziehung - Starke Beziehung).
##### Schritt 7:
Das spitze Dach des HoQ ist dazu gedacht hier die **Beziehungen zwischen den Produktmerkmalen** einzuschätzen (Zielkonflikt, Zielharmonie, Zielneutralität).
##### Schritt 8:
**Technische Bedeutung** der Produktmerkmale, die Zahlen für die Beziehung von Kundenanforderungen und Produktmerkmalen werden unten aufaddiert um eine Vorstellung davon zu gewinnnen welche Merkmale besonders bedeutsam sind.
##### Schritt 9:
**Konkrete Zielwerte** für die einzelnen Produktmerkmale werden unter Berücksichtung der bisherigen Ergebnisse festgelegt.
##### Schritt 10:
Die festgelegten Ziele werden nun verwendet, um einen **Produktvergleich mit der Konkurrenz** durchzuführen

</center>

### Stochastik

##### Begriffe
|Begriff        |  Definition                                                                                                      |
|---------------|------------------------------------------------------------------------------------------------------------------|
| Vollerhebung  |Ein Experiment wird so oft wiederholt, wie Elemente vorhanden sind, d.h. k-Ziehungen von n-Elementen (wobei k = n)|
| Stichprobe    |Ein Experiment mit n-Elementen wird k-mal wiederholt (wobei k < n)                                                |
| ungeordnet    |Reihenfolge der Ergebnisse ist ohne Bedeutung (z.B. Lotto)                                                        |
| geordnet      |Reihenfolge der Ergebnisse ist wichtig (z.B. Zieleinlauf)                                                         |
| stetige Werte |alle Werte innerhalb eines Intervalls (z.B. benötigte Zeit für einen 100m Lauf)                                   |  
| diskrete Werte|abzählbar viele Werte, z.B. Würfelaugen (d.h. keine Zwischenwerte)                                                |##### Formelzeichen
|Formelzeichen       |  Konvention                              |
|--------------------|------------------------------------------|
|kleine Buchstaben   |Elementarereignisse                       |
|große Buchstaben    |Menge von Elementarereignissen            |
|P(X)                |Wahrscheinlichkeit, mit der X eintritt    |
|n                   |Anzahl der Versuchswiederholung           |
|k                   |Anzahl der Treffer                        |  
|p                   |Wahrscheinlichkeit für einen Erfolg       |
|q                   |Wahrscheinlichkeit für eine Misserfolg    |
|V(X)                |Varianz                                   |
|E(X)                |Erwartungswert                            |
|$\sigma$ (sigma)    |Standardabweichung, Streuungsmaß          |
|$\epsilon$ (Epsilon)|Umgebung um eine Zahl, Toleranzband       |

### Binomialkoeffizient

Der Binomialkoeffizient gibt an, auf wie viele verschiedene Arten man k Objekte aus einer Menge von n verschiedenen Objekten auswählen kann. Der Versuch wird dabei ohne Zurücklegen und ohne Beachtung der Reihenfolge durchgeführt.

$$ {n \choose k} = \frac{n!}{k! \cdot (n-k)!}$$

### Verteilungen

##### Laplace-Verteilung 

Alle Ereignisse treten mit der gleichen Wahrscheinlichkeit auf, z.B. Münze oder Würfel.

$$ P(A) = \frac{Anzahl \space der \space möglichen \space Erfolge}{Anzahl \space aller \space möglichen \space Ereignisse} $$

##### Binomial-Verteilung

Das Experiment liefert genau zwei Ergebnisse mit den Wahrscheinlichkeiten p für Erfolg und q für Misserfolg.

$$ p + q = 1 $$

$$ P(X=k) = {n \choose k}⋅p^k ⋅q^{(n−k)} $$

##### Hypergeometrische Verteilung

Eine Menge besteht aus N-Elementen. M-Elemente gehören zur Sorte 1, (N-M) Elemente gehören zur Sorte 2. Die Wahrscheinlichkeit, dass bei n-Ziehungen ohne Zurücklegen k-Elemente von Sorte 1 sind, ist:

$$ P(X=k) = \frac{{M \choose k} \cdot {{N-M} \choose {n-k}}}{N \choose n} $$

z.B. Stichprobe auf Funktionsfähigkeit von N-Produkten, von denen M funktionieren und N-M defekt sind.

### Erwartungswert, Varianz, Standardabweichung

##### Erwartungswert

Der Wert der beim unendlich oft durchgeführten Versuch im Mittel erreicht wird. Für große (endliche) Anzahlen von Versuchsdurchführungen kann dieser Wert ''erwartet'' werden.

Ist $X$ eine Zufallsvariable, welche die Werte $x_1$ bis $x_n$annehmen kann, so ist der Erwartungswert:

$$ E(X) = x_1 \cdot P(X=x_1) + x_2 \cdot P(X=x_2) + ... + x_n \cdot P(X=x_n) $$

$$ E(\alpha \cdot X) = \alpha \cdot E(X) \quad \quad E(X+Y) = E(X) + E(Y) $$

##### Varianz

Drückt die quadrierte Abweichung vom Mittelwert aus. (Hohe Varianz $\rightarrow$ Hohe Streuung)

Ist $X$ eine Zufallsvariable, welche die Werte $x_1$ bis $x_n$ annehmen kann, so ist die Varianz:
$$ \mu := E(X) $$

$$ V(X) = E(X - \mu)^2 = E(X^2) - \mu^2 \quad (Verschiebungssatz)  $$

$$ V(X) = (x_1 - \mu)^2 \cdot P(X=x_1) + (x_2 - \mu)^2 \cdot P(X=x_2) + ... + (x_n - \mu)^2 \cdot P(X=x_n) $$

Liegen abgeschlossene Ergebnisse $e_1$ bis $e_n$ vor:

$$ \overline{e} := Mittelwert $$

$$ V(X) = \frac{(e_1 - \overline{e})^2 + (e_2 - \overline{e})^2 + ... + (e_n - \overline{e})^2}{n}$$

##### Standardabweichung

Die Standardabweichung ist die Wurzel der Varianz

$$ \sigma = \sqrt{V(X)}$$

##### Berechnung für die hypergeometrische Verteilung

$$ E(X) = n \cdot \frac{M}{N} $$
$$ V(X) = n \cdot \frac{M}{N} \cdot \left( 1-\frac{M}{N} \right) \cdot \frac{N-n}{N-1} $$

##### Berechnung für die Binomialverteilung

$$ E(X) = n \cdot p \quad \quad V(X) = n \cdot p \cdot q $$

### Fehler 1. und 2. Art



### OC-Diagramm (AQL, RQL, IQL, $\alpha$, $\beta$, Produzentenpunkt, Konsumentenpunkt)
### Prozessfähigkeitsindex
### Justierung
### Perato-Analyse
### Ishikawa-Diagramm
### Vollfaktorieller Versuchsplan / Teilfaktorieller Versuchsplan
### Effektdiagramm
### Fehlermöglichkeits- und Einflussanalyse (FMEA)