# Diplomarbeitsbuch
Dieses Repository enthält das Diplomarbeitsbuch von "Graveyard of Immortals".

## Benötigte Programme
Benötigte Programme befinden sich unter 
> Seidel Hans - G.O.I\05_Management\Diplomarbeitsbuch_Programme

* Pandoc 
    * Wird für das Übersetzen von .md zu .tex benötigt.
* TeXiFy IDEA & LaTeX
    * Sind Plugins für IntelliJ für die Autovervollständigung von .tex code. 
    Nachdem es in IntelliJ neben Plugins auch ein Terminal gibt und eine gute Veranschaulichung der Gitversionierung, wird es empfohlen 
    dieses Programm zu verwenden.

## Files richtig erstellen.
1. Eigenen Branch erstellen.

2. Die Files als .md im Ordner "markdown" speichern oder als .tex im Ordner "text" speichern. 
Man kann auch mit LateX in .md Files schreiben.

3. Die geänderten Daten pushen und warten bis sie in das diplomarbeit.tex File eingefügt werden.

4. Für visuelles Feedback kann man die Datei **nach einem commit** in diplomarbeit.tex mit \input{text/filename.tex} oder 
\input{markdown/filename.md.tex} importieren und dann in die cmd makeWin.bat schreiben. Nach dem Ausführen der Datei, kann
 man die Änderungen in diplomarbeit.pdf sehen. Anschließend die Änderungen mit "git stash" wieder verwerfen.
