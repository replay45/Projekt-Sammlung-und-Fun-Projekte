# Browser & sicher surfen


# 1. anonym & sicher im Internet surfen

- Um anonym surfen zu können, reicht es leider nicht mehr, nur die IP Adresse z.B. über einen VPN zu verschleiern.
Auch wenn die meisten Browser heute viele Cookies blockieren können, können häufig Webseiten über das sogenannte `Fingerprinting` - mehr dazu weiter unten.
Nutzer bzw. Browser wiedererkennen, egal welche IP Adresse diese haben.


- Auch Browser-Erweiterungen wie Werbe-Adblocker können zum Schutz beitragen, sind jedoch genauso wie ein VPN niemals eine Garantie für Anonymität.
Es empfielt sich, **nur** die **nötigsten** Erweiterungen installiert zu haben.
Ein beliebter Open-Source Adblocker ist z.B. der [uBlock Origin](https://ublockorigin.com/de).


- Allerdings kann man z.B. die `Sicherheitseinstellungen` im Browser auf `sicher` oder `am sichersten` stellen und AdBlocker, wie der  [uBlock Origin](https://ublockorigin.com/de), können zum Schutz beitragen, indem sie Tracker blockieren.

Auch ein VPN kann in individuellen Fällen zum Schutz beitragen. Wichtig ist jedoch, dass man sich jedoch niemals auf einen VPN-Anbieter verlässt, denn in einigen Fällen loggen diese die Aktivitäten mit. Insbesondere bei kostenlosen Konten besteht die Gefahr, dass Einnahmen durch das Sammeln und Verarbeiten von Daten erziehlt werden.



### Fazit
Wichtig zu merken ist, dass `anonym zu surfen ein Konzept ist` und nicht durch ein Programm gewährleitet werden kann.
Es ist daher immer notwendig, sich ausführlich zu informieren.



### Was kann man also tun, um die Sicherheit bein browsen zu erhöhen ?

Zunächst empfiehlt es sich, häufiger den privaten Modus des Browsers zu nutzen und zu überlegen, ob man nicht lieber auf einen empfehlenswerteren Browser, wie den [Firefox](https://www.mozilla.org/de/firefox/new/) oder [Brave-Browser](https://brave.com/de/) für den Alltag umsteigen möchte.
Außerdem empfiehlt sich der AdBlocker [uBlock Origin](https://ublockorigin.com/de), um Tracking und Werbung zu meiden.


Wer noch eine Stufe drauflegen möchte, kann z.B. den [Tor-Browser](https://www.torproject.org/) nutzen, jedoch `ACHTUNG`, Tor-Browser bedeutet niemals absolute Anonymität, allerdings gilt der Tor-Browser vergleichsweise als der sicherste.
Wichtig ist dabei jedoch auch die Wahl des Betriebsystems, wer dabei den Tor-Browser auf Windows nutzt, wiederspricht sich, denn Windows ist nicht gerade als besonders datenschutzfreundlich bekannt.
Wer keinen weiteren PC zur Verfügung hat, um Linux nutzen zu können, kann sich z.B. mit einer virtuellen-Maschine Abhilfe schaffen.


Beachte, dass "Tor-Browser" **NICHT** gleich "Dark-Web" bedeutet.
Wer trotzdem ein paar Ausflüge auf ".onion" - Dark-Web-Seiten machen möchte, sollte dies nicht von dem Handy oder alltäglichen System machen, sondern sich mal die Linux-Distribution [Tails](https://tails.net/index.de.html) - [mehr zu Tails in dem Linux-Repository](https://github.com/replay45/Linux_Ethical-Hacking_RaspberryPI/tree/main/linux) anschauen.


Mehr zu Sicherheit auf dem Betriebssystem und Sicherheit & Firewall auf Linux ist in dem Repository [Linux, Ethical-Hacking & RaspberryPI](https://github.com/replay45/Linux_Ethical-Hacking_RaspberryPI/tree/main/linux) zu finden.


## Fingerprinting testen & verhindern


- Ein Browser, der Fingerprinting verhindert bzw. blockiert, ist z.B. der [Brave-Browser](https://brave.com/de/).

- Ob der eigene Browser `Fingerprinting verhintert`, kann hier überprüft werden.
- Fingerprint-Test: [coveryourtracks.eff.org](https://coveryourtracks.eff.org/)




- Ein guter Artikel zur Thematik `sicher surfen` von `wiki.ubuntuusers.de` ist hier zu finden.
- Dieser Artikel war u.a. eine Inspiration für diese kurze Zusammenfassung (Punkt 3): [wiki.ubuntuusers.de](https://wiki.ubuntuusers.de/Sicherheit/Anonym_Surfen/)


---------------------------------------------------------------------------------------------------------------------------------------------------


# 2. Mehr Sicherheit im Heimnetzwerk

Wer mehr Sicherheit in seinem Heimnetzwerk haben möchte, kann [PI-Hole](https://pi-hole.net/), als [DNS-Server](https://de.wikipedia.org/wiki/Domain_Name_System) für alle Geräte im Netzerk nutzen.
Dabei werden alle DNS-Anfragen an den PI-Hole gesendet und dieser kann `Tracking oder auch Werbung filtern`.

PI-Hole kann nach den `eigenen Bedürfnissen angepasst und genutzt` werden. Man kann z.B. PI-Hole nur bei einzelnen Geräten nutzen, indem man die IP-Adresse vom DNS-Server (in diesem Fall PI-Hole) als primären DNS-Server einstellt oder auch für alle Geräte im Netzwerk nutzen. Dafür muss man lediglich in dem Router, bei den meisten wird das eine FritzBox sein, die IP-Adresse vom PC, auf dem PI-Hole installiert ist, als primären DNS-Server setzen.


Es ist `nicht zwingend notwendig` einen [RaspberryPI](www.raspberrypi.com) zu besitzen, um PI-Hole nutzen zu können, dennoch bietet der RaspberryPI einige Vorteile, u.a. wie der vergleichsweise geringe Stromverbrauch.


Wissenswertes zum `RaspberryPI` und mehr zum `PI-Hole` ist in dem Repository [Linux, ethical-hacking & RaspberryPI](https://github.com/replay45/Linux_Ethical-Hacking_RaspberryPI) zu finden.


--------------------------------------------------------------------------------------------------------------------------------------


# 3. BrowserAudit (Browser-Sicherheitstest)

BrowserAudit ist ein webbasierter Dienst zum Testen verschiedener Sicherheitsrichtlinien der Webbrowser. 
Der BrowserAudit-Test enthält aktuell über 400 Tests.


Um den Test auszuführen, muss lediglich die offizielle Webseite besucht werden und auf `Test me` geklickt werden.
Der Test kann einige Minuten in Anspruch nehmen.


> [BrowserAudit](https://browseraudit.com/)


---------------------------------------------------------------------------------------------------------------------------------------------------


# 4. [Brave-Browser](https://brave.com/de/) Dark-Mode für jede Webseite

Hinweis:
- Da der Dark-Mode zum aktuellen Zeitpunkt (Erstellung dieser Anleitung) eine experimentelle Funktion ist, kann es zu Fehlern kommen !


1. Brave-Browser öffnen und in die Suchleiste eingeben:
```
brave://flags/
```

2. Danach nach `dark mode` suchen.

3. Bei `Auto Dark Mode for Web Contents` - `enable` auswählen.


Nun ist der Dark-Mode für jede Webseite aktiviert.

Um den Dark-Mode zu deaktivieren, einfach wieder `disable` auswählen.


--------------------------------------------------------------------------------------------------------------------------------------


# 5. [Brave-Browser](https://brave.com/de/) direkt im privaten Modus öffnen

### Windows

- Ein Desktop-Icon von Brave hinzufügen.

- Rechtsklick und auf `Eigenschaften` gehen.

- Unter dem Punkt `Ziel` ganz an das Ende, hinter die Anführungszeichen mit einem `Leerzeichen` folgendes einfügen:

```
 --incognito
```
- Auf `Übernehmen` und `OK` klicken.

- Nun kann die Verknüpfung u.a. auch an die Taskleiste angeheftet werden.


--------------------------------------------------------------------------------------------------------------------------------------
