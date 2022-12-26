# 10. Prinzip der Virtuellen Kräfte

### 1. Sätze von Betti und Maxwell

Auch hier schauen wir wieder folgende Vorraussetzungen an:

![[IMG_D2CA12E2648E-1.jpeg|400]]

konservative Lasten bedeutet, dass die Kraft sich bei berührungen nicht verändern :D

##### Superpositionsgesetz der linearen Elastostatik

Dadurch, dass wir immer lineare Zusammenhänge haben, können wir die Kräfte einfach zusammenaddieren hihi

Schauen wir uns mal folgende Lastfälle an:

![[IMG_1AE3EA401085-1.jpeg]]

Das ist Quasi der Lastfall 1: "Erst fügen wir eine Kraft $F_i$ am Angriffspunkt i ein und danach eine weitere Kraft $F_k$"

Klar wenn diese Kraft wirkt, dann durchlebt sie eine verschiebung $u_i$. Diese Verschiebung $u_i$ können wir jetzt noch in Komponenten Aufteilen: eine vertikale Komponente in Richtung $F_i$ die wir $f_{ii}$ und eine horizontale Komponente. Die horizontale Komponente kann man aber Vernachlässigen, weil diese eh 0 ist. 

Die indizierung von dem $f_{ii}$ geht wie folgt: 
- Das erste i wegen dem Angriffpunkt i
- Das zweiter i wegen dem Indize von $F_i$

Jetzt wollen wir mal anfangen zu rechnen. Wir berechnen zuerst mal die Äußere Arbeit also das W:

Erinnerung: die Äußere Arbeit lässt folgendermaßen berechnen: $W = \frac{1}{2} \cdot \text{Kraft} \cdot \text{verschiebung u}$

Machen wir hier mal:

![[IMG_DAA3D9A2C465-1.jpeg|350]]

Wir haben u ja in Komponenten unterteilt. Die vertikale Komponente ist ja $f_{ii}$ und die horizontale ist 0. deswegen ersetzen wir u nur mit $f_{ii}$

Jetzt führen wir eine sogenannte Einführungszahl "$\delta$" ein. $\delta$ gibt den Einfluss von F auf die Verschiebung an.

Somit können wir sagen:
![[IMG_520A256F5C34-1.jpeg]]

Das können wir jetzt wiederrum in die Gleichung für W einsetzen, sodass gilt:

![[IMG_5E0B73360605-1.jpeg]]

SOOOO jetzt führen die zweite Kraft $F_k$ ein.

![[IMG_E17C97774948-1.jpeg|450]]

klar.... weil die Kraft $F_k$ am Punkt k auch eine verschiebung ohne horizontal komponente hat, haben wir auch hier eine Verschiebung $f_{kk}$. Allerdings müssen wir beachten, dass wir bei der Kraft $F_i$ jetzt durch die Kraft $F_k$ auch eine zusätzliche verschiebung haben. Diese indiziert sich nach dem Muster mit $f_{ik}$

Klar haben wir außerdem noch zusätzliche Einflusszahlen:
![[IMG_95E37DCEAA22-1.jpeg]]

Die Arbeit ("W") mit zwei gleichen Indizierungen nennen wir "aktive Arbeit", während die Arbeit gemische Indizes hat. Schauen wir anhand eine verbildlichung mal die Berechnung der Arbeit mal an:

![[IMG_BB7CF8B18B0B-1.jpeg]]

schauen wir uns mal eine Hooksche Feder und das dazugehörige Dehnungsdiagramm an. Wenn wir Die Kraft $F_1$ wirken, dann verschiebt es sich um $f_1$. Wenn wir jetzt noch zusätzlich $F_2$ wirken, verschiebt es sich nochmal um $f_2$, sodass wir einen Linearen Verlauf haben.

Es entsteht oben und unten 2 kleine Dreicke (Die aktiven Arbeiten -> 2 mal gleicher indize) also $W_{ii}$ und $W_{kk}$ und in der Mitte ein Rechteck (Die passiven Arbeiten -> unterschiedliche Indizes) also $W_{ik}$

Wir wollen ja den gesamten Flächeninhalt der Fläche unterhalb des Graphen haben, deswegen müssten wir ja die einzelnen Flächeninhalte berechnen. Für die aktiven Arbeiten, rechnen wir also mit der Flächeninhaltsformel des Dreiecks und für die passive Arbeit, die Flächeninhaltsformel für ein Rechteck :D

Das können wir dann auch jetzt auf unsere Aufgabe übertragen:

![[IMG_99B9C0B5AAD2-1.jpeg]]

Jetzt können wir uns den zweiten Lastfall anschauen, nämlich genau das umgekehrte.... im Endeffekt tauschen sich nur die Indizes sodass wir haben:

![[IMG_0D1240772805-1.jpeg]]

Jetzt sagt uns das Superpositionsprinzip, dass die Arbeit von dem ersten Lastfall gleich der Arbeit von dem zweiten Lastfall sein muss. Also haben wir folgenden fall :

![[IMG_97312112D97D-1.jpeg]]

Weil $W_{ik}$ und $W_{ki}$ auf beiden seiten vorkommen, können wir diese kürzen, sodass wir folgendes haben:


![[IMG_554335AD7FAF-1.jpeg]]

Außerdem muss gelten:

![[IMG_C248919A8CF6-1.jpeg]]

Jetzt haben wir das ganze für Kräfte und Verschiebungen gemacht..... wieso denn nicht auch für Momente und verbiegungen? Da gehts nämlich ziemlich gleich.

Man stellt das nur etwas anders da:

![[IMG_6146481230A3-1.jpeg]]

$q_{ik}$ und $Q_i$ können platzhalter für unterschiedliche Dinge sein. Deswegen muss man das immer alles auf eine Einheit transformieren.



##### 1. Satz von Castigliano

![[IMG_59406BB7FBD8-1.jpeg]]

Nun haben wir das W und müssen es einfach nach Q ableiten.

![[IMG_329D5583837D-1.jpeg]]

Wir leiten nicht nach irgendwas ab, sondern wir leiten nach $Q_j$ ab

Hier ziehen wir die beiden Summen und die $\frac{1}{2}$ raus. Die Ableitung eines Produkts macht man mit der Produktregel. Da wir zwei unterschiedliche indizes haben, müssen wir hier eine Fallunterscheidung machen:

Wenn nämlich diese gleich sind, dann ist die Ableitung 1. Andernfalls wäre die Ableitung gleich 0.

Wir nehmen für den indizes an, dass bei der Ableitung von $Q_i$, dass i = j ist und bei der Ableitung von $Q_k$ an, dass k = j ist. Also kommt raus:

![[IMG_1EA6BCAFE6BD-1.jpeg]]

bei der einen Seite können wir die Summe mit i wegkürzen weil auf der Seite nichts von i abhängt und das gleiche dann bei dem k.

Dann im nächsten Schritt, kann man eigentlich auf der rechten Seite, alle i mit k ersetzen, weil es nachher bei der umschreibung der Summe, ohnehin keine Buchstaben mehr geben würde.

im letzen schritt, können wir das $\delta_{jk}$ noch umschreiben als $\frac{q_{jk}}{Q_k}$, weswegen sich das Qk dann auch wegkürzt. Was übrig bleibt, ist das $q_j$.

Laut dem Arbeitsatz der Elastostatik haben wir gesagt, dass [[Arbeitssatz der Elastostatik#^b78c1d|die äußere Arbeit auch gleich dem Potenzial ist]].

somit ergibt sich:

![[IMG_27094713138E-1.jpeg]]

Man hat das W jetzt durch das \pi ersetzt, weil \pi nur von Schnittgrößen abhängt und auch einfach ist, da es keien verschiebungen hat.

Für Biegemoment-dominierte Probleme, sieht das dann wie folgt aus:

![[IMG_F2BCEE092F02-1.jpeg]]

Wenn es Biegemoment-dominiert ist, können wir die Restlichen Schnittgrößen vernachlässigen .
($Q_z$, N = 0).
Demensprechend, sind die Anteile von diesen Schnittgrößen aus der Superposition ebenfalls 0.

Das Ableiten macht man dann mit der Kettenregel.

### Prinzip der Virtuellen Kräfte
okokko das ist jetzt einfach Analog zum [[Arbeitssatz der Statik#^c052f1|Prinzip der virtuellen Arbeit]]. Damit haben wir quasi mit verschiebungen, Kräfte bestimmt. 

Jetzt mit dem **Prinzip der Virtuellen Kräfte**, können wir jetzt genau umgekehrt mit eingeführten Kräften, verschiebungen berechnen .

betrachten wir folgendes System:

![[IMG_016DDE0E2500-1.jpeg]]

Mit dem 1. Satz von Castigliano, könnten wir jetzt die verschiebung an dieser Stelle berechnen. Aber was ist, wenn wir verschiebungen an einer beliebigen Stelle berechnen wollen ?

Dann geht das mit dem Satz von Castigliano nicht mehr :(

Die Grundidee von Prinzip der Virtuellen Kräfte ist, dass man eine Kraft einfügt... Dann machen wir das doch mal:

![[IMG_9C1A3E77B643-1.jpeg]]

Erinnerung: Wir wollen die verschiebung an der Stelle i berechnen wollen. Also radieren wir alle Kräfte weg und führen da mal eine Kraft ein. Das ist die Kraft $\bar{Q_i}$ mit der Einheitslosen $\bar{1}$

An beiden Systemen haben wir natürlich ein Biegemoment. Einmal das normale $M$ für die Realkräfte und das Biegemoment $\bar{M}$ für die virtuelle Kraft die wir eingeführt haben.

Außerdem können wir jetzt hingehen und erstmal die Arbeitssätze aufstellen sprich: aktive Arbeit und für die Passive Arbeit:

![[IMG_9085296FACE0-1.jpeg]]

Das $\bar{Q_i}$ können wir dann immer mit der einheitslosen $\bar{1}$ ersetzen. 

Cool :DDDD

Jetzt für die herleitung nehme man an, dass man ein Biegemoment dominiertes Problem hat. (bedeutet, dass man alle anderen Schnittgrößen weglassen kann ^^)

Dann berechnen wir das Potenzial mit der Superposition:

![[IMG_54C1836D8491-1.jpeg]]

Das $M^2$ sehen, ist quasi das Gesamte Biegemomentenverlauf. Das heißt, dass ist der Momentenverlauf von der Virtuellen Kraft + der Momentenverlauf von den Realkräften.

Dann haben wir ja wieder den Arbeitssatz der Elastostatik :DD und können unsere Superposition, mit unserer Arbeit Gleichsetzen :DD.

Außerdem lösen wir oben die Binomische Formeln auf

Somit erhalten wir:

![[IMG_A7D3972ECB32-1.jpeg]]

Dann gehen wir hin, und trennen Die Integrale :DD

![[IMG_4316B84436B8-1.jpeg]]

Jetzt können wir einige Dinge kürzen weil sie gleich sind sodass übrig bleibt:

![[IMG_B9AD52BAF392-1.jpeg]]

Jetzt kann man natürlich auch hingehen und das verallgemeinern sodass wir folgendes haben:

![[IMG_3F32A4101EEF-1.jpeg]]

UND FERTIG :DDD

##### Allgemeine Vorgehensweise

![[IMG_705630DBBEBC-1.jpeg]]

### Wiederholung
Ziemlich lange Herleitung diesdas :D In den mechanik Vorlesungen war das auch ziemlich anstregend zuzuhören.

Wir haben ja gelernt, dass Arbeit = Weg mal Kraft ist.

Das Prinzip der Virtuellen Kräfte ist jetzt nichts weiteres, als eine **reale Verschiebung** mal eine **virtuelle Kraft**.

es gibt ein paar Bedingungen, die erfüllt werden:

![[IMG_B2941C3E3628-1.jpeg]]

das PVK, gibts natürlich sowohl für den Tymoshenko, als auch den Bernoulli-Balken.

