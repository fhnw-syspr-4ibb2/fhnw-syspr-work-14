# System-Programmierung
## Hands-on zu Lektion 14
Für Slides und Code Beispiele, siehe [Lektion 14](../../../fhnw-syspr/blob/master/14/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*

### a) GPIO, 30'
* Diese Hands-on Übung basiert auf dem [GPIO Pinout](https://pinout.xyz/pinout/wiringpi) des Raspberry Pi und kann gut zu zweit gelöst werden.
* Schreiben Sie ein Programm *my_switch.c* das mittels GPIO den Zustand eines Buttons liest, und damit eine LED ein- bzw. ausschaltet (Breadboards, Schalter, LED, Jumper Kabel und Widerstände werden im Unterricht ausgegeben).
* Während dem Aufbau der Schaltung sollte das Gerät vom Strom getrennt sein, zum Schutz der Elektronik.

### b) UART, 45'
* Diese Hands-on Übung basiert auf dem GPIO Pinout des Raspberry Pi, und kann in Gruppen gelöst werden.
* Schreiben Sie ein Programm *my_gps.c* das über UART mit AT Commands ein GPS Modul anspricht und ausliest.
* Als Hardware dient das ublox PAM 7Q GPS Modul (die Anzahl ist auf 4 beschränkt, arbeiten Sie in Gruppen).

### Abgabe (optional)
* Lokale Änderungen [committen und pushen](#git).
* GitHub [Issue erstellen](../../issues/new) mit "Bitte um Review, @tamberg".
* Offene Fragen ausformulieren, was geht nicht, was haben Sie versucht.
* GitHub mailt mir (@tamberg) automatisch, ich versuche in weniger als 24h zu antworten :)

## Tools
### Git
Auf Ihrem Computer
* Zu Beginn jeder Lektion wird ein Hands-on Repository Link freigeschaltet
* Nachdem Sie das "Assessment" annehmen, bekommen Sie per Email ein Repository
* Die REPO_URL enthält Ihren GitHub Account USER_NAME und Ihre Klasse 3ia oder 3ib, z.B.<br/>
            https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-14-tamberg

Auf dem Raspberry Pi
* Repository klonen<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Neue Datei kreieren<pre>
    $ git add FILE</pre>
* Änderungen committen<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Änderungen hochladen<pre>
    $ git push</pre>

### Nano
Auf dem Raspberry Pi
* Neue oder bestehende Datei öffnen mit $ nano FILE
* Editieren (Achtung, nano hat kein Undo)
* Speichern mit `CRTL-X` `Y` `RETURN`

### SSH
Auf Ihrem Computer
* Terminal öffnen (Mac) oder `WINDOWS` `R` cmd `RETURN` (Windows)
* SSH Session starten mit<pre>
    $ ssh pi@raspberrypi.local</pre>

## Support
- [FHNW Syspr Slack](https://fhnw-syspr.slack.com/)

