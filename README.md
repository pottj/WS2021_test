# WS2021_test


## How to git

1) GitHub Account anlegen (kann dann auch nach dem Semester gelöscht werden)
2) Installiere Git (Link zur Seite) + ggf GUI (nur wenn sie wollen)
    * Username & Email anlegen (im Idealfall passend zum GitHub Account)
3) Finde das Repository und lege eigene Kopie des Repositories an (in GitHub, "fork")
4) lokale Arbeitskopie (Stichwort clone).
    * lokal git-Ordner erstellen (Bsp: "C:/user/docs/myGitProjects")
    * Terminal in diesem Ordner öffnen
    * git clone https://github.com/<username>/WS2021_test/
    * Wechsel in die lokale Arbeitskopie
    * Jetzt kann git genutzt werden :)
    * s. https://rogerdudler.github.io/git-guide/index.de.html
5) Eigenen Branch der Übung anlegen ("branch", Name geeignet wählen, z.B. "Studentname_Übung_i")
6) Check ob alles geklappt hat ("status", "branch --list")
7) Kopie der Übungsdatei im Ordner "Abgabe_i" anlegen (copy paste + umbenennen)
8) Datei mit git tracken ("add", "commit")
9) Übung durchführen & Änderungen tracken ("status","add", & "commit")
10) Zum eigenen Repository synchronisieren ("push")
11) In GitHub mit Orignal zusammenführen ("merging" via "pull request")
12) Freuen, dass es geklappt hat
13) Bei Fragen Issue aufmachen (in GitHub)


 ## Die wichtigsten Kommandos
 
 * git status --> was ist im Repository, welche Veränderungen gibt es?
 * git log --> Commit History wird angezeigt
 * git remote -v --> zeigt upstream repositories (Origin ist WS2021_test)
 * git checkout -b <branch> --> erzeugt und wechselt in neuen Branch
 * git diff <Datei> --> zeige Änderungen an
 * git branch --list --> zeigt Branches an
 * git add <Datei> --> Datei für commit vormerken ("stage")
 * git commit --> alles was vorgemerkt ist wird im neuen Branch gespeichert ("commit")
 * git push origin <Branchname> --> wird auf das Git Repository zurückgespielt
  
