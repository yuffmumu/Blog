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
[Informatik Stunde 12](#12)
[Informatik Stunde 13](#13)
[Informatik Stunde 14](#14)
[Informatik Stunde 15](#15)

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
In den letzten beiden Stunden haben wir uns ausschließlich mit dem Programmieren von schwebenden Plattformen, bzw. dem richtigen physikalischen Verhalten der Spielfigur den Blöcken gegenüber beschäftigt. Das große und immernoch ungelöste Problem, die 4 Seiten der Blöcke für unsere Spielfigur undurchlässig zu machen war der Kern unserer Überlegungen. Wir konnten auf den Blöcken stehen, indem wir unser "Schwerkraft-Skript" mit dem if-befehl "if not touching [schwebende Plattform]" eingegrenzt haben. Das wir nicht von unten durch die Plattform durchspringen konnten haben wir damit gelöst den Sprung Skript mit dem if-Befehl "if touching [schwebende PLattform] stop this skript. Um das durchdringen des Blocks von der Seite zu verhindern haben wir einen Flag erstellt. Wir haben einen if Befehl festgelegt, dass wenn der Block berührt wird "touching Block" = 1 ist und sonst = 0. Dann haben wir die Bedingung, dass wenn "if touching Block" = 1 der Skript stoppt, in unseren Bewegungsskript eingebaut: 
![8,9 informatik Stunde (Flag)](https://user-images.githubusercontent.com/69623479/93868945-733a9080-fccb-11ea-92bd-01ee783e56f5.PNG)
 Das Probelm ist jetzt, dass die Spielfigur sich auch nicht nach rechts und links bewegen kann wenn wir von oben oder unten den Block berühren. Dann haben wir überlegt mann müsse einfach die Seiten links und rechts von den oben und unten unterscheiden können. Wir haben dann erstmal oben eine unsichtbare 2. Plattform draufbepackt jedoch ist die Spielfigur immernoch durchgeglitscht und konnte sich dann nicht bwewegen. Mann hätte also die unsichtbare Plattform so groß machen müssen, dass die Spielfigur irgendwo in der Luft schwebt.

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

![Neue Sprite-Ziel](https://user-images.githubusercontent.com/69623479/93869790-91ed5700-fccc-11ea-8b22-827ebab7be43.PNG)

### <a name="12"></a>Informatik Stunde 12:
Wir haben die gesamte Stunde den Blog geschrieben.

### <a name="13"></a>Informatik Stunde 13:

In der 13 Informatikstunde haben wir fast vollständig eine neue Mechanik in das Spiel integriert: den Schuss.
Das Ziel war ein Projektil vom Character aus nach links und rechts abfeuern zu können. 
Ein grober Anfang davon war auch kein Problem, denn eine zusätzliche Sprite mit einer Anderen Sprite (den Spielcharacter) als Startpunkt in die X oder -X Richtung laufen zu lassen ist sehr simpel zu programmieren.
Doch kleine Feinheiten passten noch nicht. 
So wurde zu erst die Position des nächsten Schusses festgelegt in dem moment wo der erste den Rand berührte. bewegte man sich also weiter stimmten Schuiss und Characterposition nicht mehr überein. Dies lies sich jedoch relativ schnell lösen, indem man den Schuss erst wieder an die Position des Spielcharacters befördert in dem Moment wo er auch tatsächlich abgefeuert wird.
Ein weiteres und schwereres Problem war, dass wenn man in eine Richtung schoss und noch während der Schuss Flog einen Schuss in die andere Richtung inniziierte. Dies sorgte dafür, dass der Schuss still in der Luft stehen blieb und nicht mehr Funktionierte.
Dies konnten wir in der 13ten Stunde nicht mehr lösen.

### <a name="14"></a>Informatik Stunde 14:

In dieser Stunde haben Malte und Yannick wieder seperat gearbeitet.
Yannick hat sich damit beschäftigt nach dem Erreichen des Ziels zum nächsten Level zu kommen.
Dafür hat er einen Command erstellt der kollektiv eine Nachricht an alle beteiligten Elemente schickt um somit entsprechende neue Commands zu aktivieren.

![stage ändern wenn ziel erreicht anfang script pic](https://user-images.githubusercontent.com/69623479/94543745-ba380100-024a-11eb-9e44-0ae9fcc58ca5.png)

Sobald die Nachricht, dass das Ziel erreicht wurde angekommen ist wird dem Spieler ermöglicht durch das drücken der gewählten Taste das 2 Level zu betreten.
Das funktionierte soweit auch, nun war aber das Ziel, immer das Nächste Level betreten zu können, der Command sah jedoch vor, nach dem Erreichen des Ziels immer zum 2. Level zu wechseln, was sich in der Stunde nicht mehr lösen lies.

### <a name="15"></a>Informatik Stunde 15:

Die Lösung für das Problem aus Stunde 14 stellte sich in dieser Stunde als simpel heraus.
Denn da der Code für das eine Ziel funktionierte um zum 2. Level zu gelangen, war es naheliegend denselben Code für eine weitere Zielsprite zu nehmen, nur dass das nächste Ziel entsprechend für das nächste Level programmiert war.
So ordnete Yannick ein neues Ziel mit entsprechend angeglichenem Code den einzelnen Leveln zu (zu diesem Zeitpunkt Level 1-3).

![1 ziel pro level](https://user-images.githubusercontent.com/69623479/94909410-670cbb00-04a3-11eb-8ca2-479f4fc7ef0f.PNG)

