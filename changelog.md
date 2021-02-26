## 0.5 Multibenutzerupdate

Version 0.5 unterstützt die Einrichtung mehrerer Benutzer in einem Durchgang.

## Known Bugs

* Benutzer UI Reagiert nicht während der Einrichtung
* Die Liste der Benutzer von Welchen die Daten bereits eingetragen wurden reagiert nicht auf Änderungen. Diese Funktion wenn möglich nicht benutzen.
* Die Migration eines Benutzers in die Cloud kann eventuell Fehlschlagen und wird Übersprungen.
* Raumpostfächer werden in einigen Fällen nicht umgewandelt
* Wird versucht ein Benutzer zu erstellen dessen UPN schon existiert gibt es Armageddon
* Raumpostfächer werden der Gruppe *WM* oder *StuPra* zugewiesen

## Changelog

 - Erstellen einer Log Datei
 - Hinzufügen einer Debug Ansicht
 - Überarbeitung der UI für die Erstellung mehrere Benutzer
 - Überarbeitung der Ausführungsroutinen für die Erstellung mehrerer Benutzer
 - Raumpostfächer erhalten keine Lizenz mehr
 - Wenn kein Kürzel eingegeben wurde führt dies nun zu einer Fehlermeldung 
