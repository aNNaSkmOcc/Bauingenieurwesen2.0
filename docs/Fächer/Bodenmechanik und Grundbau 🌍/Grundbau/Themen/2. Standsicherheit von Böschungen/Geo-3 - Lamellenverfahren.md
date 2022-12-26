### Allgemeines
Das Lamellenverfahren, nutze ich, wenn ich quasi Runde Gleitflächen habe.

Im Prinzip, funktioniert das wie [[Setzungsprognosen - indirekte Methode]], wo man den Boden in Lamellen unterteilen kann und dann das berechnet.

Man nimmt da so ca. 3-10 Lamellen :d das ist ein gutes maß.

Außerdem, teilen wir hier dann die Lamellen diesmal Vertikal auf und nicht horizontal.

Was noch wichtig zu wissen ist, dass man das mit Momenten nachweist.

![[IMG_4BB8C1D16350-1.jpeg|300]]

Hier sehen wir, dass wir die Lamellen aufgeteilt haben.

Außerdem haben wir noch oben den Punkt, das ist der Öffnungswinkel.

>Hier mal ein paar kleine Tipps vom Prof, wie man die Lamellen aufteilen sollte:
>- Am Anfang und Ende von Belastungen
>- Da wo knicke sind
>- Schnittpunkt von zwei schichten
>- Wenn man das alles hat, teilt man halt noch so auf dass es gleichmäßig wird :D

Gant allgemein, müssen wir folgende Kräfte betrachten:

![[IMG_04361DE3FF1D-1.jpeg]]

Das sieht jetzt sseeeehr sehr wüst aus. Wir werden aber alles Schritt für schritt durchgehen :d

### Treibendes Moment $E_{M,d}$ 
Um den jetzt zu berechnen gehen wir so vor:

1. Bodeneigengewicht / Auftrieb
2. Verkehrslasten
3. Strömungskraft

##### 1.1 Bodeneigengewicht
Hier fangen wir dann an, für jede Lamelle den Flächeninhalt zu berechnen. Darauf kommt dann noch mal Wichte vom Boden, dann haben wir das Eigengewicht.

Wichtig ist nur, dass wir erstmal nur die charakteristischen Werte haben, heißt also ohne Beiwerte.

Die Teilsicherheitsbeiwerte die kommen dann gleich noch dazu :D

---

##### 1.2 Auftriebslast
Jenachdem, ob der Boden irgendwo unter Wasser steht , machen wir das gleiche nur für die ebereiche, wo das ding unter Wasser steht.

---

##### 2 Verkehrslasten
Jetzt wirds interessanter :D 

Jetzt kommen ja noch die Auflasten mit ins spiel. Auflasten sind auch Veränderliche lasten.... diese sind **nicht immer da**.

Deswegen ist es wichtig vorher zu bestimmen, ob man diese überhaupt ansetzen muss oder nicht. Wenn man die nämlich ansetzt ohne dass man die braucht, ist das günstiger also unsicherer für uns :D

Woher wissen wir denn, ob wir jetzt Verkehrslasten brauchen oder nicht ?

Schauen wir uns das mal für eine Lamelle an:

![[IMG_956460286F09-1.jpeg|400]]

Außerdem brauchen wir hier zwei Formeln, mit denen wir das zeigen können, ob wir die Auflast berückstichtigen müssen oder nicht :

![[IMG_FA3A83612E4D-1.jpeg]]

Denn wenn wir die haben, dann müssen wir folgendes Zeigen:

![[IMG_07951800D49F-1.jpeg]]

Wenn das T also größer ist als das $R_\phi$, dann muss ich die Auflasten berücksichtigen.

---

Wenn wir dann die Auflasten, Auftriebskräfte und Eigengewichte haben, können wir die alle addieren und Resultierenden daraus machen :D

Dann können wir auch schon direkt das Momentengleichgewicht machen :D

Wichtig ist nur, dass wir da wo wir eine Auflast haben, dann einen anderen Teilsicherheitsbeiwert nehmen, undzwar nicht die für **ständig** sondern für **veränderliche** die werte Addieren wir dann :D

---
##### 3 Strömendes Wasser
Hier Gibts verschiedene Ansätze, wie man das strömende Wasser ansetzt.

Der einfachste Ansatz dafür ist der Annährungssatz, dieser geht so:

![[IMG_32C2A60A4E71-1.jpeg]]


Es wirkt ja Wasser auf beiden Seiten, linear ansteigend.

das was aber links wirkt, wirkt ja auch rechts das kleine stück.

Das löst sich ja auf und somit machen wir aus einem großen Dreieck, ein etwas kleines Dreieck und ein Rechteck.

Dann können wir auch eifnach die Resuliterenden davon berechnen und 

auch diese in die Momentenbilanz aufnehmen.


### Haltens Moment $R_{M,d}$
Hier mal ein Vorgehen:
1. Reibung
2. Kohäsion


##### 1. Kohäsion

Wir haben ja in jeder Lamelle Kohäsion, daher brauchen wir hier die länge der lamelle.

Für den charakterisitischen Wert, rechnen wir einfach die länge mal kohäsionswert.

Für den design-wert, teilen wir das wieder durch den Sicherheitsbeiwert und das dann für jede Lamelle :D

##### Reibung



