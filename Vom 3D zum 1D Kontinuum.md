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

Zunächst einmal müssen wir verstehen, dass in der Balkentheorie zwei unterschiedliche Betrachtungsmöglichkeiten gibt. Einmal ist es die [[Bernoulli-Balkentheorie]] und die [[Tymoshenko-Balkentheorie]]

