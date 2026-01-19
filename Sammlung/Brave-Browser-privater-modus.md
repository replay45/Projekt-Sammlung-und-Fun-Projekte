# [Brave-Browser](https://brave.com/de/) direkt im privaten Modus öffnen


### Windows

- Ein Desktop-Icon von Brave auf dem Desktop hinzufügen (falls noch nicht vorhanden).
- Rechtsklick auf das Desktop-Icon und auf `Eigenschaften` gehen.
- Unter dem Punkt `Ziel` ganz an das Ende, hinter die Anführungszeichen mit einem `Leerzeichen` folgendes einfügen:
```
 --incognito
```
- Auf `Übernehmen` und `OK` klicken.
- Rechtsklick auf das modifizierte Desktop-Icon und `Anheften an Taskleiste` auswählen.


### Linux

`In diesem Fall wurde Brave über Flatpak instlliert, daher müssen ggf. die Pfade angepasst werden, wenn Brave über einen anderen Paketmanager installiert wurde.`


- Für Brave über Flatpak in folgenden Pfad wechseln:
```
$ cd /var/lib/flatpak/app/com.brave.Browser/current/active/export/share/applications
```
```
$ ls
```
```
$ sudo nano com.brave.Browser.desktop
```

- Die Zeile, die mit `Exec=` beginnt, ändern:
    - Mit `STRG+W` suchen
```
Exec=flatpak run com.brave.Browser --incognito %U
```
```
$ reboot
```


----------------------------------------------------------------------------------------------------------------
