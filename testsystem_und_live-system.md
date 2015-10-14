# Testsystem und Live-System

It is basically recommended to first make or test changes on stage (www.[domainname.ending].stage.esono.de). After a successful acceptance the changes will be loaded to the Live-System via Deploy (= copy the entire actual-state of a file system from a development version).



Änderungen sollten grundsätzlich immer zuerst im Testsystem (= Stage) (www.[domainname.endung].stage.esono.de) vorgenommen und getestet werden. Nach erfolgreicher Abnahme werden sie per Deploy (= Kopieren des kompletten Ist-Standes des Dateisystems einer Entwicklungsversion) auf das Live-System überspielt. Die Datenbank und kundenprojektspezifische Mediadaten wie Bilder und Downloads, werden dabei nicht überspielt. Änderungen, die im Livesystem ebenfalls  dargestellt werden sollen, müssen daher dort erneut ins Backend eingegeben werden.