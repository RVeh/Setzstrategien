Informationen zur Datei 2024-08-30-Setzstrategien-A-B:

Mit diesem Programm können zwei Startverteilungen A und B vergleichen werden.
Geben Sie für A und B eine beliebige Verteilung der Chips ein. Die Größe der Tupel muss gleich sein, ist aber beliebig.
In dem Tupel p müssen die zugehörigen Wahrscheinlichkeiten eingetragen werden.

A=(3,5,4,3,2,1) bedeutet, dass zu Beginn 3 Chips auf dem ersten Feld, 5 Chips auf dem zweiten Feld, ..., liegen.

B=(2,6,5,4,1,0) entspechend.

Es wird das oft im Stochastikunterricht verwendete Spiel "Differenz trifft" untersucht. 

- Welche Startverteilung ist "besser" als eine andere Startverteilung? 

- Wie groß sind die Erwartungswerte (Anzahl der Züge bis zum Abräumen)?

In dem Tupel p stehen die zugehörigen Wahrscheinlichkeiten (P(Absolutdifferenz beim Doppelwurf)=k); k=0,...,5.
Insgesamt werden jeweils 18 Chips verteilt.


Informationen zur Datei 2024-08-30-Setzstrategien-A-gegen-Verteilungen:

Hiermit kann eine Verteilung gegen andere Verteilungen verglichen werden.

Um die Anzahl der Verteilungen einzugrenzen, gilt x_6=0. Auf dem letzten Feld liegt kein Chip. 

Wenn z. B. zusätzlich für das 5. Feld gilt: x_5=2, dann muss man Folgendes eingeben:

for x1, x2, x3, x4 in product(range(17), repeat=4):

if x1 + x2 + x3 + x4 + 2 + 0 == 18: B = (x1, x2, x3, x4, 2, 0)
