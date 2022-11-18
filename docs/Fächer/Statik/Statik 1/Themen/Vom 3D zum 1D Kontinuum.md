### Allgemeines
Jo :d schauen wir uns also jetzt einmal an, wie ich für die berechnung zur vereinfachung aus einem Balken, ein Strich machen kann.

schauen wir uns mal ein Beispiel an:

![[IMG_8E7C53B490E2-1.jpeg]]

Hier haben wir eindeutig ein 3D-Problem was wir haben. Die Straße und der Kran.

Aber dank ein paar Regeln, können wir das ganze ohne Problem in Striche ersetzen, weil wir die Informationen ja nach wie vor gegeben haben.


### Strukturthema inder 2D Balkentheorie

Auch in der Statik, haben wir einen sogenanten Kreislauf, wie wir aus Belastungen, Verschiebungsgrößen machen können. Schauen wir uns diesen Kreislauf einmal genauer an:

![[IMG_64CEE58F9B48-1.jpeg]]

Wir haben links oben unsere Ausgangssituation, und gehen dann erstmal runter um die inneren Größen die <mark style="background: #FF5582A6;">Schnittgrößen</mark> zu berechnen. 

Die Beziehung zwischen den Äußeren und den Inneren Belastungen, wird durch die <mark style="background: #FF5582A6;">Gleichgewichtsbedingungen</mark> hergestellt.

Dann gehe ich von den Schnittgrößen rüber nicht auf innere Kraftgrößen, sondern diesmal auf <mark style="background: #FF5582A6;">innere Weggrößen, also den Verzerrungen.</mark>

Diese beziehung, wird durch die Werkstoffbeziehungen hergestellt.

Dann haben wir also auch die inneren Weggrößen. Naja wenn wir die inneren Weggrößen haben, könenn wir doch auch die äußeren Weggrößen haben :D 

<mark style="background: #FF5582A6;">Diese Beziehung wird dann durch die geometrischen Beziehungen hergestellt.</mark>

Dieser Kreislauf sieht jetzt ein wenig wüst aus, hier mal eine Vereinfachung :

![[IMG_B15BB92489FD-1.jpeg]]

Belastungen sind b. 

Alle schnittgrößen zusammen ergeben die Spannungen was wir auch als $\sigma$ kennen.

die Inneren inneren Weggrößen sind unsere Verzerrungen bzw. Dehnungen was wir als $\epsilon$ kennen.

Und zu guter letzt, haben wir die Äußeren Weggrößen also die Verschiebungen, welches wir von Balzani als u kennengelernt haben :D

Die Schnittgrößen und die Verzerrungen, werden wir uns ganz besonders Anschauen. Bei den Schnittgrößen erhalten wir nämlich das N,Q und M.

Bei den Verzerrungen, erhalten wir Materialgrößen wie $epsilon$(Dehnungen), $gamma$(Gleitungen) und $\kappa$(Krümmungen). Was die drei Dinge sind, lernen wir gleich noch :D

### Vom 3D-Kontinuum, zum räumlichen Stabtragwerk.

Schauen wir uns doch jetzt mal an, wie ich denn genau von einer 3D-Struktur, in ein 1-Dimensionales System komme:

![[IMG_7092AAC637CA-1.jpeg]]

Ich sehe hier einen Stab. Auf diesem Stab wirken natürlich Spannungen (Resultierende aus Schnittgrößen) und Verzerrungen (Resultierende aus inneren Weggrößen)

Naja, der einzige Trick ist, wie wir hier sehen, ist, dass wir einfach entlang dem schwerpunkt eine 1 Dimensionale linie definieren. 

Auf diese Linie, definieren wir dann größen.

##### Grundlegende Hypothese der Stabtheorie:
Der stab kann:
- sich verdrehen aber ER BLEIBT STARR
- Querschnitte bleiben Eben

### Gleichgewichtsbedingungen - Ebener Balken
Schauen wir uns mal fix die Schnittgrößen an:

![[IMG_8ED5ACD5DB0C-1.jpeg]]

Die Resultierende der Spannung in x Richtung, ist die Normalkraft

Die Resultierende der Schubspannung ist die Querkraft

Die Spannung in x-Richtung+Hebelarm ergibt dann unser Biegemoment.

schauen wir uns ein anderes Bild an:

![[IMG_3DD48EB43178-1.jpeg]]

wir haben halt diesen Balken.

![[IMG_3DD48EB43178-1 2.jpeg]]

Dank der Differentialgleichungen aus der Elastostatik, könenn wir mit deren Hilfe, die Schnittgrößen easy berechnen.

Wir können direkt sagen, dass wenn wir wie hier in dem Beispiel, eine konstate Linienlast in z-Richtung habe, dass mein Q(x) linear sein wird, und seine Ableitung das M(x) quadratisch sein wird.


### Geometrische Beziehungen
Jetzt kommen wir zu den Geometrischen Beziehungen. Also von den inneren Weggrößen, zu dein äußeren Weggrößen.

Zunächst einmal müssen wir verstehen, dass in der Balkentheorie zwei unterschiedliche Betrachtungsmöglichkeiten gibt. Einmal ist es die [[Bernoulli-Balkentheorie]] und die [[Tymoshenko-Balkentheorie]].

Da wir die Verdrehung bei der Tymoshenko auch 0 setzen können und somit direkt die Bernoulli-Theorie haben, betrachten wir zunächst die Tymoshenko Theorie.

Schauen wir uns dazu noch ein Bild an:

![[IMG_2D1F379527E4-1.jpeg]]

Verschiebung werden bekanntlich mit u abgekützt.

Klar... bei einer Verdrehung, werden die Punkte sich verschieben.

Die Verschiebung des Punktes P, hat sowohl eine x, als auch eine y-Komponente.

Wir wissen, wenn wir etwas in Komponenten aufteilen, haben wir direkt sinus und cosinus im Spiel. Das Problem ist, Sinus und Cosinus sind keine Linearen Funktionen... Verkaaackt :D

Nee :D

Wir betrachten zunächst einmal die Theorie I. 

Die Theorie I besagt, dass wir sehr sehr kleine Verformungen haben. Somit nehmen wir an, dass alles immer nur sehr sehr sehr kleine Verformungen hat.

Das hat den Vorteil, dass wir alles Linearisieren können welches uns das Leben vereinfacht :D

>Dank der Theorie I, können wir annehmen dass
>$cos(\alpha) \approx 1$
>$sin(\alpha) \approx \alpha$

Nun.. wenn wir dann das cos und sin einsetzen erhalten wir:

![[IMG_C1FD3949E7A0-1.jpeg]]

Das $u_x$ beschreibt nur das die verschiebung des Punktes P. Da sich der Mittelpunkt ja aber auch verschiebt, müssen wir das natürlich auch betrachten.

Das macht die funktion $u_x(x,z)$. Der beschreibt die Bewegung des Punktes inkl. dem Mittelpunkt.

Schauen wir uns aber doch mal die verschiebungen des Punktes doch mal genauer an:

![[IMG_AE94C75BC3EB-1.jpeg]]

Hier haben wir das Bild nochmal in ein wenig größer :D


Wir haben auf die neutrale Faser eine Tangente gelegt.... Tangente ist nichts anderes als die Ableitung.

die Tangente, hat natürlich eine Neigung zu der Neutralen Faser ($w_{z,x}$)

Aueßrdem hab ich auf die neutrale Faser noch einen Normalenvektor gelegt.

>Wir erinnern uns, der Normalenvektor ist immer Senkrecht

Aber auch der Normalenvektor hat eine Neigung zu der Neutralen faser($\theta_y$)

Nehmen wir jetzt diese Beiden Neigungen und addieren sie, erhalte ich die sog. **Schubdeformationen** oder auch **Gleitung** genannt.


### Geometrische Beziehung - Ebener Balken

Fassen wir das Eben gelerne also einmal zusammen:

![[IMG_46B17C7E919A-1.jpeg]]

Wir haben oben die [[Verzerrung und Hooksches Gesetz|Verzerrung]] aka. die Dehnung in Normalrichtung. 

>Wie berechnen wir nochnal die Dehnung?
>Aus der Ableitung der Verschiebung :D also $\frac{du}{dx}$

Dann haben wir die Gleitung, die wir gerade ja gelernt haben

>Wie berechnen wir nochmal die Gleitung?
Da nehmen wir die Neigung der Tangente der Neutralen Faser $w_{z,x}$ + die Neigung des Normalvektors $\theta_y$

Was wir noch haben, ist die Krümmung. Doch was ist die Krümmung ? 

>*"Die Krümmung ist die Veränderung(Ableitung) des Drehwinkelts über die Gesamte länge"*

>Wie berechnen wir also dann die Krümmung?
>Wie wir bei der Dehnung die Ableitung der Verschiebungen haben, haben wir bei der Krümmung die Ableitung diesmal von dem Winkel.

### Geometrische Beziehung - Räumlicher Balken
Schauen wir uns jetzt einmal die Räumlichen Verzerrungen an, allgemein aus der  Konitnuumsmechanik kann man die Verzerrungen nämlich als ein Tensor darstellen:

![[IMG_81ED1F49D177-1.jpeg]]

Auf der Hauptdiagonale haben wir die <mark style="background: #FFB86CA6;">Normalverzerrungen</mark>, während wir auf den Nebendiagonalen die <mark style="background: #FFB86CA6;">Schubverzerrungen</mark> haben.

Man könnte das jetzt alles berechnen bla bla bla :D 

Ich erspar mir und dir lieber leser das und komme direkt mal zum Ergebnis:

![[IMG_86A006800111-1.jpeg]]

Nach viel rechnerrei undso, erhält man das dieses Ergebnis :D

Man erhält den Spannungstensor :DDD

Dass unten rechts die 4 Zahlen eine 0 steht liefert uns einfach den Beweis, dass es ein starrer Körper ist.

Wenn wir das ganze jetzt noch weiter Ausmultiplizieren, haben wir folgende Gleichungen raus:

![[IMG_AB041334FEB0-1.jpeg]]

Zum einen haben wir die Verzerrung der Mittellinie, wir haben da einen Anteil der Dehnung in x-Richtung Anteile mit Krümmungen in y und z-Richtung.

Dann habe ich natürlich auch meine Schubkomponenten.

Die haben allerdings die schon bekannte Gleitung, oben in y Richtung unten in z richtung, und dann natürlich die Krümmung noch in x-Richtung :D

### Zusammenfassung
Hier haben wir also noch zusammenfassend unsere Verzerrungsresultierenden, in der x-z-Ebene.

![[IMG_918F71AD6CD5-1.jpeg]]

Dann haben wir natürlich noch um die y-z Achse:

![[IMG_CD2ADEDFD608-1.jpeg]]

![[IMG_0531E8976A7B-1.jpeg]]

