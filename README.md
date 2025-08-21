# 🧠 Chip-Abräumspiele - Wahrscheinlichkeiten

Ein interaktives Projekt zur Analyse von Chip-Verteilstrategien mit exakten und numerischen Berechnungen zu Gewinnwahrscheinlichkeiten.
Alle Berechnungen erfolgen in Python.

## 🚀 Direkt starten mit Binder - kann einige Zeit dauern

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RVeh/Setzstrategien/HEAD)

---

## 📂 Struktur der Notebooks

| Notebook | Inhalt |
|----------|--------|
| `01a-P_A-P_B-P_U-Abb2.ipynb` | Gewinnwahrscheinlichkeiten beim Ein-Würfel-Spiel - Abb. 2 (Artikel) - mit Ein- und Ausgabe |
| `01b-P_A-P_B-P_U.ipynb` | Gewinnwahrscheinlichkeiten beim Ein-Würfel-Spiel |
| `02-S-gegen-alle-T.ipynb` | Alle Strategien $T$ mit Chipsumme $n$ gegen $S$ |
| `03a-Vergleich-better-Stragegie.ipynb` | Ein-Würfel-Fall: Feste Strategie $V$ gegen alle möglichen Strategien $W$ mit der Möglichlkeit von Einschränkungen der Chipanzahl für die einzelnen Fächer (Suche nach "besseren" Setzstrategien) |
| `03b-Vergleich-better-Stragegie.ipynb` | Zwei-Würfel-Fall: Feste Strategie $S$ gegen alle möglichen Strategien $T$ mit der Möglichlkeit von Einschränkungen der Chipanzahl für die einzelnen Fächer (Suche nach "besseren" Setzstrategien) |
| `03c-Dominanz-Zyklen.ipynb` | Dieses Notebook erzeugt alle Strategien (Chipverteilungen) für gegebene Trefferwahrscheinlichkeiten und Gesamtchipanzahl, vergleicht jede Strategie mit jeder anderen exakt und wertet die Dominanzrelation sowie nichttransitive 3-Zyklen aus.|
| `04a-ein-Wuerfel-Fall-symbolisch.ipynb` | symbolische Berechnungen für zwei Setzstrategien (kompakt)  |
| `04b-ein-Wuerfel-Fall-symbolisch-exakt-numerisch.ipynb` | symbolische, exakte und numerische Berechnungen für zwei Setzstrategien  |
| `05-exakt-ein-zwei-Wuerfel.ipynb` | exakte Berechnungen für den ein-und zwei-Würfel-Fall |
| `06-Simulation-P_A-P_B.ipynb` | Simulationen (ein Würfel) mit 95%-WALD-Konfidenzintervallen |
| `07-Simulation-ein-zwei-Wuerfel.ipynb` | Simulationen (ein/zwei Würfel) mit 95%-WALD-Konfidenzintervallen und exakten Berechnnungen für den ein-Würfel-Fall|
| `08-Simulation-Exakt.kompakt.ipynb` | Simulationen (ein Würfel) mit 95%-WILSON-Konfidenzintervallen, exakten Berechnnungen und Grafikausgabe|


---

## 📦 Weitere Hinweise

Alle zentralen Funktionen befinden sich in:

```python
PropSetzstrategien.py
```
---

Hinweise zur Nutzung

- Notebooks lassen sich direkt in Jupyter oder auf Binder öffnen.
- Bei Binder oder JupyterLab bitte in der Menüzeile **"Run All Cells"** auswählen, um alle Ausgaben zu erzeugen.
- Das Projekt verwendet die Python-Standardbibliothek und `matplotlib` für Visualisierungen.
- Bei Nutzung von JupytherLab muss sich die Datei *PropSetzstrategien.py* im gleichen Verzeichnis wie das benutzte Nootebook befinden.

---

## 📦 weitere Dateien


| Datei | Inhalt |
|----------|--------|
| `Dokumentation-ausfuehrlich.pdf` | ausführliche Dokumentation des Python-Programms (Abb. 2) zur Berechnung von Gewinnwahrscheinlichkeiten|
| `Unterrichtseinsatz.pdf` | Dokumentation zu einem möglichen Unterrichtseinsatz,  didaktische Bemerkungen, mögliche Aufgaben|
| `Berechnung_haendisch-P(200,001)` | Berechnungen zu P(200,001) ohne Rechnereinsatz; Beispiel einer ChatGPT-Kommunikation; Pythonlisting mit Dokumentation, die von ChatGPT erstellt wurde|
| `Uebersicht-ProbSetzstrategien.md` | Übersicht über alle definierten Funktionen in *PropSetzstrategien.py*|


---

## 🧮 Voraussetzungen

- Python ≥ 3.7
- matplotlib
- pandas


## ✍️ Mitwirkende

- [Reimund Vehling]
- Mit KI-Unterstützung von ChatGPT
