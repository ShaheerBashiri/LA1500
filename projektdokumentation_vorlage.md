# Projekt-Dokumentation



| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | Wir haben entschieden was für ein Spiel wir machen wollen. |
|       | 0.0.2   |  Wir haben die Planung für unser Projekt erstellt.                                                            |
|       | 0.0.3   |  Wir haben an der Steuerung und an der Strecke gearbeitet                                                           |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wie programmieren einen Rennsimulator mittels Unity.

Wir wollen ein Rennsimulator erstellen bei welchem man eine Strecke in möglichst kurzer Zeit fahren muss. Dabei soll man mit der Zeit sein Fahrzeug aber auch seine Bestzeit verbessern können. Währenddessen erhoffen wir uns die Grundlagen zu lernen die man braucht, um ein Spiel auf Unity zu erstellen und dieses Wissen uns dann in der Zukunft helfen kann,


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  Kann             |  Qualität     | Als Spieler möchte ich die Möglichkeit haben, meine Statistiken und Erfolge zu verfolgen. |
| 2 |      Muss           | Funktional     | Als Spieler möchte ich verschiedene Schwierigkeitsgrade haben, um meine Fähigkeiten herauszufordern.            |
| 3 |  Muss               |  Qualität    | Als Spieler möchte ich eine ansprechende Grafik und Soundeffekte haben, um das Spielerlebnis zu verbessern.                                  |
| 4 |    Kann             |Qualität      | Als Spieler möchte ich verschiedene Fahrzeuge zur Auswahl haben, um mein Rennen zu personalisieren.                                   |
| 5  |  Kann                |  Qualität    | Als Spieler möchte ich die Möglichkeit haben, mein Fahrzeug zu verbessern, um bessere Leistung zu erzielen.                                   |
| 6 | Muss                | Funktional     | Als Spieler möchte ich eine einfache Steuerung haben, um schnell ins Spiel einzusteigen.                                   |
| 7  |  Muss               | Funktional     | Als Spieler möchte ich eine Pause-Taste haben, um das Spiel jederzeit pausieren zu können.                                   |
| 8 |   Muss              |  Funktional    | Als Spieler möchte ich die Möglichkeit haben, das Spiel zu speichern und später fortzusetzen.                                   |
| 9  |   Kann              |  Qualität    | Als Spieler möchte ich verschiedene Rennstrecken zur Auswahl haben, um das Spiel interessanter zu machen.                                  |
| 10|    Kann             |   Qualität   | Als Spieler möchte ich verschiedene Spielmodi zur Auswahl haben, um Abwechslung zu haben. |
| 11| Kann| Qualität| Als Spieler möchte ich Power Ups haben, dass ich falls ich ein Umfall hatte trotzdem noch gewinnen kann.
|12|Kann| qualität| als Spieler möchte ich, dass mir meine aktuelle Zeit angezeigt wird, damit ich weiss ob ich gut im Rennen liege.
|13|Kann|qualität|als Spieler möchte ich, dass mir während des Rennens angezeigt wird ob sich meine Rundenzeit verbessert hat, damit ich meinen Fortschritt während des Spieles bereits messen kann.
|14 | Kann|Qualität| Als Spieler möchte ich meine Position sehen, um zu wissen ob ich schnell genug bin.|
|15| Kann| Qualität| Als Spieler möchte ich Powerups einsammeln, um mich längsämer oder schneller zu machen.



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |       Rennen beendet       |   Statistikem auswählen      |       Statistiken zum Rennen werden angezeigt            |
| 1.2 |   Mehrere Rennen gefahren           |    Statistiken auswählen     |     Statistiken wie Durchschnitte werden angezeigt              |
|   2.1   |       Schwierigkeitsgrade liegen vor             |      Schwierigkeitsgrad auswählen         |     Rennen wird einfacher/schwieriger           |
|   3.1    |         Rennen gestartet    |        Auto fährt    | Motorgeräusche |
|    4.1       |      Auf Fahrzeug ändern gedrückt                   |     Fahrzeug auswählen        |      Ausgewähltes Fahrzeug wird im Rennen benutzt                |
|     5.1      |            Auf Tuning gedrückt             |    Fahrzeug verbessern         |          Z.B Fahrzeug Geschwindigkeit erhöht            |
|     6.1     |          Rennen gestartet               |       W gedrückt      |       Fahrzeug fährt nach vorne               |
|      7.1     |          Rennen gestartet               |      Pausetaste gedrückt       |       Rennen wird pausiert               |
|     8.1      |         Rennen pausiert                |      Auf Speichern drücken       |         Spielstand wird gespeichert             |
|     9.1      |          Spiel gestartet               |      Strecke auswählen       |          Ausgewählte Strecke wird gefahren            |
|     10.1     |             Strecke ausgewählt            |     Spielmodus auswählen        |      Ausgewählter Modus wird gespielt                |
|      12.1     |          Rennen gestartet               |    Rennen ist im Gange         |        Zeit wird angezeigt              |
|      11.1     |         Powerup ausgewählt                |    Powerup benutzt         |      Bonus wird für bestimmte Zeit aktiv               |
|       13.1    |           Rennen gestartet              |     Zweite Runde beendet        |        Angezeigt ob man besser oder schlechter als in der ersten Runde war              |
|     14.1     |        Rennen gestartet                 |      Den zweiten Platz überholt       |        Platzierung 2. wird angezeigt              |




### 1.4 Diagramme

![image](https://user-images.githubusercontent.com/111045708/220877649-7eb6bdb6-8365-4cfe-9525-89f204322bb0.png)
![UML drawio](https://user-images.githubusercontent.com/111045919/220880882-e41322fd-ae3d-46d9-b49d-58547e065573.png)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 16.03  |Shaheer | Weg und Gestaltung der Erfolge. | 45min |
| 1.B  | 23.03  | Shaheer | Die Erfolge funktionieren und können abgerufen werden.  |45min |
| 2.A  | 09.03  | Giuliano |Menu erstellen welches für die Schwierigkeitsgraden.| 40min |
| 2.B  | 16.03  | Giuliano | Die verschiedenen Schwierigskeitsgrade funktionieren.| 60min|
| 3.A  | 23.03  |Damian | Musik im Menu hinzufügen.|35min|
|3.B|16.03 | Damian|Soundeffekte den Autos hinzufügen.| 40min |
|4.A|16.03|Shaheer|Verschiede Autos ins Spiel hinzufügen.|40min|
|4.B|16.03| Shaheer|Menu erstellen um ein Auto auswählen zu können.| 40min |
|5.A|23.03 | Shaheer| Funktion einfügen bei den Autos, dass man diese verbessern kann.| 30min |
|6.A| 9.03| Giuliano| Steuerung ins Spiel hinzufügen.|50min|
|7.A|9.03| Damian| Pausenknopf hinzufügen und das dieser Aufgerufen werden kann.| 40min |
|7.B|9.03| Damian|Pausenmenu gestallten und das es genutzt werden kann.| 40min |
|8.A|23.03|Giuliano| Möglichkeit den Spielstand zu speichern|40min|
|8.B|23.03|Giuliano| Möglichkeit den Spielstand wiederherzustellen|40min|
|9.A|16.03|Damian| Verschiedene Strecken in das Spiel hinzufügen| 40min|
|10.A|23.03|Shaheer| Verschiedene Spielmodi hinzufügen.| 40min|
| 11.A |  23.03     |     Damian      |     Powerups zum Spiel hinzufügen         |      30 Min         |
|11.B| 23.03|Damian|Effekt der Powerups integrieren|40 Min|
| 12.A   |   16.03    |  Giuliano     |    Rundenzeit ins Spiel einbauen        |    30 Min    |
|13.A| 16.03| Giuliano| Vergleich zur letzten Rundenzeit wird angezeigt| 45 Min|
|14.A|9.03|Shaheer| Platzierung zum Spiel hinzufügen|60min|
|15.A|16.03| Damian| Powerups mit Modell und das sie funktionieren ins Spiel einfügen|60min|

Total: 800 min


## 3 Entscheiden

Wir haben uns entschieden nicht alle User-Stories zu machen, da wir durch das Modul hindurch gemerkt haben, dass wir viel zu wenig Zeit eingeplant hatten.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 4.A  | 09.03.2023 | Shaheer  |       40min        |  60min |
| 6.A  | 09.03.2023      |    Giuliano       | 50min   | 70min |
| 9.A  | 09.03.2023      |   Damian  |  40min  |60min |
| 6.A  | 16.03.2023      |    Giuliano       | 50min   | 180min |
| 9.A  | 16.03.2023      |   Damian  |  40min  |180min |
| 6.A  | 23.03.2023      |    Giuliano       | 50min   |  60min |
| 3.B  | 23.03.2023      |   Damian  |  40min  | 60min |
| ...  |       |           |               |                   |



## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 06.04.22|Fahrzeug fährt| Eisenring|
| 2.1  | 06.04.22|es gibt eine Strecke|Eisenring|
| 3.1  | 06.04.22|es gibt verschiedene Fahrzeuge|Eisenring|
| 4.1  | 06.04.22|Fahrzeug hat Musik|Eisenring|
| ...  |       |          |        |

### Fazit
Alles was wir bearbeiten konnten funktionierte, dabei hatten wir ein grosses Problem in der Planung, da wir uns viel zu viel vorgenommen hatten. Obwohl wir das erstemal mit Unity gearbeitet haben.


## 6 Auswerten

[Link](https://github.com/ShaheerBashiri/LA1500/blob/main/Lernbericht.md)
