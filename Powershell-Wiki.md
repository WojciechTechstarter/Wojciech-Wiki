# **PowerSchell: Wichtige Grundbefehle**

## **1. Hilfe und Informationen**

**Liste aller verfügbaren Befehle**

`Get-Command`

**Anzeige von Hilfe zu einem Befehl**

`Get-Help <Cdmlet-Name>`

**Eigenschaften und Methoden eines Objekts anzeigen** 

`Get-Member`

## **2. Arbeiten mit Dateien und Verzeichnissen**

**Inhalt eines Verzeichniss anzeigen**

`ls` oder

`Get-ChildItem` oder

`dir`

**Verzeichnis wechseln**

`Set-Location <Pfad-zum-Verzeichnis>` oder

`cd <Pfad-zum-Verzeichnis>`

**Neue Datei erstellen**

`New-Item -Name 'Datei.txt'`

**Neuen Ordner Erstellen**

`New-Item -Name ''MeinOrdner''`

**Datei löschen**  

`Remove-Item Path ''Datei.txt''`

**Ordner mit Inhalt löschen**

`Remove-Item Path ''MeinOrdner''`


## **3. System und Processe**

**Liste der laufende Processe anzeigen**

`Get-Process`

**Program startet**

`Start-Process ''VisualStudioCode.exe''`

**Liste der Systemdienste anzeigen**

`Get-Service`

**Laufenden Dienst stoppen**

`Stop-Service -Name ''XboxNetApiSvc''`

