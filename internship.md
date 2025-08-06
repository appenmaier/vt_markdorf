## ABAP Development Tools einrichten

- [JDK](https://www.oracle.com/java/technologies/downloads/#java24) herunterladen und installieren
- [Eclipse](https://www.eclipse.org/downloads/) herunterladen und installieren
- Eclipse starten
- Funktion `Help - Install New Software...` ausführen
- Nachfolgende Informationen eingeben und `ENTER` betätigen
  - Work with: `https://tools.hana.ondemand.com/latest`
- Option `ABAP Development Tools` markieren und Durcktaste `Next >` betätigen
- Alles bestätigen und Drucktaste `Finish` betätigen

## Verbindung zur ABAP-Instanz herstellen

- Eclipse starten
- Funktion `Window - Perspective - Open Perspective - Other...` ausführen
- Option `ABAP` auswähöen und Drucktaste `Open` betätigen
- Funktion `File - ABAP Cloud Project` ausführen
- Nachfolgende Informationen eingeben und Drucktaste `Next >` betätigen
  - ABAP Service Instance URL: `https://ac782993-6bb1-4899-afce-159622cd9eab.abap.eu10.hana.ondemand.com`
- Drucktaste `Copy Logon URL to Clipboard` betätigen
- URL in einem Browser-Tab öffnen
- Im Brwoser-Tab nachfolgende Informationen eingeben und Drucktaste `Weiter` betätigen
  - E-Mail oder Benutzername: _Dein Benutzername (siehe unten)_
  - Kennwort: `Welcome1`
- Browser-Tab schließen
- Drucktaste `Finish` betätigen

## ABAP-Entwicklungspaket anlegen

- Rechtsklick auf das erstellte ABAP-Cloud-Projekt
- Option `New - ABAP Package` auswählen
- Folgende Informationen eingeben, Option `Add to favorite packages` auswählen und Drucktaste `Next >` betätigen
  - Name: _Deine Kennung (siehe unten)_
  - Description: _Dein Name_
  - Superpackage: `ZLOCAL`
- Option `Create a new request` auswählen, folgende Informationen eingeben und Drucktaste `Finish` betätigen
  - Request Description: _Dein Name_

### Benutzer

| Name | Benutzername | Kennung |
| - | - | - |
| Leon | TRAIN-01 | Z01 |
| Andrea | TRAIN-02 | Z02 |
| Mike | TRAIN-03 | Z03 |
| Jannik | TRAIN-04 | Z04 |
| Silas | TRAIN-05 | Z05 |
| Arne | TRAIN-06 | Z06 |
| Ruben | TRAIN-07 | Z07 |
| Mattis | TRAIN-08 | Z08 |
| Jonathan| TRAIN-09 | Z09 |
| Lisa | TRAIN-10 | Z10 |
| Liska | TRAIN-11 | Z11 |
| Karina | TRAIN-12 | Z12 |
| Oscar | TRAIN-13 | Z13 |
