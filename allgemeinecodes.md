#### 1. mv (Verschieben / Umbenennen)

Dieser Befehl wird verwendet, um Dateien oder Verzeichnisse zu verschieben oder umzubenennen.

#### Verwendung:

     mv [quelle] [ziel]

Beispiel:

     mv ./Markdown/data3.md ./Markdown2/

Dieser Befehl verschiebt die Datei data3.md aus dem Markdown-Ordner in den Markdown2-Ordner.

---

#### 2. cp (Kopieren)

Dieser Befehl wird verwendet, um Dateien oder Verzeichnisse zu kopieren.

#### Verwendung:

     cp [quelle] [ziel]

Beispiel:

     cp ./Markdown/data3.md ./Markdown2/

Dieser Befehl kopiert die Datei data3.md aus dem Markdown-Ordner in den Markdown2-Ordner.

---

#### 3. rm (Löschen)

Dieser Befehl wird verwendet, um Dateien oder Verzeichnisse zu löschen.

#### Verwendung:


     rm [dateiname]

Beispiel:

     rm ./Markdown/data3.md

Dieser Befehl löscht die Datei data3.md aus dem Markdown-Ordner.

---

#### 4. mkdir (Verzeichnis erstellen)

Dieser Befehl wird verwendet, um neue Verzeichnisse zu erstellen.

#### Verwendung:

     mkdir [neuer-verzeichnisname]

Beispiel:


     mkdir ./Markdown2

Dieser Befehl erstellt einen neuen Ordner mit dem Namen Markdown2.

---

#### 5. rm (Löschen)

Der Befehl rm (remove) wird verwendet, um angegebene Dateien und Verzeichnisse zu löschen. Gelöschte Dateien können nicht wiederhergestellt werden, daher sollte er mit Vorsicht verwendet werden.
Grundlegende Verwendung


     rm [dateiname]

#### Beispiele:

Eine Datei löschen:

     rm datei.txt

Dieser Befehl löscht die Datei datei.txt.

#### Mehrere Dateien löschen:

     rm datei1.txt datei2.txt

Dieser Befehl löscht die Dateien datei1.txt und datei2.txt gleichzeitig.

#### Alle Dateien in einem Verzeichnis löschen:

     rm *.txt

Dieser Befehl löscht alle .txt-Dateien im aktuellen Verzeichnis.

#### Ein Verzeichnis und seinen Inhalt löschen: Um ein Verzeichnis und alle darin enthaltenen Dateien zu löschen, wird die Option -r (rekursiv) verwendet.

     rm -r verzeichnis_name/

Dieser Befehl löscht das Verzeichnis verzeichnis_name sowie alle darin enthaltenen Dateien und Unterverzeichnisse.

#### Ohne Bestätigung löschen: Die Option -f (force) löscht Dateien, ohne eine Bestätigung anzufordern.


     rm -f datei.txt

Dieser Befehl löscht die Datei datei.txt, ohne eine Bestätigung anzufordern.

#### Bestätigung vor dem Löschen anfordern: Die Option -i (interaktiv) fordert vor dem Löschen zur Bestätigung auf.

     rm -i datei.txt

Dieser Befehl fragt den Benutzer vor dem Löschen der Datei datei.txt um Bestätigung.

#### Alle Inhalte eines Verzeichnisses interaktiv löschen:

     rm -ri verzeichnis_name/

Dieser Befehl löscht alle Dateien und Unterverzeichnisse im Verzeichnis verzeichnis_name und fordert für jede Löschaktion um Bestätigung.

#### Wichtige Hinweise

#####  Gelöschte Dateien können nicht wiederhergestellt werden:
 Dateien, die mit dem rm-Befehl gelöscht werden, gelangen nicht in den Papierkorb und können nicht wiederhergestellt werden.

#####  Vor der Verwendung überprüfen:
Es ist eine gute Praxis, den Befehl ls zu verwenden, um die Liste der Dateien zu überprüfen, die Sie löschen möchten.

#### Zusammenfassung

Der rm-Befehl ist ein leistungsstarkes Werkzeug zum Löschen von Dateien und Verzeichnissen. Er sollte jedoch mit Vorsicht verwendet werden, da es möglich ist, versehentlich wichtige Dateien zu löschen. 

---

#### 6. touch (Leere Datei erstellen)

Dieser Befehl wird verwendet, um eine neue Datei zu erstellen (erzeugt eine leere Datei).

####  Verwendung:

     touch [dateiname]

Beispiel:

     touch ./Markdown2/neue_datei.md

Dieser Befehl erstellt eine leere Datei mit dem Namen neue_datei.md im Ordner Markdown2.

---
#### 7. cat (Dateiinhalt anzeigen)

Dieser Befehl wird verwendet, um den Inhalt einer Datei im Terminal anzuzeigen.

#### Verwendung:

     cat [dateiname]

Beispiel:

     cat ./Markdown/data3.md

Dieser Befehl zeigt den Inhalt der Datei data3.md im Terminal an.

---

#### 8. ls (Auflisten)

Dieser Befehl wird verwendet, um die Dateien und Ordner im aktuellen Verzeichnis aufzulisten.

#### Verwendung:

     ls [optionen] [verzeichnis]

Beispiel:

     ls -l ./Markdown2

Dieser Befehl listet die Dateien und Ordner im Markdown2-Ordner detailliert auf.

---

#### 9. cd change direktory (Verzeichnis wechseln)

Der Befehl cd (change directory) wird verwendet, um das aktuelle Arbeitsverzeichnis zu wechseln. Er wechselt in das angegebene Verzeichnis.

#### Verwendung:

     cd [verzeichnis-pfad]

Beispiele:

#### Wechsel zum Heimatverzeichnis:

     cd ~
 
Dieser Befehl wechselt in das Heimatverzeichnis des Benutzers.

#### Bestimmtes Verzeichnis:

     cd ./Markdown

Dieser Befehl wechselt in das Verzeichnis Markdown, das sich im aktuellen Verzeichnis befindet.

#### Oben im Verzeichnis:

     cd ..

Dieser Befehl wechselt in das übergeordnete Verzeichnis des aktuellen Verzeichnisses.

#### Wechsel mit vollständigem Pfad:

     cd /home/benutzer/Dokumente


Dieser Befehl wechselt in das Verzeichnis Dokumente, indem der vollständige Pfad angegeben wird.

#### Zusammenfassung:

Der cd-Befehl wird häufig verwendet, um zwischen Verzeichnissen zu wechseln. Wenn Sie das richtige Verzeichnis erreichen, können Sie mit den Dateien und Ordnern in diesem Verzeichnis arbeiten. 

#### 10. nano Verwendung
Grundlegendes Starten

Um nano zu starten, geben Sie den Befehl zusammen mit dem Namen der Datei in das Terminal ein.

#### Verwendung:

     nano [dateiname]

#### Beispiel:

     nano datei.txt

Dieser Befehl öffnet die Datei datei.txt mit nano. Wenn die Datei nicht vorhanden ist, wird eine neue Datei erstellt.
Nano-Oberfläche

Wenn nano geöffnet wird, sehen Sie am unteren Rand des Bildschirms einige wichtige Befehle und Tastenkombinationen. Die häufigsten Befehle, die in der Regel mit ^ (Control-Taste) verwendet werden, sind:

^O: Datei speichern (Write Out).
^X: Nano schließen (Exit).
^K: Ausgewählte Zeile ausschneiden.
^U: Ausgeschnittene Zeile einfügen.
^G: Hilfe-Menü öffnen.

#### Grundlegende Befehle

#### Datei Speichern:
Um die Datei zu speichern, drücken Sie Ctrl + O. Bestätigen Sie den Dateinamen mit der Enter-Taste.

#### Datei Beenden:
Um Nano zu schließen, drücken Sie Ctrl + X. Wenn Sie Änderungen vorgenommen haben, werden Sie gefragt, ob Sie speichern möchten.

#### Text Hinzufügen und Bearbeiten:
Bewegen Sie den Cursor mit den Pfeiltasten an die gewünschte Stelle und beginnen Sie direkt mit dem Schreiben.

#### Zeile Ausschneiden:
Gehen Sie zur Zeile, die Sie ausschneiden möchten, und drücken Sie Ctrl + K. Diese Zeile wird ausgeschnitten und in den Zwischenspeicher gelegt.

#### Zeile Einfügen:
Um die ausgeschnittene Zeile einzufügen, bewegen Sie den Cursor an die gewünschte Stelle und drücken Sie Ctrl + U.

#### Suchen:
Um im Text zu suchen, drücken Sie Ctrl + W und geben Sie das gesuchte Wort ein.

#### Wichtige Hinweise

Vergessen Sie nicht zu Speichern: Änderungen, die nicht gespeichert werden, können beim Schließen verloren gehen.
Im Terminal: Da nano im Terminal arbeitet, gehen Änderungen nicht verloren, wenn das Terminal geschlossen wird, aber die Datei muss gespeichert werden.

#### Zusammenfassung

nano ist ein einfacher und benutzerfreundlicher Texteditor. Er kann verwendet werden, um grundlegende Bearbeitungsfunktionen leicht durchzuführen. Für komplexere Bearbeitungen können andere Texteditoren bevorzugt werden, aber nano ist für viele Benutzer ausreichend. 

---

#### 11. clear  

löscht das Terminal


#### Verwendung:

     clear

---

#### 12. code 

Es öffnet sich ein neues Vs für den aktuellen Ordner.

#### Verwendung:

     code

---

#### 13. new