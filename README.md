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
[Informatik Stunde 16-22](#16)  
[Informatik Stunde 23](#23) 
[Informatik Stunde 24](#24)  
[Informatik Stunde 25](#25) 
[Informatik Stunde 26-30](#26) 
[Informatik Stunde 31-Abgabe](#31)  

### <a name="1"></a>Informatik Stunde 1:
Wir haben einen Github account erstellt und uns nach vorerst relativ oberflächligem Anschauen der gegebenen Möglichkeiten für ein Snap-Projekt entschieden.
![1 informatik stunde](https://user-images.githubusercontent.com/69623479/90876696-4c72fc80-e3a3-11ea-9957-a134d7681be5.PNG)

### <a name="2"></a>Informatik Stunde 2:
Die ersten Schritte mit Snap wurden gemacht um ein besseres Gefühl dafür zu bekommen, wie sich eine Block-Programmiersprache handhaben lässt.
![2  informatik Stunde](https://user-images.githubusercontent.com/69623479/90877069-c5725400-e3a3-11ea-8023-bab9ded7f5a6.PNG)

### <a name="3"></a>Informatik Stunde 3:
Da Yannick krank war habe ich mich alleine mit snap beschaftigt, d.h ich habe mir die Seite "The Joy of Computing näher angeguckt" und versucht dies in SNAP! umzusetzten. Am Ende der Stunde habe ich mit Hilfe des Hilfsdokument versucht Verlinkungen und Bilder in unseren Blog einzubauen.
![snap ninformatik stunde 3](https://user-images.githubusercontent.com/69623479/90877068-c4d9bd80-e3a3-11ea-85a6-cfeae7eab6ef.PNG)

### <a name="4"></a>Informatik Stunde 4:
Yannick war noch weg, weshalb ich mich mit unserem github-account bzw. unserem Blog beschäftigt habe. Mein Problem war, dass ich nicht wusste, wie ich Bilder in meine Repositories hochladen konnte. In ihrer README.md Datei haben sie z.B diesen (![bsp starlogtng](image/starlogotng_bsp.jpg "Screenshot von StarLogoTNG")) Befehl benutzt. Wenn ich jedoch diesen Befehl kopiert habe wurde das Bild nicht angezeigt. Dann habe ich im Internet recherchiert wie man Bilder bei github einfügen kann und da wurde gezeigt, dass man die Bilder per drag and drop bei "Issues" hochladen kann und dann einfach in die README.md Datei reinkopieren kann. Der Blog sieht nun wie folgt aus:
![4  informatik Stunde 2](https://user-images.githubusercontent.com/69623479/90879870-dd4bd700-e3a7-11ea-9205-cbc577ac4d74.PNG)
-------------Währenddessen habe ich mit Samed zusammen herausgekrigt wie man die Grundbewegung des Spiels Snake zusammenstellt.---------------

### <a name="5"></a>Informatik Stunde 5:
Wir haben nun angefangen an umserem richtigen Spiel zu arbeiten, indem wir erste Mechaniken wie Schwerkraft, Bewegung nach Links und Rechts eingebaut haben. Unser größtes Problem war, dass wir beim eigentlichen Springen, durchs Halten der Leerstaste unendlich hoch springen und somit praktisch fliegen konnten.  
![5  informatik Stunde](https://user-images.githubusercontent.com/69623479/91162621-9c680100-e6cc-11ea-91fa-2650e29a1915.PNG)

### <a name="6"></a>Informatik Stunde 6:
Wir haben uns weiter mit dem Sprung unseres Spiels beschäftigt. 
Das erste Ziel war selbstverständlich es unmöglich zu machen zu fliegen. Gleichzeitig wollten wir das Verhalten des Sprungs aber auch komplexer machen, sodass unser "Character" beim Drücken der Leertaste sich nicht statisch nach oben und unten bewegte, sondern Dynamisch an Geschwindigkeit ab und zu nahm, sodass der Eindruck eines Physikalisch logischen Sprungs entstand.
Die Dynamik des Sprungs war nach einiger Zeit unseren Vorstellungen entsprechend, jedoch Ignorierte unser Charakter nach jedem Sprung auf einmal den Ursprünglichen Boden was wir in der Stunde nicht mehr Lösen konnten. 
![sprung ansatz](https://user-images.githubusercontent.com/69623479/91548387-97ea5500-e925-11ea-8ceb-5ddb9bb0a70d.PNG)
Zu hause konnte dann mithilfe eines anderen ausgangsscripts der Sprung vervollständigt werden. Es wurde auch schnell herausgefunden, dass man "forever Befehle" braucht, um den "Charakter" auch in der Luft bewegen zu können. Das Egebniss sah dann wie folgt aus:
![6  informatik Stunde (Nachmittags)](https://user-images.githubusercontent.com/69623479/91549931-05978080-e928-11ea-9f12-c73a00dd3456.PNG)  

### <a name="7"></a>Informatik Stunde 7:
In der 7. Informatik Stunde haben wir seperat an unserem Projekt gearbeitet. Yannick hat sich mit dem Designen der Stage im Bezug auf Plattformen und Grafiken beschäftigt. Das "Stehen" auf den Plattformen wurde in dem Fall mit "if touching Farbe ( )" verwirklicht. Das Endergebniss der Stunde sieht wie folgt aus:
![7  informatik Stunde (Yuff)](https://user-images.githubusercontent.com/69623479/92225456-84019e80-eea3-11ea-8d3c-6a3ed420d1e2.PNG)
Malte beschäftigte sich mit dem Kreieren eines "Power-Blocks", welcher Die Sprite vergrößert und die Farbe abwechselnd zwischen Blau und Rot wechseln ließ. Malte bemerkte, dass es kein Zeitlimit des Effekts gab machte sich daran einen Timer einzubauen. Dies wurde mithilfe einer Variable, die auf 5 gesetzt und bei jedem Farbwechel um 1 subtrahiert wurde umgesetzt, sodass Insgesamt 5 mal die Farbe von Blau nach Rot und wieder zurück gewechselt wurde. Das Script unten rechts ist das in diesem Text besprochene.
![7  informatik Stunde (Mumu)](https://user-images.githubusercontent.com/69623479/92225454-82d07180-eea3-11ea-818d-b88912a91c9e.PNG)

### <a name="8,9"></a>Informatik Stunde 8,9:
In den letzten beiden Stunden haben wir uns ausschließlich mit dem Programmieren von schwebenden Plattformen, bzw. dem richtigen physikalischen Verhalten der Spielfigur den Blöcken gegenüber beschäftigt. Das große und immernoch ungelöste Problem, die 4 Seiten der Blöcke für unsere Spielfigur undurchlässig zu machen, war der Kern unserer Überlegungen. Wir konnten auf den Blöcken stehen, indem wir unser "Schwerkraft-Skript" mit dem if-befehl "if not touching [schwebende Plattform]" eingegrenzt haben. Um zu verhindern, dass man von unten durch die Plattform springen konnte, haben wir ein Skript erstellt, welches ------------- Dass wir nicht von unten durch die Plattform durchspringen konnten haben wir damit gelöst, das Sprung Skript mit dem if-Befehl "if touching [schwebende PLattform]:stop this script------------. Um das durchdringen des Blocks von der Seite zu verhindern haben wir einen Flag erstellt. Wir haben einen if Befehl festgelegt, dass wenn der Block berührt wird "touching Block" = 1 ist und sonst = 0. Dann haben wir die Bedingung, dass wenn "if touching Block" = 1 das Skript stoppt, in unseren Bewegungsskript eingebaut: 
![8,9 informatik Stunde (Flag)](https://user-images.githubusercontent.com/69623479/93868945-733a9080-fccb-11ea-92bd-01ee783e56f5.PNG)
 Das Probelm war nun, dass die Spielfigur sich auch nicht nach rechts und links bewegen konnte wenn wir von oben oder unten den Block berühren. Dann überlegten wir, mann müsse einfach die Seiten links und rechts von den oben und unten unterscheiden können. Wir legten eine unsichtbare 2. Plattform drauf, jedoch glitchte die Spielfigur nach wie vor durch die Plattform und konnte sich dann nicht bewewegen. Man hätte also die unsichtbare Plattform so groß machen müssen, dass die Spielfigur irgendwo in der Luft schwebt.
Da wir nicht zu viel Zeit auf einmal mit dem Block verbringen wollten, stellten wir dieses Problem vorerst zurück und nahmen uns vorerst andere Dinge vor.

### <a name="10"></a>Informatik Stunde 10:
Als nächstes sollte sich der Character nicht als statische Graphik bewegen, sondern in einer Animation.
Yannick hat um dies zu erreichen eine Commandkette erstellt bei der man in beliebigen Zeitabständen, beliebig viele Kostüme unter der Bedingung, dass die entsprechende Taste gedrückt wird, einfügen kann. 

![10  informatik Stunde](https://user-images.githubusercontent.com/69623479/92228330-012f1280-eea8-11ea-8e2d-aa2a01ecb9f2.PNG)

Währenddessen hat Malte an dem Blog für die Tage 7,8,9 gearbeitet.

### <a name="11"></a>Informatik Stunde 11:
Um dem Spiel etwas mehr Struktur zu verleihen, sollte es nun ein Ziel geben.
Yannick hat also eine Sprite erstellt die, wenn sie erreicht wird das Script stoppt und erlaubt eine Graphik einzublenden die Signalisiert, dass das Level abgeschlossen ist.
Das war nach kurzem Probieren kein großes Problem, jedoch wollte Yannick als Zusatz eine Kleine Animation für den Character nach dem Erreichen des Ziels einbauen. Dies stellte sich als kleines Problem heraus, da das Erreichen des Ziels jedes Script im Programm stoppt, der Command mit der Animation musste von diesem Befehl ignoriert werden. 

Nach kurzem Überlegen ergab sich dann die Sprite "Ziel" und folgendes Skript zum Animieren des Characters nach erreichen des Ziels.

![Animation nach erreichen des Ziels](https://user-images.githubusercontent.com/69623479/93869768-8d28a300-fccc-11ea-9a02-0ff56af689e9.PNG)

![Neue Sprite-Ziel](https://user-images.githubusercontent.com/69623479/93869790-91ed5700-fccc-11ea-8b22-827ebab7be43.PNG)

### <a name="12"></a>Informatik Stunde 12:
Wir haben die gesamte Stunde den Blog geschrieben.

### <a name="13"></a>Informatik Stunde 13:

In der 13 Informatikstunde haben wir fast vollständig eine neue Mechanik in das Spiel integriert: den Schuss.
Das Ziel war ein Projektil vom Character aus nach links und rechts abfeuern zu können. 
Ein grober Anfang davon war auch kein Problem, denn eine zusätzliche Sprite mit einer anderen Sprite (dem Spielcharacter) als Startpunkt in die X oder -X Richtung laufen zu lassen ist sehr simpel zu programmieren.
Doch kleine Feinheiten passten noch nicht. 
So wurde zu erst die Position des nächsten Schusses festgelegt in dem Moment, wo der erste den Rand berührte. Bewegte man sich also weiter stimmten Schuss und Characterposition nicht mehr überein. Dies lies sich jedoch relativ schnell lösen, indem man den Schuss erst wieder an die Position des Spielcharacters beförderte in dem Moment wo er auch tatsächlich abgefeuert wird.
Ein weiteres und schwereres Problem war, dass wenn man in eine Richtung schoss und noch während der Schuss Flog einen Schuss in die andere Richtung iniziierte.
Dies sorgte dafür, dass der Schuss still in der Luft stehen blieb und nicht mehr Funktionierte.
Dieses Problem konnten wir in dieser Stunde nicht mehr lösen.

### <a name="14"></a>Informatik Stunde 14:

In dieser Stunde haben Malte und Yannick wieder seperat gearbeitet.
Yannick hat sich damit beschäftigt nach dem Erreichen des Ziels zu einem weiterem "Level" zu kommen.
Dafür hat er einen Command erstellt der kollektiv eine Nachricht an alle beteiligten Elemente schickt um somit entsprechende neue Commands zu aktivieren (Ein einmaliger Broadcast).

![stage ändern wenn ziel erreicht anfang script pic](https://user-images.githubusercontent.com/69623479/94543745-ba380100-024a-11eb-9e44-0ae9fcc58ca5.png)

Sobald die Nachricht, dass das Ziel erreicht wurde angekommen war, wurde dem Spieler ermöglicht durch das Drücken der gewählten Taste das 2. Level zu betreten.
Das funktionierte soweit auch. Nun war aber das Ziel, immer das Nächste Level betreten zu können (nach Level 1 Level 2 dann 3 dann 4 usw.), der Command sah jedoch vor, nach dem Erreichen des Ziels immer zum 2. Level zu wechseln, was sich in der Stunde nicht mehr lösen lies.

Malte hat weiter am Schuss gearbeitet und dieses Skript geschrieben:

![Stunde 14 (Schuss)](https://user-images.githubusercontent.com/69623479/97292665-d3cd6800-184b-11eb-8e21-a6d32b0c724f.PNG)

Die Lösung für das Problem letzter Stunde wurde durch das einfügen einer Variable gelöst. Die Variable ist solange 0 wie der Schuss fliegt. Dann kann man durch den Befehl "if key pressed and schuss=1" regulieren ob man schon wieder einen Schuss abfeuern kann (es wurde eine Flag gesetzt).

### <a name="15"></a>Informatik Stunde 15:

Die Lösung für das Problem aus Stunde 14 stellte sich in dieser Stunde als simpel heraus.
Denn da der Code für das eine Ziel funktionierte um zum 2. Level zu gelangen, war es naheliegend denselben Code für eine weitere Zielsprite zu nehmen, nur dass das nächste Ziel entsprechend für das nächste Level programmiert war.
So ordnete Yannick ein neues Ziel mit entsprechend angeglichenem Code den einzelnen Leveln zu (zu diesem Zeitpunkt gab es Level 1-3).

![1 ziel pro level](https://user-images.githubusercontent.com/69623479/94909410-670cbb00-04a3-11eb-8ca2-479f4fc7ef0f.PNG)

Da Yannick sich schon zu Hause diese Lösung überlegt hatte war die Umsetzung schnell erreicht.

Die übrige Zeit nutzte er um an einem neuen Element im Spiel zu arbeiten: dem Trampolin.
Würde man dieses berühren, sollte ein größerer Sprung automatisch ausgeführt werden. 
Bis auf den Feinschliff in Sachen Effektstärke und implimentierung im Spiel selbst wurde dies auch noch in derselben Stunde erreicht.

![Anfang Jump and run spiel script pic (1)](https://user-images.githubusercontent.com/69623479/94910469-0aaa9b00-04a5-11eb-872c-f330b15abc20.png)

Zu Hause hat sich Yannick zudem noch mit einer weiteren Mechanik beschäftigt.
Von 3 Leben, sollten beim Herunterfallen von Plattformen eines abgezogen werden und der Character zurück zum Anfang des Levels gebracht werden.
Dies ließ sich reibungslos einfügen:

![Anfang Jump and run spiel script pic (1)](https://user-images.githubusercontent.com/69623479/94911146-fdda7700-04a5-11eb-9771-310b6a782ed3.png)
 Zudem wurde noch direkt eine entsprechend auf die Variable reagierende Graphik eingefügt:

![leben anzeige](https://user-images.githubusercontent.com/69623479/94911297-337f6000-04a6-11eb-9427-29465f80b133.PNG)

Malte hat sich damit beschäftigt Gegner ins Spiel zu implementieren. Als erstes fügte er eine ähnliche Mechanik wie beim Charakter für die Leben, für die insgesamt drei Gegner ein. So starteten sie bei 2 Leben und verloren immer wenn sie den Schuss berührten 1 Leben. Bei 0 Leben ließ Malte sie mit dem "hide" Befehl verschwinden . Das Problem war, dass die Variable für die Leben bei einem Treffer direkt auf 0 gesetzt wurde, da mit einem Schuss mehrere Leben abgezogen werden konnte. Dies hat Malte dann mit einer Variable gelöst, die 0,5 Sekunden 0 ist und dann erst 1. Dann hat er die Bedingung, dass das zweite Leben erst abgezogen werden kann wenn diese Variable 1 ist eingefügt. 
Zuletzt wollte Malte einfügen, dass die Gegner nachdem sie ein Leben verloren haben "wütend" werden. Dass hieße sie ändern ihr Aussehen und bewegen sich schneller. Dies wurde mit einem eigenen Skript umgesetzt. Das Endergebnis dieser Stunde sah wie folgt aus:

![15  informatik Stunde (Gegner)](https://user-images.githubusercontent.com/69623479/97293348-d7152380-184c-11eb-9c35-ce60f3f984bd.PNG)

### <a name="16"></a>Informatik Stunde 16-22:

Im Zeitraum um die 16. Stunde entschieden wir uns das Spiel nicht zu einem Platformer/J&R zu machen, sondern es als eine Art Brawl-Game weiterzuentwickeln.

Wir erstellten also eine Testumgebung die sehr grob der Struktur des Spiels entsprechen würde:

![testumgebung](https://user-images.githubusercontent.com/69623479/97292436-88b35500-184b-11eb-8eb0-9c4b5769e668.PNG)

Um die Testumgebung vollständig nutzen zu können mussten wir jedoch noch den Code für unsere Blöcke fertigstellen (Das ungelöste Problem von Stunde 8,9). 

Dies konnte dieses mal auch endlich erreicht werden, indem wir eine Variable als Bedingung für die Bewegungscommands eingefügt haben.
Außerdem fanden wir noch heraus, dass man in Snap die einzelnen Sprites zusammenkleben konnte. Da unsere individuellen Blöcke jeweils aus 4 Teilen bestehen war dies eine extreme Vereinfachung beim Programmieren der Blöcke in der Stage.

![blockbedingungsvariable und neue richtung fürs spiel cleaner](https://user-images.githubusercontent.com/69623479/97292038-0460d200-184b-11eb-9288-b932dc342561.PNG)

Desweiteren erarbeiteten wir ein Konzept zur klaren Weiterführung des Spiels. Dieses umfasste die 2 verschiedenen spielbaren Charactere, die Stages und deren interaktive Elemente und zuletzt noch eine grobe Idee für Items die nur bei eventuell noch übriger Zeit implimentiert würden.
(Das Konzept mit allen Ideen haben wir an dieser Stelle eingefügt)

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
-      aktive Fähigkeit: Idee 1: Schlag auf den Boden dann „Erdbeben“ und Feind wird gestunnt
- Primär Waffe: Laser Minigun
- Sekundär: Fette Faust
	- langsamer
	- Massiver gepanzerter Cyborg
	
Gonzales:
	- Dreischussswaffe
	- kurzer instant teleporter
	- Messer/Dolch (vllt Backstab)
	- Maskierte Pflanze oder Affe mit Anzug

(Items:
    • Leben, Movement boost, Damage Boost…)


Im Rahmen dieses Konzepts begannen wir das graphische Design des Spiels.

Erste concept-pixelarts vom Character "Alphonzo" enstanden bis hierhin.

![Alphonzo konzept 1](https://user-images.githubusercontent.com/69623479/101027186-12a3bb80-3578-11eb-992f-aebb3ec3fa8e.png)

### <a name="23"></a>Informatik Stunde 23:

Wir haben die ganze Stunde den Blog geschrieben

### <a name="24"></a>Informatik Stunde 24:

Nachdem wir unsere Ideen ausgetauscht haben und wir die nächsten Schritte geplant haben, hat Malte Blog geschrieben und Yannick hat sich mit Gonzales Teleport beschäftigt. Das Hauptpproblem in dieser Stunde war, dass man sich in die Blöcke der Stage hinein teleportieren konnte. Dies hat Yannick gelöst indem er einen "anti-teleportations-marker" in den Blöcken platziert hat. Berührte man diesen Marker wurde man automatisch sofort außerhalb des Blockes gesetzt. Teleportierte man sich also nun in den Block und somit auf den Marker, wurde man automatisch sofort an die Richtige Stelle, links oder rechts vom Block, gesetzt. Dies funktionierte soweit gut, jedoch hatte das System einen Schönheitsfehler, nämlich dass man sobald man von unten an den Block heransprang, aus einem Unerklärlichen Grund den Marker zu berühren schien und somit auch wenn man sich nicht in den Block Teleportiert hatte, sondern eben nur dagegen Sprang zur Seite gesetzt wurde.

### <a name="25"></a>Informatik Stunde 25:

Heute hat Yannick den Teleport vom Character Gonzales fertiggestellt. Das Problem, dass der Character wenn er nur gegen Block sprang , dennoch aber zur Seite teleportiert wurde, hat er gelößt, indem er eine Flag gesetzt hat, welche dafür sorgte, dass die Eigenschaft des "anti-teleportations-markers" nur dann aktiv war, wenn der Teleport auch tatsächlich genutzt wurde. 
Darüber hinaus wurde noch eine Variable für die Funktion des Cooldowns der Fähigkeit integriert.
Der code für den Teleport sah dann, vollständig wie folgt aus:

![teleport](https://user-images.githubusercontent.com/69623479/100083813-3a917180-2e4a-11eb-9a45-5b4c72e291b9.PNG)

Malte hat sich mit der Fähigkeit von Alphonzo beschäftigt: dem Slam. In die if schleife wurde als Bedingung "if key s is pressed and not touching block oben and dash active= 0" gesetzt. D.h man kann den Slam erst ausführen, wenn man die Taste "s" drückt, man nicht den Block oben berührt und der "dash" nicht gerade durchgeführt wird. Dann wird eine Schleife aktiviert, die solange bis man den block oben wieder berührt den Charakter mit -20 nach unten bewegt.
Da man oft in den Boden glitchte, wenn man den Slam ausführt, hat Malte einen Befehl implimentiert, der wenn man den Slam ausführt, am Ende prüft, ob man in den Bock reingeglitcht ist und wenn dies der Fall ist den y wert um 20 erhöht. Um zu vermeiden, dass man während man den Slam ausführt den Slam erneut ausführen kann, wird die Variable "dash active"= 1 gestzt und am Ende wieder =0, da in der if schleife die Bedingung dash active = 0 gesetzt wurde. Das endgültige Skript sah dann so aus:

![25  informatik Stunde (Slam)](https://user-images.githubusercontent.com/69623479/100733300-42af5b00-33ce-11eb-881b-eaef8a858011.PNG)

Da wir einen Rückstoß simulieren wollten um das Treffen des Slams deutlicher und realistischer zu machen, fügte Malte dieses Skript ein:
![25  informatik Stunde (Slam 2)](https://user-images.githubusercontent.com/69623479/100733297-4216c480-33ce-11eb-9171-409cac5ba0a7.PNG)

### <a name="26"></a>Informatik Stunde 26-30:

Yannick nahm sich nun einen Startscreen mit allen gewünschten Features vor.
Es sollte ein Startscreen zum allgemeinen Starten des Spiels, sowie Auswahlscreens für sowohl Charactere als auch Stages entstehen.
Dabei entstand in der Stunde 26 und zu Hause ein sehr großer Codeblock, da Yannick dieses mal alle Features in einen einzelnen Codeblock eingearbeitet hatte.
Vieles funktionierte direkt jedoch taten sich 2 Probleme auf.
1: Die an sich funktionierenden Commands reagierten nicht immer direkt. Drückte man also die Taste um zum nächsten screen zu kommen reagierte das Programm manchmal direkt manchmal nicht. 
Es stellte sich heraus das dies an der Animationsschleife der Auswahlscreens lag. Der Command ließ sich erst stoppen wenn die Animation durchgelaufen war. Hielt man die Taste zum Weiterkommen gedrückt (für maximal 0.8 sekunden, da dies die länge der Animation ist) funktionierte alles wie geplant. Das war in unserem Ramen zufriedenstellend, da es die Funktionalität in keiner Weise einschränkt, solang man weiß, dass man gedrückt halten muss, bis man weitergekommen ist.

Hier ein Beispiel für eine Solche Animation welche erst durchlaufen muss (insgesamt gibt es davon natürlich viele):

![startscreen gedrückt halten beispiel](https://user-images.githubusercontent.com/69623479/100083808-37968100-2e4a-11eb-90df-4b9324f18e4d.PNG)

2: Wurde der Startscreen beendet so ignorierte das Programm den Command welcher dafür sorgen sollte zu einem neutralen screen überzugehen und behielt stattdessen den zuletzt vorhandenen Auswahlscreen bei.

Dies sah so aus: 

![startscreen fertig aber bild nicht neutral bug](https://user-images.githubusercontent.com/69623479/100084499-2437e580-2e4b-11eb-9d8d-24bbd7d3ef6f.PNG)

Wobei es eigentlich folgendermaßen aussehen sollte: 

![startscreen so solls eigentlich sein](https://user-images.githubusercontent.com/69623479/100084506-25691280-2e4b-11eb-8d7b-754df495edeb.PNG)

Dieses Problem beschäftigte Yannick über einen längren Zeitraum da er weder einen Fehler oder eine Unstimmigkeit im code, noch ein "workaround" finden konnte.
Ein Gedanke war z.B. das Neutralisieren des Hintergrunds mit einem "wait X seconds" command zu verzögern um wieder zu garantieren, dass die Animation des Auswahlscreens durchlaufen kann, da dies ja wie beschrieben zuvor schon Probleme bereitet hatte, jedoch blieb auch dieser, sowie andere Versuche erfolglos.

Zuletzt löste sich sich das Problem als Yannick die individuellen Teile des Startscreens auseinander nahm. Sobald der finale Command welcher für den Übergang von Startscreen zum tatsächlichen Spiel zuständig war vom großen Block getrennt wurde funktionierte alles einwandfrei. 
Weshalb sich das Programm so verhielt blieb uns Unerklärlich, da inhaltlich beim Command nichts verändert wurde, sondern er lediglich in einen eigenen Block gebracht wurde.
Doch das Problem war gelöst und der Startscreen somit insgesamt abgeschlossen.

Zu Hause beschäftigten wir uns desweiteren Regelmäßig mit dem Design des Spiels. Die zu Designenden Elemente wurden aufgeteilt.
Malte sollte die Stages designen und Yannick die Charactere inklusive Animationen.
Der Startscreen blieb in der Aufteilung bis aufs weitere aus, da die Aufwendigkeit desselben sich leicht auf die übrige Zeit vor Abgabe anpassen lässt.
Das Design blieb neben dem Programmieren bis auf weiteres ein Parralel laufender Prozess.

Nun waren alle absoulut notwendigen Elemente integriert.
Wir begannen also mit etwas, dass wir uns schon eine Weile vorgenommen hatten. 
Wir wollten das Programm neu aufsetzen, da im Entstehungsprozess aus einigen Gründen sich überall Unschönheiten zeigten. 
Sei es ein obsoleter Programmschnipsel für ein inzwischen nicht mehr genutztes Feature oder ein unkompakter Programmierstiel.
Außerdem befanden sich einzelne Features in unterschiedlichen Speicherständen da Malte und Yannick ja oft gleichzeitig an unterschiedlichen Features gearbeitet hatten.
Mit dem neuen Aufsetzen sollte also alles sauber und kompakt zusammengefügt werden.

### <a name="31"></a>Informatik Stunde 31-Abgabe:

Bis zum Schluss waren wir damit beschäftigt alle Elemente zusammenzuführen.
Alle Grafiken an den richtigen Ort zu bringen, jedes Feature zu implimentieren etc.
Einige Dinge z.B. in der Funktionsweise der Blöcke oder der Animation des Startscreens wurden so verändert das die Funktionalität eher als die Ästhetik garantiert war.
Z.B. sorgte das Blinken der Grafik die anzeigte, welcher Character von Player 1/2 angewählt war für Bugs und wurde somit entfernt, sodass die Anzeige zwar statisch, aber dafür 100% funktionell war.
