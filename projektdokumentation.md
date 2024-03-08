# Projekt-Dokumentation


Nursiwat Xavier, Girgioni Leonardo

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|08.03.2024       | 0.0.1   | "I" fertig und P angefangen. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Ein Programm erstellen, mit dem man eine Datei komprimieren und dekomprimieren kann.

Wir erstellen ein Programm wo man einzelne oder auch mehrere Dateien komprimieren und dekomprimieren kann. Es ist ein Programm, was auch mit dem Modul 114 zu tun hat. Wir werden das Programm in Pyhton schreiben, damit wir unser Kenntnis über Python erweitern können.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |   Muss	              |Funktion      | Als Benutzer möchte ich eine Datei komprimieren, um Speicherplatz zu sparen.|
| 2  |  Muss	               | Funktion     | Als Benutzer möchte ich eine komprimierte Datei dekomprimieren, um ihren ursprünglichen Inhalt anzuzeigen. |
| 3  |     Sollte	            |  Funktion    | Als Benutzer möchte ich den Fortschritt der Komprimierung sehen, um den Status des Prozesses zu kennen.|
| 4  |     Sollte	            | Funktion     |  Als Benutzer möchte ich den Fortschritt der Dekomprimierung sehen, um den Status des Prozesses zu kennen.|
| 5  |      Kann           |  Funktion    |  Als Benutzer möchte ich mehrere Dateien gleichzeitig komprimieren, um Zeit zu sparen.|
| 6  |     Kann            |  Funktion    |  Als Benutzer möchte ich mehrere Dateien gleichzeitig dekomprimieren, um Zeit zu sparen.|
| 7  |    Muss	             |  Funktion    | Als Benutzer möchte ich eine klare Fehlermeldung erhalten, wenn die Komprimierung oder Dekomprimierung fehlschlägt.|
| 8  |    Kann             | Funktion     | Als Benutzer möchte ich die Komprimierungsrate einstellen, um die Balance zwischen Größe und Qualität zu steuern.|

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |  Eine Datei ist vorhanden	            |Komprimierungsbefehl	        |  Die Datei wird komprimiert und Speicherplatz wird gespart|
|2.1   |Eine komprimierte Datei ist vorhanden	              |Dekomprimierungsbefehl         | Die Datei wird dekomprimiert und der ursprüngliche Inhalt wird angezeigt|
|3.1   | Eine Datei wird komprimiert	             |Keine Eingabe	         |Der Fortschritt der Komprimierung wird angezeigt|
|4.1   |Eine Datei wird dekomprimiert	              |Keine Eingabe	         |Der Fortschritt der Dekomprimierung wird angezeigt|
|5.1   |Mehrere Dateien sind vorhanden|Komprimierungsbefehl	         |Alle Dateien werden gleichzeitig komprimiert|
|6.1   |Mehrere komprimierte Dateien sind vorhanden	              |Dekomprimierungsbefehl         Alle Dateien werden gleichzeitig dekomprimiert|                   |
|7.1   |Eine Datei kann nicht komprimiert/dekomprimiert werden	              |Komprimierung/Dekomprimierungsbefehl	         |Eine klare Fehlermeldung wird angezeigt|
|8.1   |Eine Datei ist vorhanden	              |Komprimierungsbefehl mit Komprimierungsrate	         |Die Datei wird mit der angegebenen Komprimierungsrate komprimiert|




### 1.4 Diagramme



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           | Implementierung der Dateikomprimierung             |               |
| 1.B   |       |           | Testen der Dateikomprimierung             |               |
| 2.A   |       |           | Implementierung der Dateidekomprimierung             |               |
| 2.B   |       |           | Testen der Dateikomprimierung             |               |
| 3.A   |       |           |Implementierung des Fortschrittsbalkens für die Komprimierung	              |               |
| 4.A   |       |           | Implementierung des Fortschrittsbalkens für die Dekomprimierung	             |               |
| 5.A   |       |           |Implementierung der Mehrfachdateikomprimierung	              |               |
| 6.A   |       |           | Implementierung der Mehrfachdateidekomprimierung	             |               |
| 7.A   |       |           | Implementierung der Fehlerbehandlung	             |               |
| 8.A   |       |           | Implementierung der einstellbaren Komprimierungsrate	             |               |


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
