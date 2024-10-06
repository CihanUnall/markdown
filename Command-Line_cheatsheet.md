# Command-Line Cheatsheet

## Navigation und Dateioperationen

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `pwd`                                | Zeigt das aktuelle Verzeichnis (Pfad) an.            |
| `ls`                                 | Listet Dateien und Verzeichnisse im aktuellen Verzeichnis. |
| `ls -a`                              | Listet alle Dateien, inklusive versteckter.          |
| `cd <Verzeichnis>`                   | Wechseln in ein Verzeichnis.                         |
| `cd ..`                              | Eine Ebene nach oben wechseln.                       |
| `mkdir <Verzeichnisname>`            | Erstellt ein neues Verzeichnis.                      |
| `touch <Dateiname>`                  | Erstellt eine leere Datei.                           |
| `rm <Dateiname>`                     | Löscht eine Datei.                                   |
| `rm -r <Verzeichnisname>`            | Löscht ein Verzeichnis und dessen Inhalt.            |
| `cp <Quelle> <Ziel>`                 | Kopiert eine Datei oder ein Verzeichnis.             |
| `mv <Quelle> <Ziel>`                 | Verschiebt oder benennt eine Datei/ein Verzeichnis um.|
| `cat <Dateiname>`                    | Zeigt den Inhalt einer Datei an.                     |

## Datei- und Textsuche

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `find <Pfad> -name <Dateiname>`      | Sucht nach einer Datei in einem Verzeichnis.         |
| `grep <Suchbegriff> <Dateiname>`     | Sucht nach einem Text in einer Datei.                |
| `grep -r <Suchbegriff> <Pfad>`       | Sucht rekursiv nach einem Text in Dateien eines Verzeichnisses. |
| `less <Dateiname>`                   | Zeigt den Inhalt einer Datei seitenweise an.         |

## Datei- und Verzeichnisinformationen

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `ls -l`                              | Zeigt detaillierte Informationen über Dateien an.    |
| `du -h`                              | Zeigt die Größe von Dateien und Verzeichnissen an.   |
| `df -h`                              | Zeigt die Festplattenbelegung an.                    |
| `stat <Dateiname>`                   | Zeigt detaillierte Informationen über eine Datei an. |

## Systeminformationen

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `uname -a`                           | Zeigt Informationen über das Betriebssystem an.      |
| `top`                                | Zeigt laufende Prozesse und CPU-Nutzung in Echtzeit. |
| `ps aux`                             | Zeigt alle laufenden Prozesse an.                    |
| `whoami`                             | Zeigt den aktuellen Benutzer an.                     |
| `uptime`                             | Zeigt an, wie lange das System läuft.                |
| `date`                               | Zeigt das aktuelle Datum und die Uhrzeit an.         |

## Netzwerk

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `ping <Adresse>`                     | Sendet Pakete an eine Adresse, um die Verbindung zu testen. |
| `ifconfig`                           | Zeigt Netzwerkschnittstellen und IP-Adressen an.     |
| `curl <URL>`                         | Fordert eine Webseite oder Datei von einer URL ab.   |
| `wget <URL>`                         | Lädt eine Datei von einer URL herunter.              |
| `ssh <user>@<host>`                  | Stellt eine SSH-Verbindung zu einem Server her.      |

## Dateiberechtigungen

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `chmod <Modus> <Dateiname>`          | Ändert die Berechtigungen einer Datei.               |
| `chown <Benutzer>:<Gruppe> <Dateiname>` | Ändert den Besitzer einer Datei.                     |
| `umask <Modus>`                      | Zeigt oder setzt den Standard-Dateiberechtigungsmodus. |

## Archive und Kompression

| Befehl                               | Beschreibung                                         |
|--------------------------------------|------------------------------------------------------|
| `tar -cvf <Archivname>.tar <Dateien>`| Erstellt ein tar-Archiv.                             |
| `tar -xvf <Archivname>.tar`          | Entpackt ein tar-Archiv.                             |
| `zip <Archivname>.zip <Dateien>`     | Erstellt ein zip-Archiv.                             |
| `unzip <Archivname>.zip`             | Entpackt​⬤