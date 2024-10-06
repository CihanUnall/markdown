#### 1. Git Konfiguration
Mit dem Befehl `git config` können Sie die Konfiguration zwischen Ihrem Computer und Ihrem GitHub-Konto einrichten. Dazu können Sie folgendes Beispiel verwenden:

     git config --global user.name "[Name]"
     git config --global user.email "[E-Mail-Adresse]"

     git config --global --list

Überprüfung der Konfiguration
        
---

### 2. Repository Initialisieren

Mit dem Befehl git init können Sie eine Datei auf Ihrem Computer im Git-System bekannt machen. Dazu können Sie folgendes Beispiel verwenden:

     git init

 In einem Ordner git initialisieren
 
     git init [Repository-Name]

----
### 3. Repository Klonen

Mit dem Befehl git clone können Sie ein Repository von Ihrem Konto auf Ihren Computer kopieren und ein Klon erstellen. Dazu können Sie folgendes Beispiel verwenden:

     git clone [URL]

---

### 4. Datei Hinzufügen

Mit dem Befehl git add können Sie eine Datei zu Ihrem aktuellen Repository hinzufügen. Dazu können Sie folgendes Beispiel verwenden:

     git add [Dateiname]

     git add "file name"  z.b. git add index.html

bestimmte Dateien zur Versionskontrolle hinzufügen
                
     git add .

  Alles was untracked ist, zur Versionskontrolle hinzufügen  

---


### 5. Änderungen Speichern

Mit dem Befehl git commit können Sie Änderungen dauerhaft speichern und sicherstellen, dass Ihre Teamkollegen darüber informiert werden. Dazu können Sie folgendes Beispiel verwenden:

     git commit -m "[Ihr Commit-Nachricht]"

     git commit -m "meine Nachricht"

"Sie schreiben Ihre Änderungen als Kommentar, damit ersichtlich ist, welche Änderungen Sie vorgenommen haben."

---     

### 6. Branches Auflisten

Mit dem Befehl git branch, einem der wichtigsten Befehle, können Sie alle erstellten Branches auflisten. Um einen neuen Branch zu erstellen, sollten Sie den folgenden Befehl ausführen:

     git branch [Branch-Name]

     git checkout -b branchName    

Wir erstellen eine Branch (eine unabhängige Kopie des Hauptprojektes)
Dieser Befehl erstellt die Branch (engl. für Abzweigung) und wechselt auf diese Branch    

---

![AlternativText](./image/branch.png)

---

### 7. Branch Zusammenführen

Mit dem Befehl git merge können Sie einen erstellten Branch einfach mit der Hauptdatei zusammenführen. Dazu können Sie folgendes Beispiel verwenden:

      git merge [Branch-Name]

Auf einen existierenden Branch (engl. für Abzweigung) wechseln, können wir mit 

      git checkout branchName

---

### 8. git version

Es zeigt Ihnen die Git-Version.

      git --version

---

### 9. git Ordnerkontrolle

      ls -la

Versteckte Dateien/ Ordner im repository anzeigen, wenn wir den Ordner .git sehen, ist es die Bestätigung das git (Versionskontrolle) im Repo initialisiert wurde  

---


