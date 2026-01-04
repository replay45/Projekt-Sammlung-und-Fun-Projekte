# alle Suchmaschinen aus einem Browser entfernen - und "leere-Suchmaschine" Browser hinzufügen

`Anleitung erstellt am 7.12.2025`

`getestet mit Chromium basierten Browsern`


### Worum geht es in dieser Anleitung
- In Chromium-basierten Browsern kann man eigentlich nicht alle Suchmaschinen entfernen, da irgendeine eingerichtet sein muss.
- Man kann den Browser jedoch austricksen und einfach eine "leere-Suchmaschine" einfügen.
- Dabei in den Einstellungen für die Suchmaschine folgendes eingeben (das kann natürlich nach Belieben angepasst werden).
- Der Browser wird bei einer Suchanfrage natürlich trotzdem versuchen die Suchanfrage durchzuführen und es wird ein Fehler, wahrscheinlich `This site can't be reached` angezeigt werden.


### Wieso sollte man das tun ?
- Wenn man einen bestimmten Browser nur für bestimmte Funktionen oder Webseiten verwenden möchte und dabei jedoch keine "richtige" Suchmaschine für Suchanfragen aktiv haben möchte kann man eine "leere" Suchmaschine hinzufügen.
- Somit kann man versehentliche Suchanfragen in dem entsprechenden Browser verhindern.


### Einstellungen für "leere-Suchmaschine" setzen:

- Einstellungen des Browsers
- Suchmaschine
- `Hinzufügen` auswählen und folgende Parameter nutzen: 
  - Name: `blank`
  - Shortcut: `blank`
  - URL: `https://about.blank?q=%s`
