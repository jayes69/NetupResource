# NetupResource

RoR Restful Webservice Object Mapper Plugin

Beschreibung

Ein plugin für das Web-Framework Ruby on Rails, welches dem Anwender erlaubt mit APIs zu kommunizieren, als würde man per ORM auf eine Datenbank zugreifen.
Das Plugin benötigt allgemein nicht einmal ein schema für die entsprechende Schnittstelle, da es die Objekte automatisiert und dynamisch n-Dimensional erzeugen kann.
Jedoch ist es auch möglich, ein Schema im Model oder per YAML File zu definieren.

Grundlegend funktioniert das Mappen, indem man Model-Klassen erstellt und diese von der Basis-Klasse des Plugins (statt von ActiveRecord::Base) erben lässt.
Dem Model stehen dann die gängigen 4 Rest-Calls als statische Methoden zur Verfügung. (get,post,put,delete)

Die wenigen, nötigen Konfigurationen finden jeweils im Klassen-Korpus der Modelklasse statt. (siehe Doku)
