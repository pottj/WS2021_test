# WS2021_test

Okay, I wrote a comment instead of a readme ... 
I am confused...


should I make changes here?


To do: How to schreiben

1) GitHub Account anlegen (kann dann auch nach dem Semester gelöscht werden)
2) Installiere Git (Link zur Seite) + ggf GUI (nur wenn sie wollen)
    * Username & Email anlegen (im Idealfall passend zum GitHub Account)
3) Finde das Repository und lege eigene Kopie des Repositories an (in GitHub, "fork")
4) lokale Arbeitskopie (Stichwort clone).
    * lokal git-Ordner erstellen (Bsp: "C:/user/docs/myGitProjects")
    * Terminal in diesem Ordner öffnen
    * git clone https://github.com/pottj/WS2021_test/
    * Wechsel in die lokale Arbeitskopie
    * Jetzt kann git genutzt werden :)
    * s. https://rogerdudler.github.io/git-guide/index.de.html
4) Eigenen Branch der Übung anlegen (Name "Studentname_Übung_i")
5) Wechsel in den neuen Branch
6) Kopie der Übungsdatei im Ordner "Abgabe_i" anlegen (copy paste + umbenennen)
7) Datei mit git tracken
8) Übung durchführen
9) Zum eigenen Repository synchronisieren ("push")
10) In GitHub mit Orignal zusammenführen ("merging" via "pull request")
11) Freuen, dass es geklappt hat
12) Bei Fragen Issue aufmachen (in GitHub)


 ## Die wichtigsten Kommandos
 
 1) git status --> was ist im Repository, welche Veränderungen gibt es?
 2) git log --> Commit History wird angezeigt
 3) git remote -v --> zeigt upstream repositories (Origin ist WS2021_test)
 4) git branch --list --> zeigt branches an (sollte nur den Master-Branch geben)
 5) git add <Datei> --> Datei für commit vormerken ("stage")
 6) git commit --> alles was vorgemerkt ist wird im neuen Branch gespeichert ("commit")
 7) git push origin <Branchname> --> wird auf das Git Repository zurückgespielt
