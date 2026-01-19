# Exposed-Host

`Anleitung erstellt am 18.1.2026`

-------------------------------------------------------------------------------------------------------------


# Was ist ein Exposed Host / DMZ-Host ?

- Was ist ein Exposed Host / DMZ-Host ?
    - In der [FritzBox](https://avm.de/) heißt die Möglichkeit, ein Gerät direkt mit dem Internet zu verbinden, ohne Verwendung der [Firewall](https://de.wikipedia.org/wiki/Firewall) der FritzBox `"Exposed Host"`.
    - Bei anderen Herstellern kann diese Option anders heißen.
    - Beim "Exposed Host" geht es darum, ein Gerät direkt mit dem Internet zu verbinden, das bedeutet, dass das Gerät NICHT durch die Firewall der FritzBox geschützt ist, was ein potentielles Sicherheitsrisiko sein kann !
    - Diese Funktion ist jedoch nützlich, wenn die FritzBox "nur" als [Modem](https://de.wikipedia.org/wiki/Modem) arbeitet und ein WAN-[Router](https://de.wikipedia.org/wiki/Router) als Firewall agiert und das Netzwerk bereitstellt.


- Gründe für die "Exposed Host"-Funktion
    - Es gibt Szenarien, in denen diese Funktion sinnvoll eingesetzt werden kann, z.B. wenn die 
 "nur" als DSL/Glasfaser "[Modem](https://de.wikipedia.org/wiki/Modem)" fungieren soll und der eigentliche (WAN)-[Router](https://de.wikipedia.org/wiki/Router) für das Netzwerk, direkt mit dem Internet verbunden sein soll, denn viele "Router" und auch Enterprise-"Router" können nur "WAN" und haben kein "Modem" verbaut und benötigen z.B. eine FritzBox, die als "Modem" arbeitet.


- Was ist eine DMZ ?
    - Eine [Demilitarisierte Zone (DMZ)](https://de.wikipedia.org/wiki/Demilitarisierte_Zone_(Informatik) ist in der Regel ein eigenständiges Netzwerk, welches zwischen einem internen und einem externen Netzwerk liegt.
    - Eine DMZ kann z.B. zwischen dem Internet und dem internen Netzwerk liegen.
    - Man bezeichnet die DMZ auch als "Pufferzone", denn in einer DMZ werden in der Regel Server betrieben, die über das Internet erreichbar sein sollen.
    - An die DMZ wird dann erst das interne Netzwerk angeschlossen und durch [Firewall](https://de.wikipedia.org/wiki/Firewall) abgesichert.
    - Somit ist das interne Netzwerk nicht direkt, sondern nur über die DMZ an das Internet angeschlossen und genießt somit in der Regel den Schutz mehrerer Firewalls.
    - [Skizzen/ Modelle](https://de.wikipedia.org/wiki/Demilitarisierte_Zone_(Informatik)) verdeutlichen den typischen Aufbau von Netzwerken mit einer DMZ.


### WICHTIG: Sicherheitsrisiko des "Exposed Host"
- Ein Exposed Host, ist `NICHT` durch die [Firewall](https://de.wikipedia.org/wiki/Firewall) der [FritzBox](https://avm.de/) geschützt !
- Das bedeutet, dass das Gerät direkt mit dem Internet verbunden ist !
- Es empfiehlt sich dringend, dass dieser Exposed Host eine `aktive Firewall hat` und regelmäßig mit `Sicherheitsupdates` versorgt wird !
- Grundsätzlich ist es sicherer, Portfreigaben für einzelne Geräte festzulegen, statt der "Exposed Host"-Funktion, falls also Portfreigaben ausreichen sollten, wäre das die sicherere Variante.


# Wie kann man einen [Exposed Host in einer FritzBox](https://fritz.com/apps/knowledge-base/FRITZ-Box-7590/131_Exposed-Host-in-FRITZ-Box-einrichten) einrichten ?
- Web-Oberfläche der [FritzBox](https://avm.de/) öffnen und einloggen.
- In der Menüleiste zu `Heimnetz` > `Netzwerk` navigieren.
- Das `gewünschte Gerät auswählen` und auf `Bearbeiten`, dazu muss es entweder mit dem Netzwerk verbunden sein, oder mal in der Vergangenheit verbunden worden sein, damit die FritzBox das Gerät in die Liste der "bekannten Geräte" aufnimmt.
- Nun dem entsprechenden Gerät eine feste IP Adresse zuweisen, bzw. in der FritzBox festlegen, dass dem Gerät immer die selbe [IP-Adresse](https://de.wikipedia.org/wiki/IP-Adresse) zugewiesen werden soll (sofern die FritzBox als [DHCP-Server](https://de.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol) verwendet wird, was per default der Fall sein sollte).
- Nun in der Menüleiste unter `Internet` > `Freigaben` > `Portfreigaben` das Gerät auswählen, nun auf `Bearbeiten` > `Freigaben hinzufügen` und die Option `Exposed Host` für IPv4 / IPv6 aktivieren.
- Speichern/ Übernehmen


-------------------------------------------------------------------------------------------------------------
