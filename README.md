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
Dies konnten wir in dieser Stunde nicht mehr lösen.

### <a name="14"></a>Informatik Stunde 14:

In dieser Stunde haben Malte und Yannick wieder seperat gearbeitet.
Yannick hat sich damit beschäftigt nach dem Erreichen des Ziels zum nächsten Level zu kommen.
Dafür hat er einen Command erstellt der kollektiv eine Nachricht an alle beteiligten Elemente schickt um somit entsprechende neue Commands zu aktivieren.

![stage ändern wenn ziel erreicht anfang script pic](https://user-images.githubusercontent.com/69623479/94543745-ba380100-024a-11eb-9e44-0ae9fcc58ca5.png)

Sobald die Nachricht, dass das Ziel erreicht wurde angekommen ist wird dem Spieler ermöglicht durch das drücken der gewählten Taste das 2 Level zu betreten.
Das funktionierte soweit auch, nun war aber das Ziel, immer das Nächste Level betreten zu können, der Command sah jedoch vor, nach dem Erreichen des Ziels immer zum 2. Level zu wechseln, was sich in der Stunde nicht mehr lösen lies.

Malte hat weiter am Schuss gearbeitet und dieses Skript geschrieben:

![Stunde 14 (Schuss)](https://user-images.githubusercontent.com/69623479/97292665-d3cd6800-184b-11eb-8e21-a6d32b0c724f.PNG)

Die Lösung für das Problem letzter Stunde wurde durch das einfügen einer Variable gelöst. Die Variable ist solange 0 wie der Schuss fliegt. Dann kann man durch den Befehl "if key pressed and schuss=1" regulieren ob man schon wieder einen Schuss abfeuern kann.

### <a name="15"></a>Informatik Stunde 15:

Die Lösung für das Problem aus Stunde 14 stellte sich in dieser Stunde als simpel heraus.
Denn da der Code für das eine Ziel funktionierte um zum 2. Level zu gelangen, war es naheliegend denselben Code für eine weitere Zielsprite zu nehmen, nur dass das nächste Ziel entsprechend für das nächste Level programmiert war.
So ordnete Yannick ein neues Ziel mit entsprechend angeglichenem Code den einzelnen Leveln zu (zu diesem Zeitpunkt Level 1-3).

![1 ziel pro level](https://user-images.githubusercontent.com/69623479/94909410-670cbb00-04a3-11eb-8ca2-479f4fc7ef0f.PNG)

Da Yannick sich schon zu Hause diese Lösung überlegt hatte war die Umsetzung schnell erreicht.

Die übrige Zeit nutzte er um an einem neuen Element im Spiel zu arbeiten: dem Trampolin.
Würde man dieses berühren, sollte ein größerer Sprung automatisch ausgeführt werden. 
Bis auf den Feinschliff in Sachen Effektstärke und implimentierung im Spiel selbst wurde dies auch noch in derselben Stunde erreicht.

![Anfang Jump and run spiel script pic (1)](https://user-images.githubusercontent.com/69623479/94910469-0aaa9b00-04a5-11eb-872c-f330b15abc20.png)

Zu Hause hat sich Yannick zudem noch mit einer Weiteren Mechanik beschäftigt.
Von 3 Leben, wie sie auch Malte bei seinen Gegnern hatte, sollten beim herunterfallen von Plattformen eines abgezogen werden, und der Character zurück zum Anfang des Levels zurück gebracht werden.
Dies ließ sich reibungslos einfügen:

![Anfang Jump and run spiel script pic (1)](https://user-images.githubusercontent.com/69623479/94911146-fdda7700-04a5-11eb-9771-310b6a782ed3.png)

zudem wurde noch direkt eine eintsprechend auf die Variable regaierende Graphik eingefügt:

![leben anzeige](https://user-images.githubusercontent.com/69623479/94911297-337f6000-04a6-11eb-9427-29465f80b133.PNG)

Malte hat sich damit beschäftigt Gegner ins Spiel zu implementieren. Als erstes fügte Malte eine ähnliche Mechanik wie beim Charakter für die Leben für die insgesamt drei Gegner ein. So starteten sie bei 2 Leben und verloren immer wenn sie den Schuss berührten wurden 1 Leben. Bei 0 Leben haben wir sie mit dem "hide" Befehl verschwinden lassen. Das Problem war, dass die Variable direkt auf 0 gesetzt wurde, da mit einem Schuss mehrere Leben abgezogen werden konnte. Dies hat Malte dann mit einer Variabel gelöst, die 0,5 Sekunden 0 ist und dann erst 1. Dann haben wir die Bedingung, dass das zweite Leben erst abgezogen werden kann wenn diese Variable 1 ist eingefügt. Dann wollte Malte einfügen, dass die Gegner nachdem sie ein Leben verloren haben "wütend" werden. Dass heißt sie ändern ihr außssehen zu einer wütenderen Version und werden schneller. Dies wurde mit einem eigenen Skript umgestzt. Das Endergebnis dieser Stunde siehjt wie folgt aus:

![15  informatik Stunde (Gegner)](https://user-images.githubusercontent.com/69623479/97293348-d7152380-184c-11eb-9c35-ce60f3f984bd.PNG)

### <a name="16"></a>Informatik Stunde 16-22:

Im Zeitraum um die 16. Stunde entschieden wir uns das Spiel nicht zu einem Platformer/J&R zu machen, sondern es als eine Art Brawl-Game weiterzuentwickeln.

Wir erstellten also eine Testumgebung die sehr grob der Struktur des Spiels entsprechen würde:

![testumgebung](https://user-images.githubusercontent.com/69623479/97292436-88b35500-184b-11eb-8eb0-9c4b5769e668.PNG)

Um die Testumgebung vollständig nutzen zu können mussten wir jedoch noch den Code für unsere Blöcke fertigstellen. 

Dies konnte dieses mal auch endlich erreicht werden, indem wir eine Variable als Bedingung für die Bewegungscommands eingefügt haben.
Außerdem fanden wir noch heraus, dass man in Snap die einzelnen Sprites zusammenkleben konnte. Da unsere individuellen Blöcke jeweils aus 4 Teilen bestehen war dies eine extreme Vereinfachung beim programmieren der Blöcke in der Stage.

![blockbedingungsvariable und neue richtung fürs spiel cleaner](https://user-images.githubusercontent.com/69623479/97292038-0460d200-184b-11eb-9288-b932dc342561.PNG)

Desweiteren erarbeiteten wir ein Konzept zur Klaren weiterführung des Spiels. Dieses umfasste die 2 verschiedenen spielbaren Charactere, die Stages und deren interaktive Elemente und zuletzt noch eine grobe Idee für Items die nur bei evntl noch übriger Zeit implimentiert würden.


Snap Programm Konzept
Stages:
- Zukunft (Weltraum, Raumschiff)
- Mittelalter (Marktstände, Burg, Ritter mit Lanze läuft durchs Bild)
- Unterwelt, Fantasy, Lava, Vulkan
- Eis-Welt (Schnee, Schlittern, brechende „Eisschollen“)
- Apokalypse (Zombies, Verlassene eingestürzte Häuser)

Charaktere:
Alphonzo:
    • Wird stärker/wütend durch genommenen Schaden
--> macht mehr Schaden niedrigerer Cooldown auf aktiver Fähigkeit
-      aktive Fähigkeit: Idee 1: Schlag auf den Boden dann „Erdbeben“ und Feind wird       gestunnt
- Primär Waffe: Laser Minigun
- Sekundär: Fette Faust
	- langsamer
	- Massiver gepanzerter Cyborg
	
	         Gonzales
	- Dreischussswaffe
	- kurzer instant teleporter
	- Messer/Dolch (vllt Backstab)
	- Maskierte Pflanze oder Affe mit Anzug

(Items:
    • Leben, Movement boost, Damage Boost…)

Im Rahmen dieses Konzepts begannen wir das graphische Design des Spiels.

Erste concept-pixelarts vom Character "Alphonzo" und einer Mittelalterstage enstanden bis hierhin.

### <a name="23"></a>Informatik Stunde 23:

Wir haben die ganze Stunde den Blog geschrieben

### <a name="23"></a>Informatik Stunde 24:

Nachdem wir unsere Ideen ausgetauscht haben und wir die nächsten Schritte geplant haben, hat Malte Blog geschrieben und Yannick hat sich mit Gonzales Teleport beschäftigt. Das Hauptpproblem dieser Stunde war, das man in die Blöcke reinglitchen konnte, dies wurde zu Lösen versucht, in dem man zusätzliche Sprites im inneren Platzierte, die ...
