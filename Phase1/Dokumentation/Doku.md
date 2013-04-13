# Web-basierte Anwendungen 2 - Verteilte Systeme

## Dokumentation zur Phase 1

### Author: Mathias Rothert

## Aufgabe 1

###Wohlgeformt:

Eine XML-Dokument ist Wohlgeformt, wenn es den Regeln von Xml entspricht. 
* Das bedeutet zu Beginn des XML-Dokuments steht eine XML-Deklaration 
(z.B. <?xml version="1.0"?>)
* Es muss ein Root-Element vorhanden sein, welches alle anderen Elemente umschließt.
* Jedes Element welches geöffnet wird muss auch wieder geschlossen werden.

###Validität:

* Ein XML-Dokument ist gültig (valide), wenn es Wohlgeformt ist und der Definition einer DTD oder eines XML-Schemas entspricht.

###Namespace:

* Mit dem Namespace ist es möglich ein XML-Dokument eindeutig zu indentifizieren.
Dies ist zum Beispiel nützlich, wenn man in einem XML-Dokument mehrere XML-Schemas verwendet. 

## Aufgabe 2

* Siehe Aufgabe2.xml und Aufgabe 2.json
* meine erste Idee das XML-Dokument umzusetzen war es Ein Element Person zu erstellen welches ein Attribut „Leiter“ besitzt welches für den Leiter auf „1“ und für normale Mitglieder auf „0“ gesetzt wird. Leider ging die Idee nicht auf, da dann jede Person eine Anmerkung gehabt hätte, was vom Formular nicht so vorgegeben ist. Darum habe ich ein „Leiter“ Element und ein „Person“ Element erstellt.
