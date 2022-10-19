# E1-Tastatur

Dieses Repository setzt die
[Tastaturbelegung E1](<https://de.wikipedia.org/wiki/E1_(Tastaturbelegung)>) für
Microsoft Windows um. Im Vergleich zur Standardbelegung (T1) erlaubt E1 die
Eingabe vieler Buchstaben, diakritischer Zeichen und Satzzeichen aus
europäischen Schriften.

Die Tastaturbelegung E1 ist definiert in der
[DIN 2137-1](https://dx.doi.org/10.31030/2890217). Dieses Repository folgt ihrer
letzten Ausgabe, 2018-12.

Eine neuere Ausgabe (2020-11) befindet sich noch in der Entwurfsstufe. Sobald
diese verabschiedet wird, wird auch dieses Repository aktualisiert.

## Belegung

![Deutsche Tastaturbelegung E1 nach E DIN 2137-01:2020-11](https://upload.wikimedia.org/wikipedia/commons/5/54/Deutsche_Tastaturbelegung_E1_nach_E_DIN_2137-01--2020-11.png)

**Von Karl432 - Eigenes Werk, CC BY-SA 4.0,
<https://commons.wikimedia.org/w/index.php?curid=95714496>**

### Abweichungen

Aufgrund von Limitierungen im Microsoft Keyboard Layout Creator oder in
Microsoft Windows gibt es leider einige Abweichungen von der DIN 2317-1:

- Für die Tottasten, welche über die Extra-Wahltaste (AltGr+f) zu erreichen
  sind, können keine expliziten Zuweisungen festgelegt werden.
- Wenn nach Drücken der Extra-Wahltaste (AltGr+f) keine Taste mit einer
  Zuweisung in Gruppe 2 gedrückt wird, wird der Buchstabe f gefolgt von der
  zweiten Taste eingegeben.

## Installation

> TODO

## Entwicklung

Die Quelldateien mit der Endung `.klc` werden von dem
[Microsoft Keyboard Layout Creator (MSKLC) Version 1.4](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
in eine ausführbare Datei kompiliert. Diese installiert die Tastaturbelung und
macht sie in den Betriebssystem-Einstellungen verfügbar.

Nach der Installation von MSKLC muss die `namelist.txt` einmalig aktualisiert
werden, dies wird in der Menüleiste unter _Help_ → _Update Unicode character
data_ erledigt.

## Alternativen

> TODO
