**Masterarbeit an der Fachhochschule Südwestfalen im SS2026. Dieses Repository enthält neben der eigentlichen [📄 Masterarbeit PDF](arbeit/Masterarbeit.pdf) des Verfassers den für die Kapitel 4 bis 7 verwendeten Code in Form von Jupyter-Notebooks zwecks Prüfung der Ergebnisse.**

### Thema:

***"Politische Konsistenz im Bundestagswahlkampf 2025: Wie stark spiegeln Bundestagsdebatten die Wahlprogramme der Parteien wider? Ein NLP-basierter Vergleich"***

_("Political Consistency in the 2025 German Federal Election Campaign: How closely do Bundestag debates reflect party manifestos? An NLP-based comparison")_

**Hintergründe zum Thema:**

Diese Masterarbeit untersucht mithilfe von Verfahren des Natural Language Processing, inwieweit sich im Kontext der Bundestagswahl 2025 die Inhalte deutscher Wahlprogramme in den parlamentarischen Debatten des Deutschen Bundestages widerspiegeln. Im Mittelpunkt stehen die im 20. Bundestag vertretenen sechs großen Parteien.

Deren Wahlprogramme und Bundestagsreden werden untersucht hinsichtlich....:
- Formale Textkomplexität: Lesbarkeit und Verständlichkeit
- Themenextraktion, Politikfeldverteilung und zeitliche Dynamik
- Sachfragekonsistenz im Vergleich: Politische Positionierungen zu Kernfragen


**Struktur des Repository**
```text
.
├── arbeit/
│   └── masterarbeit.pdf
├── codes/
│   └── ...pro Kapitel die entsprechenden Notebooks
├── MDB-Stammdaten/
│   └── ...die Stammdaten aller Abgeordneten des Deutschen Bundestages seit 1949
├── wahlprogramme_txt/
│   └── ...die 6 Langtext-Wahlprogramme (CDU/CSU, SPD, Bündnis 90/Die Grünen, Die Linke, FDP, AfD)
│   └── ...die 5 Leichten Wahlprogramme (CDU/CSU, SPD, Bündnis 90/Die Grünen, Die Linke, FDP)
├── wahlprogramme_pdf/
│   └── ...die 6 Langtext-Wahlprogramme (CDU/CSU, SPD, Bündnis 90/Die Grünen, Die Linke, FDP, AfD)
│   └── ...die 5 Leichten Wahlprogramme (CDU/CSU, SPD, Bündnis 90/Die Grünen, Die Linke, FDP)
├── wahlprogramme_json/
│   └── ...die 6 Langtext-Wahlprogramme (CDU/CSU, SPD, Bündnis 90/Die Grünen, Die Linke, FDP, AfD)
│          welche absatzweise eingelesen wurden
├── Bundestagsreden in json - bereinigt um Metadaten und Floskeln/
├── Bundestagsreden in json für Kapitel 6 - bereinigt um Metadaten/
└── README.md

**Lizenz**
keine Lizenz

**Kontakt**
Verfasser der Arbeit: Harry Lohr
