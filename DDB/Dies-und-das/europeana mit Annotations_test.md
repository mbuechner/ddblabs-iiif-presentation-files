### Beschreibung: 
Aus der aktuellen Europeana Newspapers Collection wurde ein Manifest heruntergeladen, dass zahlreiche Annotation enthält. Dabei wurden die Annotation gemäß der von Europeana angestoßen Transformationensszenarie automatisiert aus den ALTO-Volltexten extrahiert und als JSON-Resourcen abgebildet

### Beobachtung:
Die Spezialentwicklung der Europeana funktionierte im alten Frontend unter dem Einsatz von [Leaflet](https://leafletjs.com/), mit dem EInsatz von Mirrador3 im neuen frontend fehlen aktuell jedoch die Plug-ins, um die Annotationen anzuzeigen. Der Mirrador 3 unserer Testumgebung erkennt immerhin Annotationen, kann sie aber nicht ausspielen. 
Fazit: Die Sonderentwicklung von Europeana ist so spezialisiert, dass die Anzeige nicht mit einem standardplayer funktioniert! Mehr dazu vgl. Masterarbeit von P. Dinger

Sparte: Bibliotek

Provider: Europeana

Ursprungsformat: METS/ALTO, EDM

DDB-Objekt (URL): /


### Vorgehen:
IIIF-Maifest von Europeanan heruntergeladen un in neuer Umgebung mit eigener URI implementiert --> die Links auf die Ressourcen (VOLLTEXT, BIBLIOGRAPHIE, CANVAS) bleiben bestehen,
