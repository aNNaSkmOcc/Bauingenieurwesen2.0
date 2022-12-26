# 5. Schubspannungen

##### Einführung

Die Schubspannungen sind eigentlich genau so wie die Normalspannungen. Bei der Normalspannung war das so, dass die Resuliterende aller Kräfte in Normalrichtung die Normalkraft N war.

Bei der Schubspannung ist das eigentlich genau das gleiche, hier ist das allerdings umgekehrt... hier ist die Resultierende aller Kräfte senkrecht zur Normalkraft die Querkaft 

Schauen wir uns mal nen Querschnitt an:

![[Bildschirmfoto 2022-05-06 um 22.13.53.png]]

genau also wir haben da mal so ein Balken. Der Prof ist hingegangen und hat mal so ein Stück abgeschnitten. (Rechts der Würfel). 

$\tau_{xz}$ ist das selbe wie $\tau_{zx}$ weil Symmetrie im Spannungstensor.

Ok, rechts ist die Schubspannung $\tau_{xz}$, weil die Normalkraft in x richtung geht, die schubspannung aber in z-Achse geht weil senkrecht ^^ diese ist natürlich nicht 0, weil wir ja Krafteinwirkungen in der Richtung haben nämlich q. Bei der $\tau_{zx}$ Seite allerdings haben wir von der oberen Kante, bis zur unteren Kante 0, weil wir ja keine Kraft in dieser Richtung haben.

---

##### Einfach Symmetrische Querschnitte

schauen wir uns mal so ein symmetrischen Querschnitt mal an:

![[Bildschirmfoto 2022-05-07 um 12.29.22.png]]

Aus numerischen bzw halt schwere Berechnungen kan man feststellen, dass die Schubspannung nicht nur Straight in die x-z Ebene wirkt, sondern auch zur Seite hin in richtung x-y Achse. Diese sind aber so gering, dass man sie vernachlässigen kann.

Für uns relevant ist also die Schubspannung in x-z Richtung über die länge :) DIESER WERT, bildet dann gleichzeitig den Mittelwert über die Breite ab.

Rechts sehen wir die Spannungsverteilung der Schubspannung von dem Querschnitt. Das neue hier ist der sogenannte Schubfluss.. das ist joa so eine Art vorintegral. Also die Resultierende nicht über den ganzen Querschnitt, sondern vom Rand bis zur einer bestimmten Faser z.

Also ist der Schubfluss eingeführt als $t(x) = \tau(z) \cdot b(z)$ Schubspannung an der Stelle z, mal der Breite an der stelle z des Querschnitts.

Die Aufgabe ist jetzt eine Formel zu finden, die uns das berechnen des $t(z)$ bzw. $\tau(z)$ ermöglicht ^^

---

##### Gleichgewicht an Infinitesimalen Balkenelement

![[Bildschirmfoto 2022-05-07 um 12.54.23.png]]

Schauen wir uns mal ein klitzekleines Stück des Balkens an. Die breite des Stückes ist unendlich klein. die Höhe ist gleichgeblieben... deswegen ist die breite auch dx. oben haben wir die verteilte Last, links und reichts ein paar Schnittgrößen usw usw.

jetzt schauen wir uns von dem unendlich kleinen Stück, wieder ein unendlich kleines Stück an, diesmal haben wir ein stück abgeschnitten, wo die höhe unendlich klein ist. Deswegen ist die höhe dieses stücks dz und die breite immernoch dx.

schauen wir uns das Ding mal in 3D an :

![[Bildschirmfoto 2022-05-07 um 13.21.45.png]]

Auch hier haben wir wieder Schub- und Normalspannungen die Kräfte im Negativen Schnittufer also die die nach rechts zeigen sind easy:

Da nimmt man einfach die Schubspannung $\tau$ mal die tiefe $b(x)$ mal die breite $dx$. Für die Normalspannung genau das gleiche, die Nornalspannung $\sigma(x)$ mal die höhe $dz$, mal die tiefe $b(x)$

soo im Positiven Schnittufer wirds interessant, da ist das nämlich etwas anders. Wie man das rechnet, ist in der Spannungsverteilung darüber son bisschen erklärt.

Es ist klar, dass die Spannungen mit der Länge des Balkens zunehmen, deswegen ist das eine Lineare Verteilung. Am anfang ist die lineare verteilung halt 0, deswegen haben wir da nur $\sigma(x)$ am ende hingegen, ist der Funktionswert halt nicht mehr 0, sondern $d\sigma(x)$.

Das $d\sigma(x)$ berechnen wir quasi mit der steigung (also ableitung der Funktion \sigma(x) mal die länge des Schnittes also dx).

Also haben wir für das linke Schnittufer für die Spannung, die Spannung \sigma(x) am anfang, und am Ende natürlich plus den Zuwachs  am ende $d\sigma(x)$.

Das selbe spiel, analog zur unteren Schubspannung, die nach rechts zeigt.


okay wir wollen ja was rechnen, dazu machen wir die Summe aller Kräfte in x richtung:

![[Bildschirmfoto 2022-05-07 um 14.08.22.png]]

und erhalten folgende Differentialgleichung^^ wir haben ja nicht t ist gleich irgendwas, sondern $t'(z)$ da stehen.

![[Bildschirmfoto 2022-05-07 um 14.13.50.png]]

Nun setzen wir unser \sigma(x) ein, N ist gleich 0 weil wir nur reine Biegung betrachten. Das z hat nix mit x zutun, deswegen können wir das rausklammern, und das $I_y$ können wir auch Rausklammern, weil es Konstant ist. Dann bleibt also nur noch über wenn wir das $M_y$ ableiten ja gerade die Querkraft $Q(x)$

Jetzt wollen wir ja t(z) haben und nicht die Ableitung. Deswegen müssen wir das ganze auf beiden Seiten integrieren:

![[Bildschirmfoto 2022-05-07 um 14.19.54.png]]

Als Grenzen wählen wir die oberste Faser z_0 welche ja 0 ist, und als untere Grenze irgend eine beliebige Stelle z im Querschnitt. das $Q_z$ durch $I_y$ dürfen wir ausm Integral ziehen, weil es wahrscheinlich Konstant ist. jetzt dürfen wir nicht z Integrieren, weil wir z ja als Grenze gewählt haben. Deswegen integrieren wir jetzt einfach z-schlange ^^ da $b(z) \cdot dz$ ja die Fläche ist, kann man das auch einfach dA nennen.

Joa dann setzt man halt seine obere und untere Grenze ein und rechnet das aus. Zur vereinfachung, nennen wir das Integral dann einfach $S_y(z)$. Das t(z_0) entfällt, weil wir bereits wissen, dass es 0 ist.

JOA EASY dann bekommen wir unsere beiden Formeln:

![[Bildschirmfoto 2022-05-07 um 14.52.13.png]]

Das gleiche geht auch wieder mit Dünnwandigen UTIL Profilen:

##### Einfach Symmetrische dünnwandige Querschnitte
![[Bildschirmfoto 2022-05-07 um 15.00.28.png]]

Bei den dünnwandigen Querschnitten führt man die Laufkoordinate s ein. s läuft immer so wie beispielsweise eine Flüssigkeit durch den Querschnitt laufen würde. z.B bei dem mittleren Querschnitt wenn ich da wasser durchlasse, würde es nach unten fliesen :) also genau so dann die laufkoordinate s auch. 

Die Herleitung ist wieder ähnlich wieder kleines stück schneiden (wie das ding rechts)

Wieder Spannungen einzeichnen, summe in x richtung bilden erhält man das hier:

![[Bildschirmfoto 2022-05-07 um 15.11.03.png]]

Wir wollen wieder das t alleine stehen haben und keine Differentialgleichung also integrieren:

![[Bildschirmfoto 2022-05-07 um 15.18.14.png]]

Wichtig ist hierbei, dass wir jetzt nicht z haben, sondern s

ja dann sehen unsere Formeln so aus:

![[Bildschirmfoto 2022-05-07 um 15.20.12.png]]

##### Lange rede kurzer Sinn: Wie berechne ich jetzt so eine Aufgabe ?

1. Auflagerkräfte
2. Schnittgröße
3. Gesamtfläche
4. Trägheitsmoment
5. statische Momente
6. Schubspannungen via Formel berechnen
7. Normalspannungen via Formel berechnen