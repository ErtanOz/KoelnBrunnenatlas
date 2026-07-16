# Kölner Brunnenatlas

Interaktive Karte der Kölner Brunnen mit 63 Standorten – ein Werkzeug zur
Datenqualitätsprüfung. Umgesetzt als **eine einzige HTML-Datei** ohne Build-Schritt
([Leaflet](https://leafletjs.com/) über CDN).

## Features

- **Interaktive Karte** mit 63 Brunnen-Standorten, Cluster-freien Markern und
  robustem Kachel-Fallback (CARTO → OSM.de → OSM.org).
- **Suche & Filter** nach Name, Adresse, Stadtteil, Stadtbezirk und Baujahr.
- **Offizielle Fotos der Stadt Köln** für 26 Brunnen (Quelle:
  [stadt-koeln.de](https://www.stadt-koeln.de/leben-in-koeln/freizeit-natur-sport/brunnen/index.html),
  © Stadt Köln). Ohne offizielles Foto wird automatisch in Wikimedia Commons gesucht.
- **Datenprüfungs-Hinweise** je Brunnen (Prüfhinweise, Notizen) – der Datensatz ist
  bewusst „roh", damit Auffälligkeiten sichtbar bleiben.
- **UX**: teilbare Deep-Links (`#b8`), Standort-Anzeige (Geolocation),
  Tastenkürzel `/` für die Suche, Kennzahlen-Übersicht.
- **Barrierefreiheit**: sichtbare Fokus-Ringe, `prefers-reduced-motion`,
  Live-Region für die Trefferzahl.

## Design

Farbwelt und Anmutung sind an das Corporate Design der Stadt Köln angelehnt
(Rot `#ee0000`, Dunkelrot `#a01e28`). Kein offizielles Stadtlogo, damit das Tool
nicht als offizielle Stadtseite auftritt.

## Nutzung

Die Datei [`index.html`](index.html) einfach im
Browser öffnen – keine Installation nötig. Für die Foto- und Karten-Funktionen
wird eine Internetverbindung benötigt.

## Lizenz

[Apache License 2.0](LICENSE)
