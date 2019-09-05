################################################################################################################################
### DEUTSCHE BESCHREIBUNG
################################################################################################################################

********************************************************************************************************************************
*** Switch Army Knife (SAK) by kempa - September 2019
********************************************************************************************************************************

Version: beta v0.6.7
Veröffentlicht auf psxtools.de

ICH (kempa) übernehme keine Verantwortung für Schäden/Bricks jeglicher Art.
Die durch XCI's oder bei der späteren Installation auf der Switch von NSP's auftreten können!
Nutzt stets eure eigenen Spiele, die ihr auch legal besitzt!
So habt ihr später auch keine Probleme.

*** Ich unterstütze kein Warez!!! ***

********************************************************************************************************************************

Urheberrecht:
Der Code wurde komplett von mir persönlich entwickelt.
So kann das Tool völlig frei und legal angeboten werden!

Voraussetzung dafür:
Das 7zip Archiv darf nicht verändert werden
Immer mit Quellenangabe zum original Forum-Thread (siehe nachfolgenden Support Link)

Wichtige Infos: (hinzugefügte Tools die nicht von mir sind):
4NXCI (4nxci.exe) - Hier gilt das Danke an The-4n und SciresM für die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/The-4n/4NXCI

FAT32 Format (guiformat.exe) - Danke geht an Ridgecrop Consultants Ltd für die GUI Version vom FAT32 Format Tool.
Quelle: http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm

hactool (hactool.exe) - Hier gilt das Danke an SciresM für die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/SciresM/hactool

NSC_BUILDER (squirrel.exe) - Hier gilt das Danke an julesontheroad für die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/julesontheroad/NSC_BUILDER

LibHac (hactoolnet.exe) - Hier gilt das Danke an Thealexbarney für die Entwicklung und das bereitstellen des Tools.
https://github.com/Thealexbarney

reNXpack (renxpack.exe) - Hier gilt das Danke an The-4n und SciresM für die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/The-4n/reNXpack

********************************************************************************************************************************

Support: Auf psxtools.de (https://psxtools.de/index.php/Thread/77281)

********************************************************************************************************************************
*** Funktionen
********************************************************************************************************************************

Mit diesem Switch Taschenmesser könnt ihr eure Inhalt XCI/NSP von eurer Switch einfach jonglieren.

- XCI splitten / zusammenfügen
- XCI nach NSP konvertieren
- Firmware von XCI entpacken
- NSP patchen
- NSP splitten
- NSP nach XCI konvertieren
- Extrahiere deine Switch Savegames diese du von der User Partition kopiert hast
- SD Karte in FAT32 formatieren

*** Generell gilt:
Alle Dateien werden immer im Ordner von SAK erstellt.
Es werden nur XCI + NSP Dateien >= 4GB zum splitten akzeptiert.
Alle < 4GB macht dass splitten ja auch kein Sinn!

*** Für XCI splitten gilt:
XCI können in voller Größe oder getrimmt gesplittet werden.
Getrimmt bedeutet, dass der leere Speicherplatz am Ende entfernt wird.
Dadurch gibt es einen kleinen Speicherplatz gewinn für das XCI Abbild.

Der neue Dateiname wird mit "_splitted" ergänzt.

Können auch direkt auf die µSD Karte via USB Reader gesplittet werden.

*** XCI zusammenfügen gilt:
Dateiendungen.xc0 und .xci.00 werden akzeptiert

*** Für XCI nach NSP konvertieren gilt:
keys.dat/prod.keys wird benötigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

*** Für Firmware entpacken gilt:
keys.dat/prod.keys wird benötigt
Datei muss in XCI vorliegen

***  Für NSP auf niedrige FW patche gilt:
keys.dat/prod.keys wird benötigt
Datei muss in NSP vorliegen

*** Für NSP splitten gilt:
Die gesplitteten Dateien werden in einem Ordner mit fortlaufender Nummer abgelegt.
Als Bezug für den Ordnername, wird der aktuelle NSP Dateiname genommen und mit "splitted" ergänzt

Können nun auch direkt auf die µSD Karte via USB Reader gesplittet werden.

Das Archivbit wird automatisch gesetzt.

*** Für NSP nach XCI konvertieren gilt:
nur Spiele unterstützt
keys.dat/prod.keys wird benötigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

*** Für Saves extrahiere gilt:
keys.dat/prod.keys wird benötigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547
Dein save Ordner von der User Partition (HacDiskMount oder via Homebrew Tool)
Mittels HacDiskMount, schaut dazu hier vorbei
psxtools.de/index.php/Thread/IDBLAAAAA

*** FAT32 Format:
Wenn du beim formatieren der SD Karte einen Fehler erhälst.
(Failed to opene device) vergewissere dich, dass nichts auf die SD zugreift.
Schon alleine der geöffnete Windows Explorer reicht hierzu aus.

So sollte es immer gehen:
Starte FAT32 Format und stecke jetzt erst die SD Karte in Kartenleser.
Danach die SD Karte auswählen und formatieren klicken.

********************************************************************************************************************************
*** Änderungshistorie
********************************************************************************************************************************

Beta v0.2.1: (25.11.2018)
Mit diesem Tool könnt ihr eure eigenen NSP Files für FAT32 SD-Karten splitten.
Damit ihr diese auf eurer Switch über die SD-Karte einfach installieren könnt.

- Es werden nur NSP Dateien >= 4GB akzeptiert.
  Alle < 4GB macht dass splitten ja auch kein Sinn! ;-)

- Die gesplitteten Dateien werden in einem Ordner mit fortlaufender Nummer abgelegt.
  Als Bezug für den Ordnername, wird der aktuelle NSP Dateiname genommen und mit "splitted" ergänzt

- Das Archivbit wird automatisch gesetzt.

Beta v0.3: (26.11.2018)
- Mehrfachauswahl fürs splitten nun möglich

- Freier Speicherplatz wird bei jedem Titel vorher geprüft

Beta v0.4: (01.12.2018)
- Direktes splitten auf die SD-Karte

Beta v0.5: (12.12.2018)
- XCI teilen
- XCI zusammenfügen
- XCI in NSP konvertieren (keys.dat erforderlich)
- FAT32 Format eingefügt
- Update Funktion

Beta v0.5.1: (18.12.2018)
- Möglichkeit prod.keys für 4NXCI zu verwenden
- *please wait* Nachricht beim konvertieren von XCI nach NSP

Beta v0.6: (28.12.2018)
- Entpacke Firmware Update aus XCI
- XCI in NSP konvertieren Anpassungen:
  - Dateiname automatisch umbenannt
  - Möglichkeit direkt für FAT32 zu splitten
  - Möglichkeit direkt auf USB zu splitten

Beta v0.6.1: (04.01.2019)
- kleine Korrekturen und Optimierungen

Beta v0.6.2: (05.01.2019)
- Korrektur fürs konvertieren XCI -> NSP immer in den SAK Ordner

Beta v0.6.2.1: (05.01.2019)
- Kleine Korrektur fürs ausführen bei 4nxci

Beta v0.6.3: (26.01.2019)
- 4nxci update auf neue Version 3.0
- 4nxci freier Speicherplatz wird vor konvertieren geprüft
- Entpacke FW freier Speicherplatz wird vorher geprüft
- Anzeige der benötigten Zeit für den gesammten Prozess
- Erzwungene Administratorberechtigungen wurden von SAK entfernt.
  Falls du Probleme haben solltest, so starte SAK als Administrator!

Beta v0.6.3.1: (29.01.2019)
- 4nxci update auf neue Version 3.01
- Beim konvertieren von XCI nach NSP wird die Funktion für die Titelbenennung von 4nxci genutzt

Kleines Update: (01.02.2019)
- 4nxci update auf neue Version 3.05

Kleines Update: (05.02.2019)
- 4nxci update auf neue Version 3.06

Kleines Update: (12.03.2019)
- 4nxci update auf neue Version 4.0

Beta v0.6.4: (25.03.2019)
- Beim konvertieren von XCI nach NSP
  Ausgabe von Fehlermeldung für fehlerhafte/fehlende Einträge in der prod.keys

Beta v0.6.4.1: (26.03.2019)
- Fix für falsche Meldung von fehlerhafte/fehlende Einträge in der prod.keys beim XCI nach NSP konvertieren

Kleines Update: (01.04.2019)
- 4nxci update auf neue Version 4.01

Beta v0.6.5: (12.04.2019)
- kleine Fehlerbehebungen für SAK
- Neue Funktion hinzugefüget NSP auf niedrige Firmware patchen

Beta v0.6.5.1: (21.04.2019)
- kleine Änderungen für reNXpack in SAK
- 4nxci update auf neue Version 4.03
- reNXpack update auf neue Version 1.16

Beta v0.6.6: (23.06.2019)
- Neue Funktion hinzugefüget NSP nach XCI konvertieren

Kleines Update: (10.07.2019)
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.87c

Beta v0.6.7: (05.09.2019)
- Neue Funktion hinzugefüget extrahiere Saves von der User Partition
- NSC_BUILDER (nur squirrel.exe) update auf neue Version 0.89b

********************************************************************************************************************************
*** Switch Army Knife in Betrieb nehmen
********************************************************************************************************************************

Voraussetzung:
- Windows PC
- Gedumpte keys.dat/prod.keys von deiner Switch Konsole - um deine Keys zu bekommen schaue hier -> (https://psxtools.de/index.php/Thread/76547)

7zip entpacken:
- Switch keys (keys.dat/prod.keys) im "bin" Ordner bei der 4nxci.exe ablegen
- fertig

################################################################################################################################
### ENGLISH DESCRIPTION
################################################################################################################################

********************************************************************************************************************************
*** Switch Army Knife (SAK) by kempa - September 2019
********************************************************************************************************************************

Version: beta v0.6.7
Published on psxtools.de

I (kempa) take no responsibility for damages/bricks of any kind.
Which can occur from XCI's or during the installation of the NSP's on the switch!
Always use your own games, which you legally own!
So you have no problems later.

*** I don't support warez !!! ***

********************************************************************************************************************************

Copyright:
The code was completely developed by me.
So the tool can be published completely free and legal!

Prerequisite for this:
The 7zip archive must not be changed
Always with reference to the original forum thread (see Support Link below)

Important notices: (included tools that are not from me):
4NXCI (4nxci.exe) - The respect goes to The-4n and SciresM for developing and providing the tool.
Source: https://github.com/The-4n/4NXCI

FAT32 Format (guiformat.exe) - Thanks goes to Ridgecrop Consultants Ltd for FAT32 Format as GUI version
Source: http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm

hactool (hactool.exe) - The respect goes to SciresM for developing and providing the tool.
Source: https://github.com/SciresM/hactool

NSC_BUILDER (squirrel.exe) - The respect goes to julesontheroad for developing and providing the tool.
Source: https://github.com/julesontheroad/NSC_BUILDER

LibHac (hactoolnet.exe) - The respect goes to Thealexbarney for developing and providing the tool.
https://github.com/Thealexbarney

reNXpack (renxpack.exe) - The respect goes to The-4n and SciresM for developing and providing the tool.
Source: https://github.com/The-4n/reNXpack

********************************************************************************************************************************

Support: On psxtools.de (https://psxtools.de/index.php/Thread/77281)

********************************************************************************************************************************
*** Functions
********************************************************************************************************************************

With Switch Army Knife you can easily juggle XCI / NSP content from your switch.

- Split / merge XCI
- Convert XCI to NSP
- Extract Firmware from XCI
- Patch NSP
- Split NSP
- Convert NSP to XCI
- Extracting Switch savegames which you have copied from your User partition
- Format the SD card in FAT32

*** Generally:
All files are always created in the folder of SAK.
Only XCI + NSP files >= 4GB are accepted for splitting.
All files < 4GB makes splitting no sense!

*** Split XCI:
XCI can be split in full size or trimmed.
Trimmed means that the empty space at the end will be removed.
This will saves you a lot of space for the XCI image.

The new file name will be append with "_splitted".

Can also be split directly to the ?SD card over the USB card reader.

*** Merge XCI :
Extensions.xc0 and .xci.00 are accepted

*** Converting XCI to NSP:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Firmware extraction:
keys.dat / prod.keys is required
File must be as XCI

***  Patch NSP to lower firm:
keys.dat / prod.keys is required
File must be as NSP

*** Split NSP:
The split files are stored in a folder with a sequential number.
As reference for the folder name, the current NSP file name is taken and added with "splitted"

Can now be split directly to the ?SD card over USB card reader.

The archive bit is set automatically.

*** Converting NSP to XCI:
only games supported
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Extracting saves:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547
YOur save folder from the User partition (HacDiskMount or Homebrew Tool)
By HacDiskMount, look here psxtools.de/index.php/Thread/IDBLAAAAA

*** FAT32 Format:
If you get an error when formatting the SD card.
(Failed to open device) make sure nothing access the SD card.
Already opening the windows explorer is enough to get the error.

This is how it should always be:
Start FAT32 Format and now insert the SD card in the card reader.
Then select the SD card and format it.

********************************************************************************************************************************
*** Changelog
********************************************************************************************************************************

Beta v0.2.1: (25.11.2018)
With this tool you can split your own NSP files for FAT32 SD cards.
So you can easily install them on your switch via the SD card.

- Only NSP files >= 4GB are accepted.
  All < 4GB files makes no sense to split! ;-)

- The splitted files are stored in a folder with a sequential number.
  As reference for the folder name, the current NSP file name is taken and added with "splitted"

- The archive bit is set automatically.

Beta v0.3: (26.11.2018)
- Multiple selection for splitting is now possible

- Free space will be checked for each title

Beta v0.4: (01.12.2018)
- Directly splitting on the sd-card

Beta v0.5: (12.12.2018)
- XCI split
- XCI merge
- XCI to NSP converting (keys.dat required)
- FAT32 Format implemented
- Update feature

Beta v0.5.1: (18.12.2018)
- possibility to use prod.keys for 4NXCI
- added *please wait* message at converting XCI to NSP process

Beta v0.6: (28.12.2018)
- Extract firmware update from XCI
- XCI to NSP converting changes:
  - filename auto renaming
  - possibility to directly split for FAT32
  - possibility to directly split to USB

Beta v0.6.1: (04.01.2019)
- small fixes and optimizations

Beta v0.6.2: (05.01.2019)
- fix for converting XCI -> NSP always to SAK folder

Beta v0.6.2.1: (05.01.2019)
- small fix for 4nxci execution

Beta v0.6.3: (26.01.2019)
- 4nxci update to new version 3.0
- 4nxci check free disk space before converting
- Extract FW from XCI check free disk space
- Show needed time for the complete action
- Removed required administrator rights from SAK
  If you have problems, run SAK as administrator!

Beta v0.6.3.1: (29.01.2019)
- 4nxci update to new version 3.01
- At converting process XCI to NSP now using titelnaming feature from 4nxci

Small update: (01.02.2019)
- 4nxci update to new version 3.05

Small update: (05.02.2019)
- 4nxci update to new version 3.06

Small update: (12.03.2019)
- 4nxci update to new version 4.0

Beta v0.6.4: (25.03.2019)
- At converting process XCI to NSP
  Output failure message for incorrect/missing entries in prod.keys

Beta v0.6.4.1: (26.03.2019)
- Fix for wrong incorrect/missing prod.keys message at XCI to NSP converting

Small update: (01.04.2019)
- 4nxci update to new version 4.01

Beta v0.6.5: (12.04.2019)
- small fixes for SAK
- Added new feature patch nsp to lower firm

Beta v0.6.5.1: (21.04.2019)
- small changes for reNXpack at SAK
- 4nxci update to new version 4.03
- reNXpack update to new version 1.16

Beta v0.6.6: (23.06.2019)
- Added new feature NSP to XCI converting

Small update: (10.07.2019)
- NSC_BUILDER (only squirrel.exe) update to new Version 0.87c

Beta v0.6.7: (05.09.2019)
- Added new feature extract saves form the User partition
- NSC_BUILDER (only squirrel.exe) update to new Version 0.89b

********************************************************************************************************************************
*** Put Switch Army Knife into operation
********************************************************************************************************************************

Requirement:
- Windows PC
- Dumped keys.dat/prod.keys from your Switch console - to get your keys look here -> (https://psxtools.de/index.php/Thread/76547)

Unzip 7zip:
- Switch keys (keys.dat/prod.keys) copy it to the "bin" dir near 4nxci.exe
- finished
