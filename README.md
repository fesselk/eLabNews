<!--

author:   Andre Dietrich

email:    dietrich@ivs.cs.uni-magdeburg.de

version:  1.0.0

language: en_US

narrator: US English Female

-->
# eLabNews 19/10/17

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

4. __Danke für die gemeldeten Issues__


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
