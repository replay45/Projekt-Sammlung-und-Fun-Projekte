# Filme auf Disney+ im Browser unter Linux streamen

`Anleitung verfasst am 13.10.2025`

`verwendeter Browser: Firefox 140.3.1esr`


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 1. Warum ist das Abspielen von Filmen aus Streaming-Plattformen unter Linux ein Problem ?
- [DRM (Digital Rights Management)](https://de.wikipedia.org/wiki/Digitale_Rechteverwaltung)
	- Die meisten Streaming-Dienste nutzen `Widevine DRM` um Inhalte z.B. `vor unerlaubter Nutzung und verbreitung zu schützen`.
	- Für die Urheber ist DRM also eine gute Sache, für Nutzer ist es jedoch eher lästig.
	- Aber nicht nur Filme, sondern auch Musik, E-Books, Bilder oder Software können mit DRM-geschützt werden.
	- Das Abspielen von DRM-geschützten Inhalten ist unter Linux immer wieder ein Problem. Die meisten Browser haben mittlerweile jedoch eine Option, die man aktivieren kann, um Inhalte aufrufen zu können, die DRM-geschützt sind.

- [User-Agent-Blockaden](https://de.wikipedia.org/wiki/User_Agent)
	- Manche Dienste können Linux-Systeme blockieren, indem sie den User-Agent des Browsers überprüfen.
	- Das heißt, die Dienste prüfen den User-Agent und sehen, welches Betriebssystem verwendet wird und blockieren ggf. Linux-Systeme.
	- Hier kann jedoch einfache Abhilfe geschaffen werden, denn der User-Agent kann manuell z.B. zu einem User-Agent von Windows-Systemen angepasst werden, sodass der Anbieter davon ausgeht, dass das Betriebssystem Windows ist.
	- Anleitung dazu weiter unten.

- nicht unterstützte Browser
	- Da die Optimierungen in der Regel für Chromium-basierte Browser vorgenommen werden und [Firefox](https://www.mozilla.org/de/firefox/new/) nicht dazugehört, kann das Verwenden eines Chromium-basierten Browsers wie z.B. den [Brave-Browser](https://brave.com/de/) in einigen Fällen Abhilfe schaffen.


## 2. DRM aktivieren & User-Agent im [Firefox](https://www.mozilla.org/de/firefox/new/) ändern, um Inhalte von Disney+ streamen zu können
- In diesem Beispiel wird erklärt, wie man den [User-Agent](https://de.wikipedia.org/wiki/User_Agent) ändern kann, um unter Linux mit dem Firefox-Browser Inhalte, wie Filme oder Serien von dem Streaming-Dienst Disney+ zu streamen.


### DRM in [Firefox](https://www.mozilla.org/de/firefox/new/) aktivierenm
- Zunächst muss DRM in dem Firefox eingeschaltet werden.
	- Firefox öffnen.
	- Dafür die Einstellungen von Firefox öffnen und zum Reiter `Allgemein` (DE) oder `General` (ENG) wechseln.
	- Zum Punkt `Digital Rights Management` scrollen.
	- Die Option `Play DRM-contolled content` aktivieren.

### User-Agent für Disney+ ändern
- WICHTIG:
	- Der User-Agent wird nur für die entsprechende Webseite von Disney+ angepasst !

- Aktuellen User-Agent für Windows finden & kopieren
	- Folgende Webseite öffnen: [whatismybrowser.com/guides/the-latest-user-agent/chrome](https://www.whatismybrowser.com/guides/the-latest-user-agent/chrome)
	- Nun den User-Agent für Windows10 kopieren.
	- Hinweis: Der User Agent für Windows10 und Windows11 ist identisch.

- User-Agent für Disney+ ändern
	- [Firefox](https://www.mozilla.org/de/firefox/new/) öffnen.
	- `about:config` in die URL-Leiste eingeben und öffnen.
	- Risiko akzeptieren
	- In die Suchleiste der `about:config`-Seite `general.useragent.override.disneyplus.com` eingeben und zu `String` wechseln.
	- Nun auf das `+`-Symbol klicken und in das Feld den aktuellen User-Agent einfügen.
	- Speichern und Firefox neu starten (schließen und erneut öffnen).

- Disney+ öffnen und anmelden
	- Nun sollte auch das Streaming unter Linux über Disney+ im Firefox-Browser funktionieren.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
