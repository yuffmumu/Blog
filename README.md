# Blog Stundenübersicht

[Informatik Stunde 1](#1)  
[Informatik Stunde 2](#2)  
[Informatik Stunde 3](#3)  
[Informatik Stunde 4](#4)  
[Informatik Stunde 5](#5)  
[Informatik Stunde 6](#6)  
[Informatik Stunde 7](#7)  
[Informatik Stunde 8,9](#8,9)  
[Informatik Stunde 10](#10) 
[Informatik Stunde 11](#11) 

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
![6  informatik Stunde (Nachmittags)](https://user-images.githubusercontent.com/69623479/91549931-05978080-e928-11ea-9f12-c73a00dd3456.PNG)  

### <a name="7"></a>Informatik Stunde 7:
In der 7. Informatik Stunde haben wir seperat an unserem Projekt gearbeitet. Yannick hat sich mit dem Designen der Stage in bezug auf Plattformen und Grafiken beschäftigt. Das "stehen" auf den Plattformen wurde in dem Fall mit "if touching Farbe ( )" verwirklicht. Das Endergebniss der Stunde sieht wie folgt aus:
![7  informatik Stunde (Yuff)](https://user-images.githubusercontent.com/69623479/92225456-84019e80-eea3-11ea-8d3c-6a3ed420d1e2.PNG)
Malte beschäftigte sich mit dem Kreieren eines "Power-Blocks", welcher Die Sprite vergrößert und die Farbe abwechselnd zwischen Blau und Rot wechseln ließ. Malte bemerkte, dass es kein Zeitlimit des Effekts gab machte sich daran einen Timer einzubauen. Dies wurde mithilfe einer Variable, die auf 5 gesetzt und bei jedem Farbwechel mit -1 subtrahiert wurde umgesetzt, so das Insgesamt 5 mal die Fareb von Blau nach Rot und wieder zurück gewechselt wurde. Der Script unten rechts ist der in diesem Text besprochene.
![7  informatik Stunde (Mumu)](https://user-images.githubusercontent.com/69623479/92225454-82d07180-eea3-11ea-818d-b88912a91c9e.PNG)

### <a name="8,9"></a>Informatik Stunde 8,9:
(Blog noch schreiben!) Wir haben DIE GANZE Zeit an ranzischen Blöggen geaurbeitet

### <a name="10"></a>Informatik Stunde 10:
Als nächstes sollte sich der Character nicht als statische Graphik bewegen, sondern in einer Animation.
Yannick hat um dies zu erreichen eine Commandkette erstellt bei der man in beliebigen Zeitabständen, beliebig viele Kostüme unter der Bedingung, dass die entsprechende Taste gedrückt wird, einfügen kann. 

![10  informatik Stunde](https://user-images.githubusercontent.com/69623479/92228330-012f1280-eea8-11ea-8e2d-aa2a01ecb9f2.PNG)

Währenddessen hat Malte an dem Blog für die Tage 7,8,9 gearbeitet.

### <a name="11"></a>Informatik Stunde 11:

Um dem Spiel etwas mehr Struktur zu verleihen, sollte es nun ein Ziel geben.
Yannick hat also eine Sprite erstellt die, wenn sie erreicht wird das Script stoppt und erlaubt eine Graphik einzublenden die Signalisiert, dass das Level abgeschlossen ist.
Das war nach kurzem Probieren kein großes Problem, jedoch wollte Yannick als Zusatz eine Kleine Animation für den Character nach dem Erreichen des Ziels einbauen, dies stellte sich als kleines Problem heraus, da das erreichen des Ziels jedes Script im Programm stoppt, es musste der Command mit der Animation von diesem Befehl ignoriert werden. 

Nach kurzem überlegen ergab sich dann die Sprite "Ziel" und Folgendes Skript zum Animieren des Characters nach erreichen des Ziels.

![Animation nach erreichen des Ziels](https://user-images.githubusercontent.com/69623479/93869768-8d28a300-fccc-11ea-9a02-0ff56af689e9.PNG)



