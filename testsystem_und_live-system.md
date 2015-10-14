# Testsystem und Live-System

It is basically recommended to first make or test changes on stage (www.[domainname.ending].stage.esono.de).



Änderungen sollten grundsätzlich immer zuerst im Testsystem (= Stage) (www.[domainname.endung].stage.esono.de) vorgenommen und getestet werden. Nach erfolgreicher Abnahme werden sie per Deploy (= Kopieren des kompletten Ist-Standes des Dateisystems einer Entwicklungsversion) auf das Live-System überspielt. Die Datenbank und kundenprojektspezifische Mediadaten wie Bilder und Downloads, werden dabei nicht überspielt. Änderungen, die im Livesystem ebenfalls  dargestellt werden sollen, müssen daher dort erneut ins Backend eingegeben werden.