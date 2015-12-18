# Dokumente

~~Über den Punkt *Dokumente* gelangt man zur zentralen Dokumentenverwaltung im Chameleon-System. Hier werden alle Daten abgelegt, die den Besuchern der Webseite als Download zur Verfügung gestellt werden sollen.~~

Via *Documents* you get to the central document management of the Chameleon System. Every file is deposit in here. So each visitor browsing the website is able to download them.

~~Von hier aus kann man neue Dokumente hochladen sowie bestehende entfernen oder aktualisieren. Die Verzeichnisstruktur links und die Suchfunktion ermöglichen ein schnelles Auffinden der gesuchten Datei.
Für die genaue Beschreibung der Funktionen aus dem Kontextmenü siehe oberes Kapitel ***2.8 Medien***.~~

In this step you can upload new documents, delete or update existing ones. The directory on the left and the searching functions make it possible to find the relevant folder very quick. See chapter ***2.8 Media*** for a detailed description of the context menus functions.

~~Die Dateigröße darf die unter *CMS / Portal-Einstellungen → CMS Einstellungen → Uploader Konfiguration* eingestellten Werte nicht überschreiten.~~

The file size should not exceed the set values via *CMS / Portal Settings -> CMS settings -> Configuration Upload*

~~Eine Besonderheit der Dokumente ist die Einstellung *geschützt: NEIN/JA*. Für nicht geschützte Dokumente wird ein öffentlich verfügbarer und menschlich lesbarer Link auf die Datei angelegt (http://ww.mydomain.de/chameleon/outbox/public/categoryId/FileName.pdf).~~

A special feature of the documents is the setting point *secure: YES / NO*. If you have an unprotected document a link is created which is easily to read and even available to the public (http://ww.mydomain.de/chameleon/outbox/public/categoryId/FileName.pdf). 

Als *geschützt* markierte Dateien werden hingegen nicht direkt verlinkt, sondern durch einen Download-Manager ausgeliefert (SEO Handler). Dieser reagiert auf eine per config einstellbare URL (Config Konstante: URL_PROTECTED_DOCUMENT_VIRTUAL_OUTBOX). Außerdem kann aktiviert werden, dass der Download nur für angemeldete Benutzer zugreifbar ist (CHAMELEON_CHECK_VALID_USER_SESSION_ON_PROTECTED_DOWNLOADS). Für z.B. kaufbare Downloadprodukte kann alternativ zu Login-Prüfungen ein Download auch mit einem temporären "Schlüssel" (Token) versehen werden, der nach Zeit x ausläuft (einstellbar über: CHAMELEON_DOCUMENT_AUTH_TOKEN_LIFE_TIME_IN_MINUTES)

Protected data is not linked directly. First they run through a download manager (SEO Handler), which responds to a URL set via config (Config Konstante: URL_PROTECTED_DOCUMENT_VIRTUAL_OUTBOX). Thereby it is possible to set that the download is only available to authorized users.