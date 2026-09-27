v0.2.0

* Change: Kanalauswahl nach OpenKNX-Standard – eigener Tab "Kanalauswahl" mit einer Zeile je Kanal (Kanal / Prognose-Anbieter / Beschreibung)
* Change: Der Schieberegler "Verfügbare Kanäle" und der Tab "(mehr)" entfallen; ein Kanal wird über "Deaktiviert" beim Prognose-Anbieter abgeschaltet
* Change: Deaktivierte Kanäle erscheinen nicht mehr in der Baumansicht; die Beschreibung bleibt trotzdem eingebbar
* Change: "Bezeichnung" heißt jetzt durchgängig "Beschreibung"
* Breaking: Das Speicherlayout verschiebt sich, da der Kanalzähler entfällt – bestehende Projekte müssen neu parametriert werden

v0.1.0

* Feature: Initiale Implementierung mit forecast.solar-Integration (weltweit, kein API-Key)
* Feature: Solcast-Integration (weltweit, Hobbyisten-API-Key)
* Feature: Konfigurierbare Anlage (Breitengrad, Längengrad, Neigungswinkel, Azimut, Spitzenleistung)
* Feature: Automatische Aktualisierung (30 min / stündlich / täglich)
* Feature: ETS Kontexthilfe (Baggages, HelpContext in XML)
* Doc: Applikationsbeschreibung mit Inhaltsverzeichnis
