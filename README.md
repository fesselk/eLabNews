<!--

author:   Andre Dietrich

email:    dietrich@ivs.cs.uni-magdeburg.de

version:  1.0.0

language: en_US

narrator: US English Female

-->
# eLabNews 23/10/17

__ Markdown-Updates __

Eure Einstellungen bezüglich des Aussehens, der Sprachausgabe, etc.
werden jetzt lokal bei euch im Browser gespeichert, sodass ihr nicht
immer auf die letzte Seite springen müsst oder die Sprachausgabe
ausschaltet.

__ Merke: __ Die Sprachausgabe kann ausgeschaltet werden, einfach auf
das Ohr-Symbol in der Navigationsleiste klicken und ihr wechselt in
den (nicht so coolen) Lesemodus ...

__ Compiler-Output __

Warnings, etc. wurde heraufgesetzt und der Compiler-Output wird euch
in der Konsole ausgegeben.

![Gcc Config](https://raw.githubusercontent.com/liaScript/eLabNews/master/compiler_output.gif)<!-- width: 100% -->

__ Merke: __ Ihr könnt jetzt nur noch Terminal-Eingaben machen, wenn
Ihr ein Programm ausführt, sonst ist die Eingabe deaktiviert, also nicht
wundern ;-)

## Gcc Experimente 19/10/17

Falls ihr selber mit Bitshift-Operationen oder anderen C-Syntax-Elementen
experimentieren wollt, die erstmal nicht zwingend einen Roboter benötigen,
so könnt ihr auch selber Projekte anlegen.

Einfach unter Projects auf __New-Project__ gehen und die __Gcc-Basic__ 
Konfiguration auswählen. Das Terminal funktioniert wie bei Arduino, nur
die Flashzeiten entfallen ;-)

![Gcc Config](https://raw.githubusercontent.com/liaScript/eLabNews/master/gcc.gif)<!-- width: 100% -->

## FrontEnd 19/10/17

Heute gab es ein paar kleine Änderungen im FrontEnd (in der Sandwich-Methode) :

1. __Streams wurden verkleinert__

   Da die hohe Anzahl an Video-Streams (in höchster Qualität) zur Verringerung
   der Bandbreite für Websockets geführt hat, haben wir diese zunächst herunter
   geschraubt, um allen Nutzern eine gute Usability zu ermöglichen.

2. __Enter bei Terminaleingabe__

   Ihr könnt jetzt oder in ganz kurzer Zeit auch ein Enter als Short-Cut für
   die Terminal-Eingabe nutzen. An einem besseren visuellen Feedback für das
   Fläschen ;-) und die Ausführung eures Codes arbeiten wir gerade. Bitte
   beachtet dass es beim Flash-Vorgang auf dem Microcontroller zu Verzögerungen
   (Fläschen-Hals) kommen kann. Habt also ein wenig Geduld und nutzt die
   serielle Ausgabe als Feedback für euch, wann euer Programm startet.
   _ Direkt auf dem Aurduino funktioniert leider auch nicht schneller. _

   ___ Wichtig: Ändert nicht die Baud-Rate von Serial und Serial1 ___

3. __Resizable Editor__

   Da sind wir auch dran, haben das Fenster ersteinmal fix vergrößert, dynamische
   Vergrößerung ist noch nicht möglich, die verwendeten JavaScript-Bibliotheken
   arbeiten nicht so einfach zusammen, als dass das so einfach zu implementieren
   wäre (elm bootstrap-tabs und CodeMirror)...

4. __Am Licht wird gearbeitet__

5. __Danke für die gemeldeten Issues__


## eLabNews 18/10/17

Aller Anfang ist schwer, deshalb haben wir uns entschieden euch auf diesem Wege
über Neuerungen und Bugfixes am System zu informieren ...

### Me Settings

In der Navigationsleiste wurde ein *ME* - Link hinzugefügt, damit könnt ihr eure
persönlichen Einstellungen ändern.

__ Merke: __ Das Passwort wird nur geändert, wenn ihr dort Eingaben macht, sonst
nicht! Und jedes Element kann auch auch selbst für sich alleine geändert werden ;-)

### Verbindungsbug

todo
