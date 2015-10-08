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
| Code | Identifikationscode des Gutscheins |
| Datum | Erstellungsdatum |
| Verbraucht (Ja / Nein) | Markierungsfeld zur Identifikation, ob Gutschein als verbraucht markiert wurde |
| Verbrauchsdatum | wird hinterlegt, sobald ein Gutschein komplett verbraucht wurde  |
| Restwert | möglicher unverbrauchter Restwert des Gutscheines |

Gutscheine können für alle Benutzer verwendbar sein oder auf bestimmte Benutzergruppen oder Benutzer eingeschränkt werden.

Gutscheine können einen Gutscheinsponsor haben, der für den Gutschein gezahlt hat, siehe *Gutscheinsponsoren*.

Gutscheine, die nicht „gesponsert“ und damit nicht tatsächlich bezahlt sind, dürfen nicht auf Artikel zugreifen, die von Gutscheinen ausgeschlossen wurden. Die für den Gutschein relevante Mindestbestellsumme sowie der Warenkorbwert (der nicht unter Null fallen darf) beziehen sich immer auf die Summe der Artikel, die nicht von Gutscheinen ausgeschlossen wurden. 

Folgende zusätzliche Einstellungen und Einschränkungen sind möglich:

* Über ein Start- und Enddatum kann ein Gutschein auf eine Zeitspanne eingeschränkt werden.
* Es kann ein Mindestbestellwert definiert werden, der überschritten werden muss, bevor der Gutschein akzeptiert wird.
* Ob der Gutschein mit einem anderen Gutschein der gleichen Gutscheinserie verwendet werden kann.
* Ob der Gutschein mit anderen Gutscheinen (egal von welcher Gutscheinserie) verwendet werden kann.
* Ob ein Kunde Gutscheine dieser Gutscheinserie generell nur einmal verwenden darf (also auch nicht bei zwei getrennten Bestellungen).
* Ob der Gutschein nur bei der ersten Bestellung des Benutzers verwendet werden kann.
* Ob der Gutschein die Versandkosten aufheben soll.
* Es ist möglich, den Gutschein als einen „gesponserten“ Gutschein zu markieren. Zusätzlich können der Name des Sponsors, ein Bild und ein Logo hinterlegt werden. „Gesponserte“ Gutscheine ignorieren die Einstellung „keine Gutscheine zulassen“ der Warenkorbartikel im Warenkorb.


Folgende Felder stehen bei der Erstellung einer neuen Gutscheinserie zur Verfügung:



