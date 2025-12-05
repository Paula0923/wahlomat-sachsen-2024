# Parteipolitisches Mapping Wahl-O-Mat Sachsen 2024

<img src="images/ellipsen_webseite_alle_parteien.png" alt="Ellipsen mit 0.5σ" width="900"/>

## Zusammenfassung der Ergebnisse

a) Mittelwerte auf beiden Achsen*
| Partei    | X | Y     |
|:---------|:-------:|:----------:|
| AfD    | 0.07    |  -0.65  |
| BSW     | -0.2    | 0.04  |
| CDU | 0.73    | -0.39  |
| Die Linke    | -0.73     | 0.83  |
| FDP     | 0.73    |  0.04 |
| Grüne | -0.47     | 0.7  |
| SPD | -0.4    | 0.3  |

b) Streuung der Parteipositionen (in Kategorien)**
| Partei                      | σ X-Achse             | σ Y-Achse |
|:--------------------------------|:---------------|:------------------:|
| AfD | 🔴 | 🟢|
| BSW | 🔴 | 🔴|
| CDU | 🟢 | 🔴 |
| Die Linke | 🟢 | 🟢 |
| FDP | 🟢 | 🔴 |
| Grüne | 🟡 | 🟢 |
| SPD | 🔴 | 🟡 |

*Parteien alphabetisch geordnet, alle Werte auf zwei Nachkommastellen gerundet
** Parteien alphabetisch geordnet; rot = heterogen, grün = homogen

## Daten und Operationalisierung
- Der **Code** für die gesamte Analyse kann [hier](main.ipynb) eingesehen und nachvollzogen werden.
- Grundlage ist der Datensatz des **Wahl-O-Mats Sachsen 2024**, welche [hier](https://www.bpb.de/themen/wahl-o-mat/sachsen-2024/550556/download/) oder in diesem Repo [hier](daten/original/Wahl-O-Mat%20Sachsen%202024_Datensatz.xlsx) abgerufen werden kann.
- Die Analyse wurde auf solche Parteien beschränkt, die entweder in der 7. oder 8. Whalperiode im Sächsischen Landtag vertreten waren (CDU, AfD, Die Linke, Bündnis 90/ Die Grünen, SPD, FDP, BSW).
- Es gab keinerlei Einthaltungen, alle Parteien haben bei jeder Aussage eine Antwortmöglichkeit gewählt.
- **Operationalisierung**: 
    1. Sämtliche Thesen wurden jeweils einer Achse zugeordnet: X-Achse: links-rechts (wirtschaftlich), Y-Achse: konservativ-progressiv (gesellschaftlich).
    2. Daraufhin wurde definiert, ob die Zustimmung bzw. Ablehnung der jeweiligen These progressiv oder konservativ / rechts oder links ist.        
        ➡️ Diese Zuordnungen lassen sich in dieser [Tabelle](daten/wahlomat-sachsen-thesen-achsen-politikfeld-werte.xlsx) nachvollziehen.
    3. Auf dieser Grundlage wurden die Mittelwerte berechnet, wobei sämtliche Thesen gleich gewichtet wurden.
    4. Die Visualisierung der Ergebnisse wurde mit 0.5σ erstellt, da dies übersichtlicher ist. 

