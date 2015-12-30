# Article

*Article → Article*

~~In der Artikelverwaltung sind alle im Shop verfügbaren Artikel aufgelistet. Die Suchfunktion ermöglicht ein schnelles Auffinden des gesuchten Artikels. Die Artikel gelangen entweder per Import in den Shop oder werden manuell angelegt.~~

Every available article is listed in the article administration. Using the search function you can easily find the product, you are looking for. The articles are created either via import or manual. 


<br>


#### Basic Data


~~| Beschreibung | Bezeichnung | erforderlich |
| -- | -- | -- |
| **Name** | Benennung des Artikels. Der Name ist erforderlich, um den Artikel im CMS-Backend finden zu können. | ja |
| **Artikelnummer** | Die eindeutige Nummer des Artikels im Shop | nein |
| **Artikeldetailbilder** | Bilder des Artikels. Wenn keine Artikelvorschaubilder definiert sind, wird das erste Bild aus dieser Liste als Standardvorschaubild verwendet. | nein |
| **Standard-Artikelvorschaubilder** | Das Hauptbild des Artikels (wird in den Kategorien angezeigt) | nein |
| **Artikelvorschaubilder** | Da ein Artikel im Shop an vielen Stellen unterschiedlich präsentiert werden kann, ist hier die Möglichkeit geboten, die jeweiligen Vorschaubilder definieren zu können. Ist hier kein Bild für die passende Vorschaugröße definiert, so wird das erste Bild aus den Artikelvorschaubildern verwendet. | nein |
| **Artikeldokumente** | Hier werden die zum Artikel passenden Dokumente zugewiesen (z. B Benutzerhandbuch, technische Beschreibung usw.). | nein |
| **Erstellt am** | Erstellungsdatum / Anlagedatum | nein |
| **Aktiv** | Inaktive Artikel werden im Shop nicht angezeigt. | ja |
| **Tags / Schlagworte** | Wird auf der Artikeldetailseite ausgegeben. Artikel mit gleichen Tags können so in einer Artikelliste ausgegeben werden. | nein |~~



| Designation | Description | required |
| -- | -- | -- |
| **Name** | Name of the article. The name is required to find the article in the CMS backend. | yes |
| **Article Number** | The unique number of the article | no |
| **Detailed Images of the article** | Images of the article. The first image of the list will be used as a standard preview image if there is nothing else defined.  | no |
| **Article Default Preview Images** | Main image of the article (displayed within the categories) | no |
| **Article Preview Images** | In here you can define the individual preview images, because it is possible to present the article in different ways and different points in your shop. The first of the article preview images will be used if there is nothing else defined for a matching preview size. | no |
| **Article Documents** | In here the relevant documents are assigned to the articles (for example  the user guide, the technical descriptions etc.) | no |
| **Date of Creation** | On which date the article was created. | no |
| **Active** | Non active articles will not be displayed in the shop. | yes |
| **Tags / Keywords** | Displayed in the article detail page. Articles with the same tag can be displayed within a list. | no |

<br>


#### Description


~~| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **Kurzbeschreibung** | Eine kurze Zusammenfassung, die den Artikel möglichst treffend beschreibt. Die Anzeige der Kurzbeschreibung ist abhängig vom gewählten Seitentemplate (View), gewöhnlich wird sie in der Artikelliste mit aufegführt. | nein |
| **Beschreibung** | Ausführliche Beschreibung des Artikels auf der Artikeldetailseite | nein |~~


| Designation | Description | required |
| -- | -- | -- |
| **Short Description** | Short and apt summary of the article. If the short description is displayed or not depends on the selected page template (view). Usually it is displayed in the article list. | no |
| **Description** | Detailed description displayed on the article detail page. | no |

<br>

#### Categorie / Attributes


~~| Designation | Description | required |
| -- | -- | -- |
| **Producer / Brand** | Producer or brand | no |
| **Warengruppen** | Forms article groups.ppen selbst können z.B. als Einschränkung bei Zahlmethoden verwendet werden. Die Zahlmethode wäre im Warenkorb nur dann verfügbar, wenn alle Artikel des Warenkorbes mindestens in einer Warengruppe sind.Warengruppen können entweder hier, direkt beim Artikel, angelegt werden oder über *Artikel → Warengruppen*, die Warengruppe wird dann beim Artikel verknüpft (AUSWÄHLEN). | nein |
| **Artikeltyp** | Ein Artikel kann einem oder mehreren frei definierbaren Artikeltypen zugewiesen werden (CD, Download, Produkt usw.). Artikeltypen können z.B. für Suchfilter sowie im Warenkorb zur Anwendung kommen (Downloads z.B. haben keine Versandkosten). | nein |
| **Produktkategorien** | Jeder Artikel kann einer (oder auch mehreren) Kategorie(n) zugewiesen werden und wird dann in der Artikelliste der jeweiligen Kategorie angezeigt. | ja |
| **Hauptkategorie des Artikels** | Befindet man sich gerade nicht auf einer Kategorieseite, welcher der Artikel zugewiesen ist, so wird als Standard die Hauptkategorie zur Generierung der Artikel-URL verwendet. | nein |
| **Artikelmerkmale** | Artikelmerkmale sind Beschreibungen, die den Artikeln zugefügt werden können. Diese Beschreibungen machen eine klare Aussage über den Artikel, z.B. “ist abwaschbar” oder „Blauer Engel“. Für jedes Merkmal kann ein Name, eine Beschreibung sowie ein Icon hinterlegt werden. | nein |
| **Produktattribute** | Produktattribute sind Merkmale, denen unterschiedliche Werte zugewiesen werden können, z.B. “waschbar bei” + zugehöriger Wert “30°C”. Ohne Zuweisung eines Wertes ist dieses Attribut aussagelos. | nein |
| **Auf folgende Shops einschränken** | Falls im System mehrere Shops existieren, kann hier eine Einschränkung der Artikelsichtbarkeit vorgenommen werden. | nein |
| **Zum Arktikel beitragende Personen** | Hier werden Personen oder Firmen hinterlegt, die in die Produktion des Artikels involviert waren (z.B. als Autor oder Sprecher). Die Anzeige ist abhängig vom gewählten Seitentemplate. | nein |
| **Download-Datei** | Hier können Sie diesem Artikel einen Download aus der Dokumentenverwaltung zuweisen. Diese Datei kann vom User erst heruntergeladen werden, wenn der Artikel erfolgreich gekauft wurde. **<u>Wichtig</u>**:Da diese Funktion auch bei Produkten zur Verfügung steht, die nicht explizit als "Download" definiert wurden (z.B. über die Zuweisung eines Lagers namens "Download"), können hier auch sonstige für den Artikel relevanten Files hinterlegt werden - z.B. Firmware-Upgrades für Hardware etc. | nein |~~

| Designation | Description | required |
| -- | -- | -- |
| **Producer / Brand** | Producer or brand | no |
| **Product Group** | Forms article groups. You can use them for example as a limitation wihtin the payment method. So the relevant payment method gets available in the shopping cart, in case of the following: All articles are part of at least one product group. You can create a product group either directly in this step via the article or via *Article → Product Group*. So the product group will be linked to the article (SELECT). | no |
| **Article Type** | An article can be assigned to one or several article types (CD, download, product etc.). Article types are useful to execute the serching filter or use the shopping cart (For example: There are no shipping costs for downloads). | no |
| **Product categories** | Every article can be assigned to one (or several) categories. Thereby it will be displayed within the article list of the corresponding category. | yes |
| **Main category of the article** | If you are not on a category page which is linked to the article the main category will be used for the generation of the article-URLs by default. | no |
| **Article characteristics** | Article characteristics are descriptions which can be attached to the articles. The description sets out clearly on how to deal with an article. For example: „is washable“, „is heat- and cold-resistant“ etc.. It is possible to attach a name, a description and even an icon to every characteristic. | no |
| **Product attribute** | is a characteristic which is assignable to several values. For example: „washable up to“ + corresponding value “30°C“. It is useless if you do not assign them. | no |
| **Limited to the following shops** | If there are several shops existing within the same system it is possible to limit them to the articles which should be visible. | no |
| **Persons who can contribute to an article** | In here you can assign persons or companies, which were involved in the production (for exmaple: an author or speaker). Whether it is displayed or not depends on the selected page template. | no |
| **Download-File** | In here you can assign the correspoding download from the document management to the article. This is only possible, if the user has already bought it.  **<u>Please note</u>**: This function does also exist for products, which are not explicitly defined as a „download“ (for example: Via the allocation of a warehouse called „download“). So you can store any file which ist relevant for the product (for example: Firmware-Upgrade for hardware etc.).| no |

<br>

#### Price / Shipping

~~| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **Preis** | Artikel-Brutto-Preis | ja |
| **Vergleichspreis** | Der Vergleichspreis (UVP) des Artikels (wird für gewöhnlich im Shop durchgestrichen angezeigt, da höher als der eigentliche Preis) | nein |
| **Umsatzsteuergruppe** | Zum Artikel passender Umsatzsteuersatz | nein |
| **Artikel ist versandkostenfrei** | Identifiziert Artikel, die versandkostenfrei versendet werden. | nein |
| **keine Gutscheine zulassen** | JA: im Warenkorb angewendeten Gutscheine wirken sich nicht auf dieses Produkt aus. | nein |
| **keine Rabatte zulassen** | JA: Rabatte werden nicht auf dieses Produkt angewendet. | nein |~~


| Designation | Description | required |
| -- | -- | -- |
| **Price** | Article-Button-Price | yes |
| **Comparison-Price** | The comparison price (UVP) will be normally displayed crossed out in the shop. This one is a little bit higher than the normal one. | no |
| **VAT group** | VAT rate which fits to the article | no |
| **Article with no shipping costs** | Identifies articles, which are delivered without shippig costs. | no |
| **No Vouchers accepted** | YES: Vouchers which will be used in the shipping cart will not be accepted for the product. | no |
| **No Discount accepted** | YES: Discounts will not be accepted for the product. | no |

<br>

#### Content / Sizes / Weight

~~Unter *Inhalt / Maße / Gewicht* können die entsprechenden Angaben zu den Dimensionen des Artikels angegeben werden.~~

Via *Content / Sizes / Weight* you can set information about the dimension of the article.

~~Möchten Sie Grundpreise in Ihrem Shop angeben (z.B. 100g / 5,73 €), hinterlegen Sie die Angaben in den Feldern **Inhalt** (Mengenangabe) und **Maßeinheit des Inhalts** (kg, g, l, ml, usw.).~~

If you want to set the basic price (for example 100g / 5,73 €) in your shop just deposit the information in the box **Content** (quantity) und **Unit of Measurement** (kg, g, l, ml, etc.).

~~Die Maßeinheiten selbst können über das CMS erweitert werden (sh. Kapitel **3.4 Maßeinheiten**).~~

The units of measurement can be extended via the CMS (see chapter **3.4 Units of Measurement**).

<br>

#### Vari

~~Varianten eines Artikels, wie z.B. verschiedene Größen und/oder Farben bei Bekleidung, können mithilfe des Variantengenerators erzeugt werden, sh. Kap. **4.8 Artikelvarianten**.~~

You can create several variations of an article, for example sizes and / or colors of clothes, via the variant generator. See chapter **4.8  Variations of Articles**.

<br>

####Warehouse

~~| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **Lagerbestand** | Auf Lager, verfügbare Artikelanzahl | nein |
| **Bei 0 Bestand Vormerken anbieten** | Sinkt der Bestand auf „0“, wird ein Formular zum Vormerken des Artikels auf der Artikeldetailseite angezeigt. | nein |
| **Lieferstatus** | Ein meist vom Shopbetreiber vorgegebener Status wie „nicht lieferbar“ oder „sofort lieferbar“, der auf der Artikeldetailseite angezeigt werden kann. Im Datensatz des Lieferstatus (Lagerbestandsmeldung) kann definiert werden, ob der Artikel automatisch deaktiviert werden soll, wenn der Bestand 0 ist. Bei NEIN ist der Artikel also immer noch sichtbar, auch wenn der Bestand ≤0 ist. | nein |~~


| Designation | Description| required |
| -- | -- | -- |
| **Stock** | in stock, number of available items | no |
| **offer „Note Stock“ when 0** | When the inventory sinks down to „0“, a formular will get displayed where you can note the article on the artikel detail page. | no |
| **Delivery Status** | is a status given by the shop owner. For example „out of stock“ or „in stock“, which can be shown on the artikel detail page. You can manage your settings if the article should be deactivated automatically if the stock sinks down to 0 via the data set within the inventory report. By clicking NO the article is stays visible in the shop (even the inventory is less than zero). | no |

<br>

#### Cross Selling

~~Im Bereich Cross Selling können mit dem Artikel verwandte Artikel (ähnliche Artikel) verknüpft werden und das Zubehör des Artikels zugewiesen werden. Diese Verknüpfungen werden je nach Shop-Design zur Verkaufsförderung verwendet und werden bei der Ansicht des Artikels mit angezeigt (sh. auch Kapitel **4.9 Produktlisten**).~~

In here you can assign articles with similar ones and even their accessories. This is useful for your sales promotion because they will be displayed in the same article view (see chapter **4.9 Product Lists**).

<br>

#### SEO / Meta

~~| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **SEO Pattern** | Durch die Definition des SEO-Patterns kann genau gesteuert werden, wie der Titel der Artikelseite aussehen soll. **<u>Zur Verfügung stehen</u>**: [{PORTAL_NAME}] - Name des Portals; [{CATEGORY_NAME}] – Kategorie-Name; [{MANUFACTURER_NAME}] – Hersteller-Name; [{ARTICLE_NAME}] - Artikelbezeichnung; [{SHOW}] – zeigt alle Möglichkeiten an; *Wird hier nichts eingetragen, greifen die allgemeinen Einstellungen unter Portale/Webseiten* | nein |
| **Meta-Schlüsselwörter** | Hier werden die Suchmaschinen-relevanten Meta-Schlüsselwörter (meta keywords) hinterlegt.Wird dieses Feld leer gelassen, verwendet der Shop die Kurzbeschreibung des Artikels. | nein |
| **Meta-Description** | Optionale Meta-Beschreibung (description) für die Artikelseite. Wird kein Wert hinterlegt, erstellt das System eine Meta-Beschreibung auf Basis der Artikeldaten. Die Description wird als erläuternder Text bei den trefferlisten in Suchmaschinen angezeigt. | nein |~~


| Designation | Description | required |
| -- | -- | -- |
| **SEO Pattern** | Via the definition of the SEO-Pattern it is possile to manage the look of the title on the article page. **<u>Available</u>**: [{PORTAL_NAME}] – Portal-Name; [{CATEGORY_NAME}] – Category-Name; [{MANUFACTURER_NAME}] – Producer-Name; [{ARTICLE_NAME}] - Article-Designation; [{SHOW}] – shows every opportunity; When there are no settings made the basic settings do apply via Portals / Websites. | no |
| **Meta-Keywords** | In here you can set meta keywords which are relevant to search engines. When no input was made the shop uses the short description of the article. | no |
| **Meta-Description** | Optional Meta-Description for the Artikel-Page. If no value was set the system creates a Meta-Discription with the help of the available information of the article. The description will be displayed with the benefit of an explanatory text within the list of search engines. | no |

~~Unter „Metadaten“ können die Metadaten speziell für dieses Produkt überschrieben werden.~~

Via "Metadata" you can overwrite the metadata for the relevant product.

<br>

#### Searching

~~| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **Gewichtung des Artikels** | Zahl, über die der Rang des Produktes in den Listen gesteuert werden kann. | nein |
| **Virtueller Artikel** | Identifiziert den Artikel als virtuell (real nicht verfügbar). Ein Beispiel für einen virtuellen Artikel könnte ein eBook-Download beim Kauf eines Buches sein. | nein |
| **Ist suchbar** | Definiert, ob der Artikel in den Suchindex aufgenommen wird. | nein |
| **Als neu kennzeichnen** | Optionale Einstellung, die im Design ausgewiesen wird. | nein |~~


| Designation | Description | required |
| -- | -- | -- |
| **Ranking of the Article** | is a number. With that one you can manage the ranking of all products within lists. | no |
| **Virtual Article** | Identifies the article as virtual (does not exist in real-life). For example an e-book-download when buying a book. | no |
| **Is searchable** | Determines if the article will be added to the searching index. | no |
| **Mark as new** | is an optional setting which is shown via the design. | no |


<br>

#### Valuation

~~| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **Anzahl Sterne** | Gibt die durchschnittliche Benutzerbewertung des Produktes an | nein |
| **Kundenrezessionen** | Alle von den Kunden geschriebenen Rezensionen. Je nach Konfiguration | nein |~~

| Designation | Description | required |
| -- | -- | -- |
| **Number of Stars** | Sets the average recession from customers about the product. | no |
| **Customer Recession** | Recessions which are created by customers. Depends on the configuration. | no |

<br>

#### Bundle

| Bezeichnung | Beschreibung | erforderlich |
| -- | -- | -- |
| **Ist ein Bundle** | Bundles werden als echtes Produkt im Shop geführt. Hier muss also eine eigene Beschreibung, eigene Bilder, ein eigener Preis, usw. hinterlegt werden. Um das Bundle als solches zu erkennen, wird das Produkt über „Ist ein Bundle“ als Bundle markiert. Zusätzlich werden alle zu dem Bundle gehörenden Produkte dem Bundle zugewiesen. Bei der Zuweisung jedes Artikels kann die Stückzahl mit angegeben werden. Im Warenkorb und bei allen Berechnungen wird das Bundle ebenfalls als ein Produkt behandelt. | nein |
| **Artikel, die zu diesem Bundle gehören** | Wenn es sich um ein Bundle handelt, können hier die zu dem Bundle gehörenden Produkte hinterlegt werden. **<u>Wichtig</u>**: Alle dem Bundle zugewiesenen Produkte werden dabei ignoriert. Rabatte, Gutscheine, Zahlmethoden, Versandkosten und Mehrwertsteuerregeln gelten also nie für die einzelnen Produkte in dem Bundle, sondern immer nur für das Bundle-Produkt. | nein |

<br>

#### Stats

![](bild air.png)

Liefert eine statistische Kurzübersicht über den Artikel (Verkäufe, Detailaufrufe, durchschnittliche Bewertung, Anzahl der Bewertungen).

Ihre Eingaben speichern Sie über den SPEICHERN-Button oberhalb des Datensatzes oder auch noch bequemer, über Rechtsklick an jeder beliebigen Stelle im Datensatz erreichen Sie das Kontextmenü, welches Ihnen die wichtigsten Editierfunktionen.

| Bezeichnung |Beschreibung |
| -- | -- |
| **Speichern** | Nach erfolgreicher Plausibilitätsprüfung wird der Artikel gespeichert |
| **Kopieren** | Kopiert die Artikeldaten und erstellt einen neuen Artikel |
| **Neu** | Erstellt einen neuen leeren Artikel |
| **Löschen** | Löscht den Artikel |
| **Sprache kopieren** | Felder, die in der aktuellen Sprache nicht übersetzt sind, können aus einer anderen Sprache kopiert werden. Wenn man sich z.B. in der Editiersprache Englisch befindet, kann man so den deutschen Text erst einmal in dieses Feld kopieren, um es zum jetzigen (oder auch späteren) Zeitpunkt zu übersetzen.  |
| **Menü abschalten** | Schaltet bis zum nächsten Seiten-Reload das CHAMELEON-Kontextmenü auf dem rechten Mausklick ab, damit das Standardmenü des Browsers durch Rechtsklick verwendet werden kann. |







