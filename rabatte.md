# Rabatte

*Rabatte & Gutscheine → Rabatte*

Im System können Rabatte definiert werden, die sich auf den Warenkorb oder auf Teile des Warenkorbs auswirken.

Rabatte können über eine Checkbox aktiviert und deaktiviert oder automatisch über das System für einen bestimmten Zeitraum aktiviert werden.
Bei einem Rabatt kann festgelegt werden, ab welcher Einkaufsmenge oder ab welchem Einkaufswert dieser aktiviert werden soll.

Zusätzlich kann festgelegt werden, ob der Rabatt generell für alle Artikel, nur für bestimmte Kategorien oder nur für bestimmte Artikel gelten soll.

Gilt der Rabatt nur für bestimmte Artikel oder Kategorien, beziehen sich die Einkaufsmengen- und Wertangaben immer auf die Summe der Artikel im Warenkorb, die für diesen Rabatt gelten.

Rabatte können außerdem auf bestimmte Benutzergruppen oder Benutzer sowie bestimmte Länder eingeschränkt werden. 
Hier ist zu beachten, dass so eingeschränkte Rabatte erst zur Anwendung kommen, nachdem sich der Benutzer angemeldet bzw. sein Lieferland gewählt hat.

Generell können Rabatte als absoluter Wert oder als prozentualer Wert angegeben werden. Die prozentuale Angabe bezieht sich auf die für den Rabatt relevanten Artikel. Hier muss also nicht unbedingt der ganze Warenkorb betroffen sein.

Zusätzlich zu der prozentualen oder absoluten Angabe kann ein Gratisartikel bei einem Rabatt hinterlegt werden. Wird ein Rabatt mit einem Gratisartikel angewendet, so wird der Gratisartikel automatisch mit einem 0,- € Wert in den Warenkorb gelegt.

Wird ein Rabatt auf den aktiven Warenkorb oder einen Teil des Warenkorbs mit einem positiven berechneten Wert größer 0 angewendet, so wird der Rabatt unterhalb der Bruttoproduktsumme mit Namen und Wert aufgeführt.

| Bezeichnung | Beschreibung |
| -- | -- |
| **Name** | Bezeichnung des Rabattes |
| **Wert** | Der Wert des Rabattes, der als Absolut- oder Prozentangabe konfiguriert werden kann. Handelt es sich um eine Prozentangabe (siehe Wertart), so bezieht sich die Angabe auf die Summe aller betroffenen Artikel. Absolutwerte werden nicht auf den gesamten Warenkorb verteilt, sondern absteigend auf die Artikel im Warenkorb. Bei einem Rabatt von 10,- € und zwei Artikeln im Warenkorb würde das System versuchen, die 10,- € zuerst auf den ersten Artikel anzuwenden. Sollte es danach einen Restwert geben, wird dieser auf den zweiten Artikel angewendet. |
| **Wertart** | Definiert,  ob es sich bei der Wertangabe um einen Absolutbetrag handelt oder um eine Prozentangabe |
| **Prozentuale Rabatte auf der Produktdetailseite anzeigen** | Prozentuale Rabatte, die nicht auf Warenkorb-Werte (ab X € usw. ...) eingeschränkt sind, können bereits auf der Produktdetailseite berechnet werden und dort als reduzierter Preis angezeigt werden (Anzeige wie bei Verwendung von Vergleichspreisen). Somit können bestimmten Kundengruppen für bestimmte Waren im Shop andere Preise (Rabatte) angezeigt werden, sobald sie eingeloggt sind. WICHTIG: Funktioniert nur, wenn der Rabatt prozentual berechnet wird. |
| **Gratisartikel*** | Ein optionaler Gratisartikel, der bei diesem Rabatt automatisch in den Warenkorb gelegt wird. |
| **Aktiv** | Aktivierung / Deaktivierung |
| **Gültig ab** | Ab welchem Zeitpunkt der Rabatt zugelassen ist |
| **Gültig bis** | Bis zu welchem Zeitpunkt der Rabatt zugelassen ist. |
| **Sortierung** | Die Rabatte werden in der hier definierten Reihenfolge auf den Warenkorb angewendet. |
| **Mindestanzahl betroffener Artikel** | Ab welcher Anzahl betroffener Artikel der Rabatt greifen soll. |
| **Maximalanzahl betroffener Artikel** | Bis zu welcher Anzahl betroffener Artikel der Rabatt greifen soll. |
| **Mindestwert der betroffenen Artikel (Euro)** | Ab welchem Warenwert der betroffenen Artikel der Rabatt greifen soll. Hinweis: Als Basis für den Warenwert wird die Produktsumme ohne die Anwendung anderer Rabatte verwendet. |
| **Maximalwert der betroffenen Artikel (Euro)** | Bis zu welchem Warenwert der betroffenen Artikel der Rabatt greifen soll Hinweis: Als Basis für den Warenwert wird die Produktsumme ohne die Anwendung anderer Rabatte verwendet. |
| **Auf folgende Produktkategorien einschränken** | Filter |
| **Auf folgende Artikel einschränken** | Filter |
| **Auf folgende Kundengruppen einschränken** | Filter |
| **Auf folgende Kunden einschränken** | Filter |
| **Auf folgende Lieferländer einschränken** | Filter |
| **Beschreibung** | Beschreibender Text, wird auf der Produktdetailseite angezeigt |
| **Wann wurde der Cache der betroffenen Artikel zuletzt zurückgesetzt?** | Da Rabatte zeitabhängig aktiviert/deaktiviert werden können, die Rabattinformation bei Artikeln aber gecached werden kann, läuft für diesen Zweck im System ein Cronjob. Jedes Mal, wenn der Cache der Artikel (entweder durch den Cronjob oder durch Speichern des Rabatts) zurückgesetzt wurde, aktualisiert das System hier den Wert. Dadurch kann der Cronjob entscheiden, für welche Rabatte ein Zurücksetzen des Caches notwendig wird. |

*nur verfügbar, wenn das Modul Gratisartikel freigeschaltet ist.

