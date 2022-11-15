# Deer-club
## Projekt-Dokumentation

#Parrot(Deer club): Pascal Oestrich, Keanu Koelewijn, Stefan Jesenko, Dorian Herzig, Lorenzo Lai

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|    25.10.22   | 0.1  | IPE = Informieren/ Planen/ Entscheiden |
|   01.11.22    | 0.2  | R = Realisieren             |
|   08.11.22    | 0.3  |    R = Realisieren / K = Kontrollieren                                                          |

## 1 Informieren

### 1.1 Workshop

In unserem Projekt erstellen wir ein Programm, indem eine gerechte Workshop einteilung gelingen wird.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |      Muss           |   Funktional   | Als Nutzer erwarte ich, dass ich meine Workshops selber eintragen kann. |
| 2  |      Muss           |   Funktional   | Ich als Nutzer erwarte, dass ich die Namen der Teilnehmer selber eintragen kann. |
| 3  |       Muss          |    Funktional  |  Ich als Nutzer erwarte, dass ich die Priorität selber bestimmen kann, damit man die Teilnehmer nach den Prioritäten und anzahl Plätzen einteilen kann. |
| 4  |        Muss         |   Funktional   | Ich als Nutzer erwarte, dass am Ende des Programms, die gegebenen Daten korrekt und gerecht eingeteilt wird. |
| 5  |    Muss             |  Funktional    | Ich als Nutzer erwarte, dass die Mindestangabe der Teilnehmer die Anzahl Workshops * 4 ist um die Mindestgrösse einzuhalten. |
| 6  |        Muss         |    Funktional  |  Ich als Nutzer erwarte, dass der Programm mit Fehler Eingaben umgehen kann. |
| 7  |          Muss       |  Funktional    |  Ich als Nutzer erwarte, dass ich abgefragt werde, nach jeden neuen Teilnehmer, ob ich einen weiteren Teilnehmer hinzufügen möchte, nachdem die Mindestanzahl erreicht wurde. |
| 8  |   Muss              |  Funktional    |  Ich als Nutzer erwarte, dass die Teilnehmer korret gleichmässig verteilt werden in die Workshops und das Resultat ausgegeben wird. |
| 9  |         Muss        |   Qualität   |  Ich als Nutzer erwarte, dass das Program übersichtliche Ausgaben hat, damit man es besser verstehen kann. |
| 10  |         Kann        | Qualität      |  Ich als Nutzer erwarte, dass das Program ein einfaches und gutes Design hat, um eine bessere Erfahrung zu erleben. |
| 11  |    Kann             |    Rand  |  Das Programm wird mit Listen und Funktionen geschrieben. |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm wurde gestartet|         | Bitte drücken sie Enter Nach jeder Eingabe eines Workshops, wenn sie keine mehr hinzufügen wollen geben sie bitte n ein.|
| 1.2  | Programm wurde gestartet, Workshopname Abfrage   |          | Bitte geben sie Workshop 1 ein:|
| 1.3  | Programm wurde gestartet, Workshopname Abfrage   | *Malen*  | Workshop Malen wurde hinzugefügt|
| 1.4  | Workshopname wurde eingegeben | *Enter*  | Bitte geben sie Workshop 2 ein:|
| 1.5  | Programm wurde gestartet, Workshopname Abfrage   | *sieben* | Ungültige Eingabe! Bitte versuchen sie es erneut!  |
| 2.1  | Das Programm fragt, ob man noch einen Workshop hinzufügen möchte |*n*|Vorname und Nachname des Teilnehmers eingeben:|
| 2.2  | Testfall 2.1 | *13* |  Ungültige Eingabe! "Bitte versuchen sie es erneut!", Eingabefeld erscheint  |
| 3.1  | Testfall 2.1  |*Pascal Oestrich*| "Bitte wählen sie einen Workshop für Priorität (1-3)"|
| 3.2  | Testfall 2.1 |  *x*  | Ungültige Eingabe! "Bitte versuchen sie es erneut!", Eingabefeld erscheint |
| 4.1  | Testfall 2.1  |(alle Teilnehmer wurden hinzugefügt)|(Teilnehmer werden gerecht nach den Prioritäten in den Workshops verteilt|
| 5.1  | Testfall 2.1  | *n* |"Sie haben die Mindestanzahl von (4 * Anzahl Workshops) noch nicht erreicht bitte geben sie weitere Teilnehmer ein"|
| 6.1  | Programm wurde gestartet, Workshopname Abfrage |*Buchstabensuppe*| "Ungültige eingabe bitte versuchen sie es erneut", Eingabefeld erscheint|
| 7.1  | genügend Teilnehmer eingegeben (mehr als 4 * Anzahl Workshops)|         |"Sie haben die Mindestanzahl von Teilnehmer erreicht, wenn sie keine Teilnehmer mehr hinzufügen wollen geben sie bitte n ein."|
| 8.1  |Testfall 7.1|*n*|(Eingeteilte Teilnehmer nach Workshop)|

### 1.4 Diagramme

![LA1200--PAP](https://user-images.githubusercontent.com/110892250/197727857-f38caf37-20c7-421a-b46e-1d7b90fe09a3.png)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   25.10.2022    |     Lorenzo      |       Informieren / Userstory       |      1        |
| 1.B |    25.10.2022   |      Kenau     |        Informieren / Testfälle      |       0.5        |
| 1.C |    25.10.2022   |      Stefan     |        Informieren / PAP     |       0.75        |
| 1.D |    25.10.2022   |      Dorian     |        Überprüfen PAP    |       0.5        |
| 2.A |    25.10.2022   |      Pascal / Dorian     |        Planung     |       0.45        |
| 3.A |    25.10.2022   |      Alle    |        Entscheiden / Auswerten      |       1.5        |
| 3.B |    01.11.2022   |      Pascal   |        Teamplanung    |       1        |
| 4.A |    01.11.2022   |      Pascal / Stefan / Dorian   |        Coding    |       5        |
| 4.B |    01.11.2022   |      Dorian / Keanu / Lorzeno   |        List Informieren   |       1        |
| 4.C |    07.11.2022   |      Pascal   |        Teamplanung    |       1        |
| 4.D |    08.11.2022   |      Keanu / Lorenzo    |        Coden von Prioritätauswahl   |       2        |
| 5.A |    15.11.2022   |      Keanu / Stefan / Pascal    |        Programme zusammen setzten   |       2       |
| 5.B |    08.11.2022   |      Dorian    |        Testprotokoll   |       1        |
| 5.C |    08.11.2022   |      Dorian    |        Testen   |       1        |
| 6.A |    15.11.2022   |      Alle    |        Lernbericht / Dokumentation   |       5        |

Total Arbeitspakete: 21,7

45min = 1 Arbeitspaket

## 3 Entscheiden

Die Entscheidung in der Gruppe war das Informieren und die Plannung so zu übernehmen

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  25.10.2022     |     Lorenzo      |     1          |          1         |
| 1.B  |   25.10.2022    |      Keanu     |      0.5         |         1          |
| 1.C  |   25.10.2022    |     Stefan     |      0.75         |         0.75          |
| 1.D  |   25.10.2022    |      Dorian     |      0.5         |         0.45          |
| 2.A  |   25.10.2022    |      Pascal / Dorian    |      0.45       |         0.45          |
| 3.A  |   25.10.2022    |      Alle    |      1.5         |         1          |
| 3.B  |   01.11.2022   |      Pascal    |      1         |         0.5          |
| 4.A  |   01.11.2022   |      Pascal / Stefan / Dorian     |      5         |         5          |
| 4.B  |   01.11.2022   |      Dorian / Keanu / Lorenzo    |      1        |         1          |
| 4.C  |   07.11.2022  |      Pascal     |      1         |         0.5          |
| 5.A |   08.11.2022  |      Keanu / Stefan / Pascal     |      2        |         2          |
| 5.B |   15.11.2022  |      Dorian     |      1        |         Offen          |
| 5.C  |   15.11.2022  |      Dorian     |      1         |         Offen          |
| 6.A  |   15.11.2022  |      Alle    |      5        |         Offen         |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
