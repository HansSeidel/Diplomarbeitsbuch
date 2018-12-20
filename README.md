# Diplomarbeitsbuch
Dieses Repository enthält das Diplomarbeitsbuch von "Graveyard of Immortals".

##Files richtig erstellen.
1. Eigenen Branch erstellen.

2. Die Files als .md im Ordner "markdown" speichern oder als .tex im Ordner "text" speichern. 
Man kann auch mit LateX in .md Files schreiben.

3. Die geänderten Daten pushen und warten bis sie in das diplomarbeit.tex File eingefügt werden.

4. Für visuelles Feedback kann man die Datei **nach einem commit** in diplomarbeit.tex mit \input{text/filename.tex} oder 
\input{markdown/filename.md.tex} importieren und dann in die cmd makeWin.bat schreiben. Nach dem Ausführen der Datei, kann
 man die Änderungen in diplomarbeit.pdf sehen. Anschließend die Änderungen mit "git stash" wieder verwerfen.