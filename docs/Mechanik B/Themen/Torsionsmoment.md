# 7. Torsionsmoment
Der Schubmittelpunkt war quasi der Punkt, wo der Querschnitt bzw. der Balken kein Torsionsmoment erleidet. Wenn wir Torsionsmomente haben, müssen wir wissen, wie wir damit umgegehen.

Der Torsionsmoment ist die Resultierende der Spannungen, die so im Kreis gehen mäßig.

Wichtig ist, dass wir das Torsionsmoment, als eine weitere Schnittgröße betrachten.

## Vollflächige Querschnitte

**Wie sieht eigentlich so ein Torsionsmoment aus ?.... schauen wir uns dazu mal einen Querschnitt an:**

![[IMG_3642FFDF46EA-1.jpeg]]

Hier haben wir wieder ein verdrehtes U-Profil. Die Kraft F, wirkt natürlich nicht auf dem Schubmittelpunkt, weil wir sonst kein Torsionsmoment haben.

Wichtig zu sehen ist aber, dass wir bei dem Torsionsmoment, wenn wir auf das U-Profil draufdrücken, dass sich die obere spitze zur Längsachse reinzieht, und die untere Spitze sich zur Längsachse rauszieht.

Das ist die sogennannte Wölbbehinderung, und die Betrachten wir nicht, weil wir dadurch auch zusätzliche 

##### <mark style="background: #D2B3FFA6;">Kreiswelle (Stab mit Kreisquerschnitt ^^)</mark> 

Schauen wir uns mal die Herleitung an einer Kreiswelle an.

![[IMG_1733ECA178A2-1.jpeg]]

Wir haben hier einen fest-eingespannten, runden Stab mit Kreisquerschnitt. Der Querschnitt hat natürlich einen Radius R.

Wir wirken nun ein Moment um den Mittelpunkt der Querschnittsfläche um ein Torsionsmoment zu erzeugen. Um zu sehen, wie sich der Querschnitt dreht, malen wir eine Faser auf (schwarze linie). 

Wir sehen, um welchen Winkel sich der Querschnitt dreht hat. Dieser Winkel wird beschrieben durch den Buchstabe $\chi$.

Wollen wir jetzt aber die Verdrehung auf die ganze länge des Stabes beziehen, berechnen wir dazu die **Verdrillung**

![[IMG_636F362A5917-1.jpeg]]

Die Verdrillung, ist quasi die Ableitung der Verdrehung, also dann $\chi'$.

---

##### <mark style="background: #D2B3FFA6;">Winkeländerung (Gleitung)</mark> 

Jetzt ist das ja so, dass wir bei der Torsion, im Endeffekt eine Gleitung ($\gamma$) von zwei körpern haben. Diese Gleitung möchten wir jetzt berechnen. Dazu schneiden wir uns ein infinitisimal breiten Stück des Stabes ab:

![[IMG_EE6860F55BDF-1.jpeg]]

Betrachten wir zunächst mal das linke Stück:

Wichtig ist zu wissen, dass die gestrichelte Linie quasi darstellen soll, dass das Objekt kein Torsionsmoment hat.

WIr schneiden uns jetzt vom inf. breiten stück, jetzt noch ein inf. schmales Stück ab, sodass wir das Teil in der Mitte haben. Das soll den unveränderten zustand des Stabes zeigen.

unser tatsächlicher stab ist allerdings, das verformte grüne.

Somit können wir zeigen, dass das inf. schmales stück, sich um den Winkel $\gamma$ gebogen hat. Der Abstand von Mittelpunkt zu Mittelpunkt sei a. Via tangenz, können wir das a nun bestimmen.

Also wissen wir auch, dass wir rechts im Querschnitt, dass sich der ganze Stab um $d\chi$ dreht. Das können wir dann auch wieder via tangenz beschreiben.


![[IMG_C41266842D7C-1.jpeg]]

wir haben nun also die beiden Tangenzfunktionen und lösen beide nach a auf. Danach können wir das einfach Gleichsetzen und nach $\gamma$ auflösen.

das $\frac{d\chi}{dx}$ kann man auch laut definition oben umschreiben als dieses v umschreiben :)

Wofür brauchen wir die Gleitung jetzt also? NAKLAR für die Schubspannungen :)

Wir haben gelernt, dass wie die Schubspannungen berechnen können mit: 

$$\fbox{$\tau = G \cdot \gamma$}$$

Dies setzen wir dann ein und erhalten:

![[IMG_59BE3584DB24-1.jpeg]]

Es ist aber wichtig zu wissen, dass das G und v,  konstant sind und nichts mit dem r zutun haben.

Okay, "G" haben wir, ist gegeben und konstant. r haben wir, ist auch gegeben... fehlt uns nurnoch das v. Das können wir über das Torsionsmoment berechnen.

Um das Torsionsmoment zu verstehen, schauen wir uns dazu mal ein kleines Bild an:

![[IMG_F5017B2F0C49-1.jpeg|300]]

unsere Spannungsverteilung ist ja linear, inder Mitte 0, weil der radius ja 0 ist und ganz außen maximal, weil der Radius ja auch maximal ist. Um ein Moment zu berechnen, machen wir einfach Kraft mal Hebelarm. Nur wollen wir das nicht für diese Verteilung, sondern für eine beliebige Verteilung im Querschnitt.

Deswegen bilden wir dann davon das Integral, sodass gilt:

![[IMG_A56BF4B7C47A-1.jpeg]]

Jetzt haben wir zwar v was ja gleichzeitig $\chi'$ ist, wir wollen aber $\chi$ haben, also integrieren wir wieder auf beiden seiten:

![[IMG_98D6F2E8F96A-1.jpeg]]

Das können wir jetzt einfach das errechnete v, in die Formel für die Schubspannung einsetzen und erhalten:

![[IMG_BA58F0A78140-1.jpeg]]

Weil wir ja die maximale Schubspannung berechnen wollen, können wir dies so tun:

![[IMG_7E3251C93869-1.jpeg]]


## dünnwandige , geschlossene Querschnitte

Die Dünnwandigen Querschnitte sind natürlich mehr Praxisorientiert als so ein Vollflächiger Querschnitt. 

Schauen wir uns am besten direkt mal ein Beispiel an:

![[IMG_8BAE268A160A-1.jpeg]]

Das hier ist z.B ein Rohr, dass die Wände sehr sehr dünn hat.

Wir haben zunächst mal einen Schubfluss. Außerdem sind die Wände so dünn, dass die Schubspannung nicht linear, sondern konstant ist.

Auch hier ballern wir wieder ein Torsionsmoment um den Querschnittsfläche.

Auch hier haben wir einen Schubfluss (die Grüne Fläche oben links) dieser ist die Schubspannung * die Dicke.

**Schauen wir uns das grüne stück mal bisschen genauer an:**

![[IMG_6BD0B2E75994-1.jpeg]]

wir haben vorne und rechts wieder unsere Schubspannungen, also länge * breite und hinten bzw. links wieder dasselbe + den zuschlag.

Machen wir jetzt Summe in x-Richtung, können wir das t, dx überall streichen und ehralten, dass $\frac{dt}{ds} = 0$.

So wissen wir, dass das t sich nicht über s ändert und t = t(x) konstant.

Wenn wir ein inf. kleines Stück betrachten, haben wir halt auch ein inf. kleines Torsionsmoment:

![[IMG_F6115E91A202-1.jpeg]]

das $dM_T$ lässt sich halt auch aus Kraft mal hebelarm bestimmen.


Jetzt tun wir das aber Integrieren, damit wir das "mini-Moment" auf den ganzen Querschnitt übertragen können.

Nun wollen wir das auch längst übertragen: das machen wir wie folgt:

![[IMG_E78ABEA2AD1C-1.jpeg]]

Wir teilen hier quasi das parallelogram auf, und machen ganz ganz viele Dreiecke nebeneinander, sodass wir so perfekt die Fläche über Längs integrieren können.

und joahh dann erhalten wir halt unser Schubfluss :)

der Schubfluss durch die höhe, liefert uns dann auch die Schubschpannung:

![[IMG_92AFE679D53D-1.jpeg]]

Das heißt also, je dünnwandiger der Querschnitt ist, desto höher ist dann die Schubspannung.


Wir haben jetzt aber noch ein phänomen, was sich "Gleitung" nennt. Schauen wir uns mal folgendes an:

![[IMG_5E4D41C474AE-1.jpeg]]

Hier ist wichtig zu wissen, dass das v nicht die Verschiebung in y-Richtung ist, sondern die Verschiebung entlang der Durchlaufkoordinate.

Durch den Tensor 2. Ordnung, können wir auch die Indizes der Gleitung tauschen ^^

berechnen wir uns Gamma doch mal :

![[IMG_6FFA865F5F7D-1.jpeg]]

Schauen wir uns nochmal den Allgemeinen Querschnitt nochmal an:

![[IMG_22336AE8476D-1.jpeg]]

Wir haben zunächst das r gezeichnet. Wir wissen, wenn wir den Querschnitt jetzt nach links drehen würden, dass sich der Punkt tangential (also senkrecht zum r)nach oben bewegen.

Wenn wir uns den grünen Pfeil jetzt in Komponenten aufteilen, haben wir hier das dv und der nach Oben zeigt und irgend ein anderer Vektor der dann den rechten Winkel bildet. 

Wir haben einen Winkel alpha, und das $rd\chi$ können wir uns mit dem tangenz berechnen, wenn wir uns das große grüne dreieck anschauen.

haben wir die Ankathete vom kleinen blauen Dreieick und die Hypotenuse, und können $cos(\alpha)$ aufstellen.

Wenn wir uns das rote Dreieck anschauen, hat es auch eine länge, diesmal $r_⊥$ aber den selben Winkel $\alpha$, wegen Balzanis lieblingssatz.

Somit könneen wir auch hier den cosinus bilden aber viel wichtiger, wir können die beiden cosinus dinger gleichsetzen und nach dv umstellen.

Wenn wir auf beiden seiten nun die Ableitung nach x machen, haben wir $\frac {dv}{dx}$ auf der linken seite und $r_⊥ \cdot \frac{d\chi}{dx}$ was ja die Ableitung von $d\chi$ wäre und das wäre ja dann $\theta$.

somit kommt dann $\frac {dv}{dx}$ =  $r_⊥ \cdot \theta$ heraus.

Das können wir dann in den Term für die Gleitung einsetzen und erhalten:
![[IMG_B1D57D5BAD36-1.jpeg]]

Wir stellen nach $r_⊥ \cdot \theta$ um, und Integrieren auf beiden Seiten, entlang der Durchlaufkoordinate.

![[IMG_43A2C303D2AC-1.jpeg|500]]

das Ende vom Glied muss 0 sein, weil wir keine Klaffung haben. Klaffung ist sowas wie eine Wölbung. Die punkte dürfen sich nicht verschieben bei einer Torsion... sie müssen übereinanderliegen.

Durch die Umfourmung nach $I_T$, haben wir sogesehen die 2. Bredsche Formel:

![[IMG_568DD9B64FCE-1.jpeg]]

## Dünnwandige offene Querschnitte

Schauen wir uns mal so einen Dünnwandigen offenen Querschnitt mal an:
![[IMG_CAF70A2CDA7B-1.jpeg]]

Wie sehen hier einen Linearhen Schubspannungsverlauf am Rand maximal ist.

wir haben auch einen unendlich kleinen Schubfluss dt(y):
![[IMG_A09FF4CED5CC-1.jpeg]]
-> Ist also die Schubspannung mal der Dicke eines Kastens, welches dy dick ist.

Das können wir jetzt in die Bredsche Formel, umgestellt nach $M_T$ einsetzen:
![[IMG_3980C4D669F9-1.jpeg]]

Bei Dünnwandigen Wänden ist man dann hingegangen und hat gaaanz viele Dünne schichten ineinander macht. 

Man ist per Definition dann hingegangen, und hat gesagt okay.. jedes dieser dünnen schichten hat dieselbe höhe.

Wir wollen ja wieder das $M_T$ alleine stehen haben, deswegen müssen wir auch hier wieder Integrieren.

![[IMG_B6AF82569AB0-1.jpeg]]

## Zusammengesetze offene Profile
Zusammengesetze UTIL- Profile macht man wie folgt :
![[IMG_AE1DD3E28134-1.jpeg]]

Hier ist die Maximale Schubspannung genau andersherum wie bei den geschlossenen Querschnitten, nämlich wie bei maximaler Profildicke ^^

## Nachweise berechnen

okok wir haben jetzt alle Werte herausgefunden. Aber..... wie bestimmen wir das jetzt ? Wir haben ja aus verschiedenen Gründen Schubspannungen, nämlich einmal aus Momenten und einmal aus Torsion. Was machen also dann ?

Man muss die Schubspannung infolge Querkraft und Schubspannung infolge Torsionsmoment zusammenaddieren, und kann so dann die Maximale Schubspannung berechnen.
![[IMG_D3AFFACEA613-1.jpeg]]