# Zusammmenfassung Automatisierungstechnik

## Themenliste

+ Matlab (?)
+ De Morgan'sche Regeln
+ Bool'sche Algebra
+ KNF und DNF
+ Karnaugh Diagramm
+ K-F-Diagramm
+ Kippschaltungen
+ RS Latch / Flipflop
+ Zustandsgraph
+ Zustandsübergangsdiagramm
+ Systemzustände
+ Schaltfunktionen
+ Fuzzy Logic
+ Neuronale Netze
+ Bayes Netze
+ KNN


## De Morgan'sche Regeln
Die DeMorgan'schen Regeln lauten
$$\neg {(a\wedge b)}=\neg {a}\vee \neg {b}$$
$$\neg {(a\vee b)}=\neg {a}\wedge \neg {b}$$
Sie sind leichter zu merken, wenn man die mathematischen Symbole weglässt:
$$nicht \space (a \space und \space b) = (nicht \space a) \space oder \space (nicht \space b)$$
$$nicht \space (a \space oder \space b) = (nicht \space a) \space und \space (nicht \space b)$$

## Bool'sche Algebra

##### Negation
Die Verneinung einer Aussage A dreht den Wahrheitswert von A in sein Gegenteil um.
$$\lnot A$$
<center>''nicht A''</center>

##### Konjunktion 
Die Konjunktion ist das logische **UND**, ihr Symbol ist:
$$A\land B$$
<center>''A und B''</center>

##### Disjunktion
Die Disjunktion ist das logische **ODER**, ihr Symbol ist:
$$A\lor B$$
<center>''A oder B''</center>

##### Materiale Implikation
Die materiale Implikation, auch Konditional oder Subjunktion genannt, drückt die hinreichende Bedingung aus: Sie sagt, dass die Wahrheit des einen Satzes eine hinreichende Bedingung für die Wahrheit des anderen Satzes ist.
$$A\rightarrow B$$
<center>''Wenn A, dann B''</center>


## KNF und DNF
##### Konjunktive Normalform
Eine Formel der Aussagenlogik ist in konjunktiver Normalform, wenn sie eine Konjunktion von Disjunktionstermen ist. Disjunktionsterme sind dabei Disjunktionen von Literalen. Literale sind nichtnegierte oder negierte Variablen.

Bespiel:
$$(A \vee B \vee C ) \wedge (\bar{A} \vee B \vee C)$$

###### Kanonische konjunktive Normalform
Eine kanonische konjunktive Normalform (KKNF) besteht aus paarweise verschiedenen Maxtermen. In jedem dieser Maxterme kommt jede Variable genau einmal vor.
Jede Boolesche Funktion besitzt genau eine KKNF. Die KKNF wird auch vollständige konjunktive Normalform genannt.

###### Bildung
Jede Formel der Aussagenlogik lässt sich in konjunktive Normalform umwandeln, da sich auch jede boolesche Funktion mit einer KNF darstellen lässt. Dazu genügt es, die Zeilen ihrer Wahrheitstabelle abzulesen. Für jede Zeile, die als Resultat eine 0 liefert, wird eine Klausel gebildet, die alle Variablen der Funktion disjunktiv mit der invertierten Belegung verknüpft. Die entstehenden Terme sind Maxterme. Deren konjunktive Verknüpfung liefert die kanonische konjunktive Normalform.

Diese ist in der Regel keine minimale Formel, das heißt eine Formel mit möglichst wenig Klauseln. Will man eine minimale Formel bilden, so kann man dies etwa mit Hilfe von Karnaugh-Veitch-Diagrammen (kurz KV-Diagrammen) tun.

##### Disjunktive Normalform 
Eine Formel der Aussagenlogik ist in disjunktiver Normalform, wenn sie eine Disjunktion von Konjunktionstermen ist. Ein Konjunktionsterm wird ausschließlich durch die konjunktive Verknüpfung von Literalen gebildet. Literale sind dabei entweder nichtnegierte oder negierte Variablen.

###### Kanonische disjunktive Normalform
Eine kanonische disjunktive Normalform (KDNF), auch vollständige disjunktive Normalform genannt, ist eine DNF, die nur Minterme enthält, in denen alle Variablen vorhanden sind, jede Variable genau einmal vorkommt und deren Minterme alle voneinander verschieden sind. Jede Boolesche Funktion besitzt genau eine KDNF.

In der KDNF sind diejenigen Variablenbelegungen, für die die Funktion den Wert 1 annimmt, durch Minterme ausgedrückt.

###### Bildung
Jede Formel der Aussagenlogik lässt sich in die disjunktive Normalform umwandeln, da sich auch jede Boolesche Funktion mit einer DNF darstellen lässt. Dazu genügt es, die Zeilen ihrer Wahrheitstabelle abzulesen. Für jede Zeile, die als Resultat eine 1 liefert, wird eine Konjunktion gebildet, die alle Variablen der Funktion (der Zeile) verknüpft. Variablen, die in der Zeile mit 1 belegt sind, werden dabei nicht negiert und Variablen, die mit 0 belegt sind, werden negiert. Diese Terme werden auch Minterme genannt. Durch disjunktive Verknüpfung der Minterme erhält man schließlich die disjunktive Normalform.

Auf diese Weise erhält man allerdings in der Regel keine minimale Formel, das heißt eine Formel mit möglichst wenig Termen. Will man eine minimale Formel bilden, so kann man dies mit Hilfe von Karnaugh-Veitch-Diagrammen oder mithilfe des Quine-McCluskey-Verfahrens tun.

## Karnaugh Diagramm
## K-F-Diagramm
## Kippschaltungen
## RS Latch / Flipflop
## Zustandsgraph
## Zustandsübergangsdiagramm
## Systemzustände
## Schaltfunktionen
## Fuzzy Logic
## Neuronale Netze
## Bayes Netze
## KNN
