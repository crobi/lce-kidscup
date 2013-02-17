Hier meine automatisierte Rangliste. Die farbigen Spalten muss man nach dem Benutzen ausblenden (nur ausblenden, nicht l�schen), dann sieht das ganze gleich aus wie beim Original von Dino.
Einzige �nderung von mir: bei UBS-Goldsprint und der H�rdensprintstafette habe ich die Spalte "Punkte" zu "Zeit" umbenannt, da die Werte in dieser Spalte die Einheit Sekunden haben.

Die Rangliste funktioniert mehr oder weniger wie immer, Tom wird es kennen. @Tom: bitte vorher kurz testen, ob alles funktioniert.

Was die Rangliste kann:
- Automatische Berechnung der R�nge der Disziplinen
- Automatische korrekte Berechnung des Ranges in einer Disziplin bei Punktegleichheit (alle Disziplinen ausser UBS-Goldsprint und H�rdenstafette, wo es zwei Teams auf dem gleichen Rang geben darf)
- Automatische Berechnung der Gesamtrangpunkte
- Automatische Berechnung des Gesamtranges

Was sie nicht kann:
- Automatisch nach Gesamtrang sortieren. Muss man manuell machen (alle Daten-Spalten ausw�hlen, im Men� Daten->Sortieren...)
- Korrekte Behandlung bei Punktegleichheit im Gesamtresultat. Korrigierten Gesamtrang manuell eintragen.

Zur Benutzung:
- Spalten welche die erreichte Punktzahl einer Disziplin enthalten: wie gewohnt manuell eintragen.
- Spalten welche den Rang in einer Disziplin enthalten: nichts eintragen, wird automatisch berechnet. Ausser beim Teamcross, da ist der Rang ja eigentlich die Punkzahl.
- Spalte f�r die Gesamtrangsumme: nichts eintragen, wird automatisch berechnet.
- Spalte f�r den Gesamtrang: nichts eintragen, wird automatisch berechnet. Vor dem Ausdrucken der endg�ltigen Version pr�fen ob doppelte R�nge vorkommen und evtl. manuell korrigieren.
- Rote Spalten: nichts eintragen, beinhalten Zwischenresultate.
- Blaue Spalten: Einzelresultate sortiert eintragen. Wenn z.B. eine Mannschaft 1x4, 1x6, 2x5, und 1x3 Punkte gemacht hat, tr�gt man die Zahl "65543" ein. Also alle Einzelresultate sortieren, dann hintereinander ohne Abstand aufschreiben. Laut Reglement kann man n�mlich bei Punktegleichheit zus�tzlich nach dieser Zahl sortieren (@Tom: bitte meine Logik mit Reglement pr�fen). Wichtig: Fehlende Einzelresultate als "0" eintragen.
- Rote und blaue Spalten vor dem Ausdrucken ausblenden (ganze Spalte markieren, Rechtsklick -> Ausblenden)

Achtung: Die Rangliste produziert fehlerhafte Resultate falls man in einem Einzelresultat mehr als 9 Punkte holen kann (aktuelles Maximum ist 6 Punkte), oder falls eine Mannschaft mehr als 1000 Kegeln trifft im Biathlon (unrealistisch).