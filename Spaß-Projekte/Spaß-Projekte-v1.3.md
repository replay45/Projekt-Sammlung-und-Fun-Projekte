# Spaß-Projekte


## Inhaltsverzeichnis
1. CMatrix - Linux / MacOS / Termux
2. cacafire - Linux / MacOS / Termux
3. Fun Befehle
4. looks like a Hacker - Windows
5. Dino Chrome Hack
6. Hollywood
7. Weltkarte im Terminal


--------------------------------------------------------------


# 1. CMatrix - Linux / MacOS / Termux

### a) Installation

- Installation auf Linux mit apt:
```
$ sudo apt install cmatrix
```

- Termux auf Android mit pkg:
```
$ pkg install cmatrix
```

- Installation auf MacOS mit [HomeBrew](https://brew.sh/) - [hier mehr zu HomeBrew](https://github.com/replay45/Windows-Apple-und-Android/tree/main/Apple)
```
$ brew install cmatrix
```


### b) CMatrix benutzen

- CMatrix starten:
```
$ cmatrix
```

1. zusätzliche Optionen
   - `-b` Bold characters on
   - `-r` rainbow mode
   - `-m` lambda mode


2. Geschwindigkeit ändern:
   - `0` -> am schnellsten
   - `9` -> am langsammsten


3. Farbe ändern:
   - `#` -> orange
   - `!` -> rot
   - `$` -> blau
   - `%` -> lila
   - `&` -> weiß


---------------------------------------------------------------------------


# 2. cacafire - Linux / MacOS / Termux

### a) Installation

- Installation auf Linux mit apt:
```
$ sudo apt install caca-utils
```

- Termux auf Android mit pkg:
```
$ pkg install libcaca
```

- Installation auf MacOS mit [HomeBrew](https://brew.sh/) - [hier mehr zu HomeBrew](https://github.com/replay45/Windows-Apple-und-Android/tree/main/Apple)
```
$ brew install libcaca
```



### b) cacafire benutzen

- cacafire starten:
```
$ cacafire
```


---------------------------------------------------------------------------


# 3. Fun Befehle

### Die Befehle funktionieren in den gängigen Terminals, wie z.B. auf Linux, MacOS, Termux oder Windows.

```
$ color 2 & curl ascii.live/forrest
```

```
$ color a & curl parrot.live
```

---------------------------------------------------------------------------


# 4. looks like a Hacker (Windows)


### WICHTIG: Funktioniert nur unter Windows !

In CMD eigeben:

```
$ color 0a
```
```
$ dir/s
```

- Der Befehl `$ color 0a` ändert die Schriftfarbe in `grün`.
- Der Befehl `$ dir/s` listet alle `Verzeichnisse` im Terminal auf.


---------------------------------------------------------------------------


# 5. Dino Chrome Hack

__Hinweis__:
  - Das offline Spiel läuft lokal auf dem Computer !
  - Daher ist die Ausführung auf eigenen Geräten __nicht__ rechtswiedrig.


### In Chrome, Chromium oder einem Browser, der auf Chromium basiert, (wie z.B. Brave, Opera...) das __offline Game__ "Dino" hacken.


1. In die Adressleiste des Browsers `chrome:dino` eingeben, um das offline Spiel zu starten.
2. Rechtsklick,
3. "Untersuchen" auswählen,
4. im Menü auf "Console" klicken,
5. Befehl eingeben:
```
$ Runner.prototype.gameOver = function (){}
```
6. Enter.


- Wenn automatisch in einer neuen Zeile `ƒ (){}` erscheint, dann wurde der Befehl erfolgreich ausgeführt und das Spiel läuft ohne, dass der Dino bei einem Hindernis stirbt.


---------------------------------------------------------------------------


# 6. Hollywood
- Hollywood ist ein `Demonstartionsprogramm` für das Linux Terminal.
- Hollywood führt `"zur Show" Befehle aus`, und `simmuliert` in einem `drammatischen Layout` ein `"hacker Terminal"` wie man es aus `Filmen` kennt.
- Befehle die von Hollywood verwendet werden, sind z.B. cmatrix, top, htop, atop, dmesg, journalctl, watch, usw.
- Das Ausführen der ganzen Befehle benötigt etwas mehr Ressourcen.

```
$ sudo apt install hollywood
```
```
$ hollywood
```

- Zum Beenden von Hollywood:
	- Option 1: `F6` drücken
	- Option 2: `STRG+C` und danach `$ exit` eingeben


---------------------------------------------------------------------------


# 7. Weltkarte im Terminal
- Über Telnet kann man sich eine Weltkarte im Terminal anzeigen lassen.

### ASCII-Weltkarte mit Telnet
```
$ telnet mapscii.me
```
- Hier kann nun z.B. mit den Pfeiltasten oder mit einer Maus die Karte bewegt und hineingezoomt werden.
- zum Verlassen `q` drücken



---------------------------------------------------------------------------
