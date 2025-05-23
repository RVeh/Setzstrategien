# 🧠 Chip-Abräumspiele - Wahrscheinlichkeiten

Ein interaktives Projekt zur Analyse von Chip-Verteilstrategien mit exakten und numerischen Berechnungen zu Gewinnwahrscheinlichkeiten.
Alle Berechnungen erfolgen in Python.

## 🚀 Direkt starten mit Binder - kann einige Zeit dauern

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RVeh/EX_Setzstrategien/HEAD)

---

## 📂 Struktur der Notebooks

| Notebook | Inhalt |
|----------|--------|
| `00_Start.ipynb` | Übersicht und Einstiegspunkt |
| `01_P_A-P_B-P_U.ipynb` | Gewinnwahrscheinlichkeiten beim Ein-Würfel-Spiel |
| `01_EinSpieler_Alle_Verteilungen.ipynb` | Alle Strategien $V$ mit Chipsumme $n$ |
| `01_EinSpieler_3D.ipynb` | 3D-Darstellung für $m = 3$ |
| `02_ZweiSpieler_EX_mit_E_V_und_W.ipynb` | Vergleich: $E(V)$, $E(W)$, $E(V, W)$ |
| `02_Zweispieler_V_gegen_alle.ipynb` | Feste Strategie $V$ gegen alle möglichen $W$ |

---

## 📦 Weitere Hinweise

Alle zentralen Funktionen befinden sich in:

```python
chipspiel_utils.py

```
---

Hinweise zur Nutzung

- Notebooks lassen sich direkt in Jupyter oder auf Binder öffnen.
- Bei Binder oder JupyterLab bitte in der Menüzeile **"Run All Cells"** auswählen, um alle Ausgaben zu erzeugen.
- Das Projekt verwendet die Python-Standardbibliothek und `matplotlib` für Visualisierungen.
- Bei Nutzung von JupytherLab muss sich die Datei *chipspiel.py* im gleichen Verzeichnis wie das benutzte Nootebook befinden.

---

## 📦 Beispielrechnungen

- Berechnungen.pdf

---

## 🧮 Voraussetzungen

- Python ≥ 3.7
- matplotlib
- pandas


## ✍️ Mitwirkende

- [Reimund Vehling]
- Mit KI-Unterstützung von ChatGPT
