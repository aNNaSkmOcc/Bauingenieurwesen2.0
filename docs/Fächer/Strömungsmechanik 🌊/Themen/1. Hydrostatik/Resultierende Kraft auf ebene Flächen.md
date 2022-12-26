Schauen wir uns nun an, wie denn Drücke unter Wasser eigentlich so wirken... wir wir dass wenn wir ein Gegenstand unter Wasser bauen, wir die statische Berechnung durchführen müssen:

schauen wir uns das Konstrukt doch mal an :


![[IMG_F2042B48B698-1.jpeg|350]]

wir sehen, wir haben nicht eine Konstant rechteckige linienlast, sondern eine die Dreieckig ist... 

ist ja auch klar, denn es ist ja so, dass je tiefer ich bin, desto höher wird auch der Druck.. merkt man ja, wenn man tieftaucht und irgendwann es anfängt in den Ohren zu drücken.

>💡 Der Wasserdruck wirkt **immer** senkrecht zur Fläche bzw Wand

Außerdem, sehen wir eine linienlast $p_0$, die darauf Wirkt... undzwar ist das die Last des Luftes.

>💡 Die Luft wirkt immer auf beiden seiten und **löst sich auf**

Außerden haben wir dort so ein Ding dass sich "**Klappe**" nennt.

Die Klappe ist quasi so eine Art querschnitt der Wand... wir müssen uns vorstellen, dass wir vor der Wand stehen und die Wand anglotzen.

In diesem Beispiel, hat die Wand die grün markierte Form.

okay okay genug erklärt, lets gooo

##### Resultierende Kraft F
Also wir schauen uns ja die Klappe an. Die Klappe hat jedoch eine begrenzte länge.... daher brauchen wir uns nicht den gesamten Wasserdruckverlauf anschauen, sondern betrachten uns nur den Teil der Linienlast, die so breit ist wie die Klappe.

![[Bildschirmfoto 2022-10-24 um 15.52.44.png]]

stellen wir doch mal als erstes unsere [[Grundgleichung der Hydrostatik|Grundgleichung]] auf welche hier lauten würde:

$$p(z) = \rho \cdot g \cdot z$$

Jetzt haben wir allerdings hier das Problem, dass die Klappe bzw. die Wand geneigt ist, und somit nicht mehr in unserer z-y-Ebene.

Daher müssen wir das z umschreiben zu:

$$s \cdot cos(\alpha)$$

Wir führen hier noch eine 3. Koordinate "s" ein, weil auch der Druck p(s) von der Tiefe der Wand abhängig ist. Je tiefer ich bin desto größer

sodass unsere Grundgleichung lautet:

$$p(s) = \rho \cdot g \cdot s \cdot cos(\alpha)$$

Somit haben wir uns jetzt das Trapezförmige stück ausgeschnitten.

Jetzt wollen die Resultierende Kraft aus diesem Trapez.

Dazu brauchen wir den Flächeninhalt der Trapezes... und was eignet sich für Flächeninhalte besser als die [[Integrale|Integralrechnung]].

Somit können die Resultierende Kraft F berechnen:

![[IMG_6DBC13370F63-1.jpeg]]

das $b(s) \cdot ds$ würde dem A also der Fläche entsprechen.

jetzt können wir aber hier das p(s) ersetzen durch unsere Grundgleichung und alles was nicht von s abhängig ist vor das Integral ziehen.

Dann merken wir schnell das wir erst alles haben was nicht von s abhängig ist, aber dann das **statische Moment**, bzw. das **Flächenmoment 1. Grades** auf uns kommt :D

Nun können wir das Sy in unsere gleichung F einsetzen und erhalten :

![[Bildschirmfoto 2022-10-24 um 15.56.22.png]]

---

allgemein un schöner geschrieben lautet unsere Formel für die Resultierende Kraft also:


##### Angriffspunkt der Kraft F
Nun haben wir unsere resultierende Kraft F. Allerdings, wissen wir jetzt noch nicht , wo die Kraft wirkt... das finden wir jetzt heraus :

![[Bildschirmfoto 2022-10-24 um 16.17.13.png]]

Zunächst machen wir ein Momentengleichgewicht um einen beliebigen Bezugspunkt bei s = 0.
Da würde das Moment $F \cdot s_D$ herauskommen. Das ist das Moment von der Resultieren F auf die Klappe.

Dies setzen wir gleich dem Moment von der gesamten Resultierenden der dreieckslast mal den hebelarm s.

das Integral kommt dahingehend zustande, dass p(s) bzw. auch b(s) beides von s abhängen und größer werden, je größer das s werden.

Jetzt können wir das p(s) wieder umschreiben und erhalten wieder Komponenten, die wieder nicht von s abhängen, weöche wie natürlich vor das Integral ziehen.

Diesmal erhalten wir ein Integral irgendwas mit hoch 2, was uns sehr stark an das [[Flächenträgheitsmoment und Biegelinie#^a3b6bf|Flächenträgheitsmoment]] erinnert.

Nun kann ich auch das F ersetzen und nach $s_D$ auflösen.

somit erhalten wir folgende Gleichung:

![[Bildschirmfoto 2022-10-24 um 16.30.50.png]]

##### Was ist der Unterschied zwischen dem $s_D$ und $s_S$ 

Der Unterschied ist, dass der Druckpunkt nicht gleich der Schwerpunkt ist.... der Punkt D ist ein wenig verschoben. Daher haben wir eine sogenannte "Exzentrität"

##### Exzentrizität und Abstand $s_D$

Die Exzentrizität und den Abstand $s_D$ kann man wie folgt berechnen:

![[IMG_8BCA83C65AC7-1.jpeg|300]]
