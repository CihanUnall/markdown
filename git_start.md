# Git - Open Souce Projekt zur Versionskontrolle

## Was ist ein Commit?

Unter dem Beriff 'commit' kann man sich einen Speicherpunkt, in Form eines Kommentares, vorstellen.
Bei der Erstellung eines Commites wird der aktuelle Stand eines Projektes gespeichert, um diesen Stand später aufrufen zu können falls nötig. Um eine Bildliche Vorstellung einem Commits zu haben, könnte man diesen als eine Art Backup/Wiederherstellungpunkt zu sehen.

## Was ist ein Branch?

Stell dir vor, du entwickelst eine Webseite, die bereits Live ist. Nun könntest du neue Features natülich auf dem Main-Branch entwickeln, diese sind dann Live auf der Webseite zu sehen. Um dies zu vermeiden, erzeugt man einen Branch. Ein Branch ist eine Art Kopie des aktuellen Mainbranches. Das bedeutet in dem Momante, in dem du einen Branch erzeugst, wird der aktuelle IST-Zustand, deiner Webseite, in den neuen Branch übernommen.  
Dadurch ist es möglich ein neues Feature direkt in deinem jetzigen Stand der Seite aufzubauen ohne dass sich die Live Webseite ändert.

## Was ist Mergen?

Unter dem Begriff Merge versteht man den Zeitpunkt in dem man den Branch wieder mit dem Main-Branch zusammenführt. An diesem Punkt wird alles was ihr in eurem Branch an Änderungen durchgeführt habt in den Main-Branche implementiert. Am Ende des Merge-Vorganges **muss Commitet** werden.

## Git Commands

|command|Beschreibung|
|---|---|
|git init|Erzeuge/Inizialisiere ein git Repository. Ein Projekt in dem ein git-Repo erzeugt wurde steht unter der Beobachtung von git. Das bedeutet, dass git jegliche Änderungen den den Enthaltenen Datein bemerkt und diese Änderungen speichert.|
|add .|Der `git add` Befehl sorgt dafür, dass git alle Änderungen übernimmt.|
|git commit -m "text"|Nach dem Befehl `git add.` verlangt git, dass ein Commit gemacht wird. Der Erste Commit in einem neuen Projekt sollte immer ein `inital commit` sein.|
|git checkout -b "branchName" oder git switch -c "branchName"|Beide Befehle erzeugen einen neuen Branch. `checkout -b` ist der alte Befehl und wurde von `switch -c` ersetzt. Beide Befehle funktionieren.|
|git clone ...|Mit dem `git clone` Befehl clonst du Repos von GitHub auf dein lokales System um diese bearbeiten zu können.|
|git pull |Bei der Bearbeitung eines Repos auf deinem lokalen System, kann es sein, dass jemand das Repo auf GitHub bereits bearbeitet hat. Um deine geclonte Version auf den neusten Stand zu bringen musst du den pull Befehl einmal ausführen. Der `git pull` Befehl ist eine **Kombination aus `git fetch` und `git merge`!**|
|git push -u origin main|Der `git push` Befehl ist der "upload" auf GitHub. Hierbei muss beim ersten Push `-u origin` + `branchName` angegeben werden.|
|git fetch|Änderungen/Commits, die von Anderen in ihrenen eigenen Branches vorgenommen wurde, werden nicht gepullt. Um diese Informationen zu erhalten gibt es den `git fetch` Befehl.|
|git merge|Der `git merge` Befehl ist das zusammenführen von unterschiedlichen Branches. Bei einem Merge können Merge-Konflikte auftreten, wenn sich beide Versionen voneinander unterscheiden. Diese Merge-Konflikte lassen scih entweder direkt auf GitHub oder in VS-Code lösen.|
|git Status|Mit dem `git Status` Befehl sieht man den Status der Dateien. Dateien, die noch nicht mit dem add Befehl|
|git log|Mit dem `git log` Befehl erhält man Einsicht, die Commit History (Wer, Wann welchen commit gesetzt hat. Ebenfalls sieht man hier den Ccommit Hashtag, mit dem man Projekte zurück setzen kann.|

[mehr Infos zu Git](https://www.atlassian.com/git/tutorials/syncing)


TR

Git - Açık Kaynak Proje için Versiyon Kontrolü
Commit Nedir?

"Commit" terimi, bir yorum şeklinde bir kaydetme noktası olarak düşünülebilir. Bir commit oluşturulduğunda, projenin mevcut durumu kaydedilir, böylece bu duruma daha sonra ihtiyaç duyulursa geri dönülebilir. Bir commit'in görsel bir temsili olarak, bunu bir tür yedekleme veya geri yükleme noktası olarak görmek mümkündür.
Branch Nedir?

Bir web sitesi geliştiriyorsun ve bu web sitesi zaten canlı. Yeni özellikleri doğal olarak ana branch'te geliştirebilirsin, bu da web sitesinde hemen görülebilir. Bunu önlemek için bir branch oluşturursun. Bir branch, mevcut ana branch'in bir kopyasıdır. Yani bir branch oluşturduğun anda, web sitenin mevcut durumu yeni branch'e aktarılır.
Bu sayede, web sitenin mevcut durumunu değiştirmeden yeni bir özelliği geliştirmek mümkündür.
Merge Nedir?

Merge terimi, bir branch'in tekrar ana branch ile birleştirildiği zamanı ifade eder. Bu noktada, branch'inde yaptığın tüm değişiklikler ana branch'e uygulanır. Merge işleminin sonunda commit edilmesi gerekir.
Git Komutları
Komut	Açıklama
git init	Bir git deposu oluşturur/başlatır. Bir git repo oluşturulan bir proje, git'in gözlemi altındadır. Bu, git'in içindeki dosyalarda yapılan değişiklikleri takip edip kaydettiği anlamına gelir.
git add .	git add komutu, git'in tüm değişiklikleri almasını sağlar.
git commit -m "metin"	git add . komutundan sonra git, bir commit yapılmasını talep eder. Yeni bir projedeki ilk commit her zaman initial commit olmalıdır.
git checkout -b "branchName" veya git switch -c "branchName"	Her iki komut da yeni bir branch oluşturur. checkout -b eski komut olup, switch -c ile değiştirilmiştir. Her iki komut da çalışır.
git clone ...	git clone komutu, GitHub'dan reposu yerel sistemine klonlayarak üzerinde çalışmanı sağlar.
git pull	Yerel sisteminde bir repo üzerinde çalışırken, bir başkasının GitHub'da bu repoyu zaten düzenlemiş olabileceğini unutmamalısın. Klonladığın sürümü güncel tutmak için git pull komutunu bir kez çalıştırmalısın. git pull komutu, git fetch ve git merge komutlarının birleşimidir!
git push -u origin main	git push komutu, GitHub'a "yükleme" yapar. İlk push işlemi sırasında -u origin + branchName belirtilmelidir.
git fetch	Başkalarının kendi branch'lerinde yaptıkları değişiklikler/commitler, pull ile alınmaz. Bu bilgileri almak için git fetch komutu kullanılır.
git merge	git merge komutu, farklı branch'lerin birleştirilmesidir. Bir merge işlemi sırasında, her iki versiyon arasında farklılıklar varsa merge çatışmaları meydana gelebilir. Bu merge çatışmaları, doğrudan GitHub'da veya VS Code'da çözülebilir.
git status	git status komutu ile dosyaların durumunu görebilirsin. Henüz add komutuyla eklenmemiş dosyalar görüntülenir.
git log	git log komutu ile commit geçmişini (Kim, ne zaman hangi commit'i yaptı) görebilirsin. Ayrıca burada commit hash'ini görerek projeleri geri alabilirsin.