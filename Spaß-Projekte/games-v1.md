# Games


## Inhaltsverzeichnis
1. [Tux Racer](https://tuxracer.sourceforge.net/) - Rennspiel 
2. [Supertux](https://www.supertux.org/) - Jump-'n'-Run


-----------------------------------------------------------------------------------------------------------------------------------------------


# 1. [Tux Racer](https://tuxracer.sourceforge.net/) - Rennspiel 


- Linux, MacOS, Windows


- In dem "Rennspiel" Tux Racer muss man das Linux-Maskottchen `Tux` durch eine Eislandschaft steuern.


- Installation auf Linux:
```
$ sudo apt install extremetuxracer
```

-----------------------------------------------------------------------------------------------------------------------------------------------


# 2. [Supertux](https://www.supertux.org/) - Jump-'n'-Run


- Linux, MacOS, Windows, Android

- Das Spiel Supertux ist ein 2D-Jump-'n'-Run-Spiel, indem man ebenfalls das Linux-Maskottchen `Tux` durch verschiedene Landschaften steuern muss.


### Installation 

- Android
    - [PlayStore](https://play.google.com/store/apps/details?id=org.lethargik.supertux2&hl=en)

- MacOS & Windows
	- [supertux.org/download](https://www.supertux.org/download)

- Linux
    - [AppImage, Linux 32 bit oder flatpakref](https://www.supertux.org/download)
    - [Paketmanager: Flatpak](https://flathub.org/apps/org.supertuxproject.SuperTux)
    - über Paketmanager apt: `$ sudo apt install supertux`


## [Entwicklermodus mit Cheat-Menü in Supertux2](https://github.com/SuperTux/supertux/wiki/Developer-Mode)

- Linux:
```
$ supertux2 --developer
```


- Windows:
	- App-Verknüpfung auf dem Desktop hinzufügen.
	- Mit Rechtsklick auf Eigenschaften gehen.
	- Unter dem Punkt `Verknüpfung` hinter `supertux2.exe` mit einem Leerzeichen ` --developer` ergänzen.
	- Das sollte dann so aussehen: `C:/Benutzer/Pafad/zu/supertux2.exe --developer`
	- Auf "Übernehmen" & "OK" klicken und Spiel starten.


- MacOS:
	- [Finder](https://de.wikipedia.org/wiki/Finder_(Mac)) öffnen & in den Ordner `Applacations` gehen.
	- Rechtsklick auf `SuperTux.app`.
	- In `/Contents/Resources/bin` wechseln,
	- neues Terminalfenster öffnen und mit "Drag and Drop" `supertux2` in das Terminalfenster ziehen.
	- Hinter `.../bin/supertux2` `--developer` mit einem Leerzeichen einfügen.
	- Das spllte dann wie folgt aussehen: `.../bin/supertux2 --developer`
	- Enter drücken.



### Um nun das Cheat-Menü öffnen zu können `F1` drücken.


-----------------------------------------------------------------------------------------------------------------------------------------------


- Bei älteren Versionen von Supertux kann ein anderes Vorgehen erforderlich sein.
	- [Mehr dazu hier](https://github.com/SuperTux/supertux/wiki/Developer-Mode)


-----------------------------------------------------------------------------------------------------------------------------------------------
