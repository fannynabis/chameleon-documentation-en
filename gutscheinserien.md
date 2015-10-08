# Gutscheinserien

Rabatte & Gutscheine → Gutscheinserien

Im System können Gutscheine hinterlegt werden, die einen absoluten oder prozentualen Wert als Nachlass gewähren. Prozentuale Nachlässe beziehen sich immer auf die Bruttosumme der Produkte, bevor Rabatte oder ähnliches angerechnet werden. Zusätzlich kann bei einem Gutschein ein Gratisartikel hinterlegt werden (wenn das entsprechende Modul installiert ist). Wird ein solcher Gutschein mit Gratisartikel eingelöst, legt das System den Artikel mit einem Wert von 0,- € in den Warenkorb. Zusätzlich erscheint der Hinweis, über welchen Gutschein der Artikel in den Warenkorb gelegt wurde. Neben dem Hinweis erscheint weiterhin ein Link, über den der Gutschein wieder aus dem Warenkorb genommen werden kann.

Geldwert-Gutscheine erscheinen unterhalb der Produktbruttosumme mit Namen und Wert. Zusätzlich wird neben jedem Gutschein ein Link angezeigt, über den der Gutschein wieder aus dem Warenkorb entfernt werden kann.

Gutscheine werden generell in Gutscheinserien angelegt. Alle Einstellungen beziehen sich auf die Gutscheinserie, und damit auf alle Gutscheine in dieser Serie. Für eine Gutscheinserie können automatisch Gutscheine generiert werden. Hier kann entweder ein fester Gutscheincode angegeben werden oder ein vom System automatisch generierter Code verwendet werden.

Innerhalb einer Gutscheinserie darf ein Gutscheincode mehr als einmal vorkommen, ein Gutscheincode darf aber nie in mehr als einer Gutscheinserie verwendet werden<sup>2</sup>. Bei jedem Gutschein wird ein Erstellungsdatum hinterlegt. 
Der Gutscheinwert selbst wird immer aus der Gutscheinserie genommen (verändert man diesen Wert, verändert sich auch automatisch der Gutscheinwert). Bei jeder Verwendung eines Gutscheins wird das Datum, der Benutzer sowie der Verbrauchswert beim Gutschein in der Gutscheinverwendungsliste hinterlegt. Sobald der Gutschein komplett verbraucht ist, wird das Verbrauchsdatum hinterlegt und der Gutschein als verbraucht markiert. 
Die Gutscheine einer Gutscheinserie können als CSV-Datei exportiert werden. Für jeden Gutschein werden folgende Daten exportiert:

![](bild50.png)

| Bezeichnung | Beschreibung |
| -- | -- |
| Code | 1:2 |
| Datum | 1:3 |
| Verbraucht (Ja / Nein) | 1:4 |
| Verbrauchsdatum | 1:5 |
| Restwert | 1:6 |


