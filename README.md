# Blog Stundenübersicht

[Informatik Stunde 1](#1)  
[Informatik Stunde 2](#2)  
[Informatik Stunde 3](#3)  
[Informatik Stunde 4](#4)  
[Informatik Stunde 5](#5)  
[Informatik Stunde 6](#6) 

### <a name="1"></a>Informatik Stunde 1:
Wir haben einen Github account erstellt und uns nach vorerst relativ oberflächligem Anschauen der gegebenen Möglichkeiten für ein Snap projekt entschieden.
![1 informatik stunde](https://user-images.githubusercontent.com/69623479/90876696-4c72fc80-e3a3-11ea-9957-a134d7681be5.PNG)

### <a name="2"></a>Informatik Stunde 2:
Die ersten Schritte mit Snap wurden gemacht um ein besseres gefühl dafür zu bekommen, wie sich eine Block-Programmiersprache handhaben lässt.
![2  informatik Stunde](https://user-images.githubusercontent.com/69623479/90877069-c5725400-e3a3-11ea-8023-bab9ded7f5a6.PNG)

### <a name="3"></a>Informatik Stunde 3:
Da Yannick krank war habe ich mich alleine mit snap beschaftigt, d.h ich habe mir die Seite "The Joy of Computing näher angeguckt" und versucht dies in SNAP! umzusetzten. Am ende der Stunde habe ich mit Hilfe ihres Hilfsdokument versucht verlinkungen und Bilder in unserern Block einzubauen.
![snap ninformatik stunde 3](https://user-images.githubusercontent.com/69623479/90877068-c4d9bd80-e3a3-11ea-85a6-cfeae7eab6ef.PNG)

### <a name="4"></a>Informatik Stunde 4:
Yannick war noch weg, weshalb ich mich mit unserem github account bzw. unserem Blog beschäftigt habe. Mein Problem war, dass ich nicht wusste, wie ich Bilder in meine Repositories hochladen konnte. In ihrer README.md datei haben sie z.B diesen (![bsp starlogtng](image/starlogotng_bsp.jpg "Screenshot von StarLogoTNG")) befehl benutzt. Wenn ich jedoch diesen Befehl kopiert habe wurde das Bild nicht angezeigt. Dann habe ich im Internet danach geguckt wie man Bilder bei github einfügen kann und da wurde gezeigt, dass man die bilder per drag and drop bei Issues hochladen kann und dann einfach in die README.md Datei reinkopieren kann. Der Blog sieht nun wie folgt aus:
![4  informatik Stunde 2](https://user-images.githubusercontent.com/69623479/90879870-dd4bd700-e3a7-11ea-9205-cbc577ac4d74.PNG)
Währenddessen habe ich mit Samed zusammen herausgekrigt wie man die Grundbewegung des Spiels Snake zusammenstellt.

### <a name="5"></a>Informatik Stunde 5:
Wir haben nun angefangen an umserem richtigen Spiel zu arbeiten, indem wir erste Mechaniken wie Schwerkraft, Bewegung nach Links und Rechts eingebaut haben. Unser größtes Problem war, dass wir beim eigentlichen Springen, durchs Halten der Leerstaste unendlich hoch "fliegen" konnten.  
![5  informatik Stunde](https://user-images.githubusercontent.com/69623479/91162621-9c680100-e6cc-11ea-91fa-2650e29a1915.PNG)

### <a name="6"></a>Informatik Stunde 6:
Wir haben uns weiter mit dem Sprung unseres Spiels beschäftigt. 
Das erste Ziel war selbstverständlich es unmöglich zu machen, zu fliegen, gleichzeitig wollten wir das Verhalten des Sprungs aber auch komplexer machen, sodass unser "Character" beim Drücken der Leertaste sich nicht statisch nach oben und Unten bewegt, sondern Dynamisch an Geschwindigkeit ab und zu nimmt, sodass der Eindruck eines Physikalisch logischen Sprungs entstand.
Die Dynamik des Sprungs war nach einiger Zeit unseren Vorstellungen entsprechend, jedoch Ignorierte unser Charakter nach jedem Sprung auf einmal den Ursprünglichen Boden was wir in der Stunde nicht mehr Lösen konnten. 
![sprung ansatz](https://user-images.githubusercontent.com/69623479/91548387-97ea5500-e925-11ea-8ceb-5ddb9bb0a70d.PNG)
Zu hause konnte dann mithilfe eines anderen ausgangsscripts der Sprung doch vervollständigt werden. Es wurde auch schnell herausgefunden, dass man forever befehle braucht, um den "Charakter" auch in der Luft bewegen zu können. Das Egebniss sah dann wie folgt aus:
