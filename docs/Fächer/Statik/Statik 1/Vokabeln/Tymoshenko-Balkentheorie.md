Die Tymoshenko-Balkentheorie, trägt den Namen zu ehren des des Ingenieurs [Stepan Tymoshenko](https://de.wikipedia.org/wiki/Stepan_Tymoschenko) der uns Ingenieuren eine ganz andere Betrachtungsweise über Balken gegeben hat.

Stepan Tymoshenko sagt, dass wenn sich ein Balken verbiegt, der Querschnitt des Balken **nicht** mehr Ortogonal zur Stabachse ist und einen eigenen Drehwinkel einnimmt.

![[TimoshenkoBeam.svg.png]]

so sieht der Timoshenko-Balken dann aus. Der Querschnitt des Balkens, hat also seinen Eigenen Drehwinkel.

Ein Sonderfall der Tymoshenko-Balkentheorie, wäre die sogenannte [[Bernoulli-Balkentheorie]], wo der Querschnitt des Balkens, bei der Verdrehung **immer** Senkrecht zum Querschnitt ist. Wir können einfach hergehen, und die Verdrehung 0 setzen... zack haben wir dann die Bernoulli-Theorie.

Wichtig ist, dass die <mark style="background: #FFB8EBA6;">Verdrehung gegen die Uhr positiv</mark> ist.

### Biegelinien kommen zurück ?!?!

Schauen wir uns das noch einmal konkreter an:

Wir möchten ja, aus den Belastungen, die Verschiebungen und Biegungen errechnen.

Dazu müssen wir ja wie wir gelernt haben, erst über die Schnittgrößen, dann über die inneren Weggrößen gehen, um dann die äußeren Weggrößen herausfinden zu können.

Das wäre jetzt ein Overkill, wenn man das die ganze Zeit hätte machen müssen :D

Deswegen... könnte man diesen Weg direkt gehen ?  

![[IMG_366A1D974F2C-1.jpeg]]

Ja kann man :d 

Sei schonmal vorrausgesagt, dass die scheiß [[Flächenträgheitsmoment und Biegelinie#^4d9e1b|Biegelinien]] wiederkommen.

!!ABER ACHTUNG!!

Die Differentialgleichungen und die Randwerte, sind bei der Tymoshenko-Theorie gaaaaanz anders :D

schauen wir uns das einmal an:

### Differentialgleichungen des Tymoshenko-Balkens:

Schauen wir uns an, welche Parameter wir alles haben:

![[IMG_7CAF8C8E7FDC-1.jpeg]]

WIr haben aus den verschiedenen Beziehungen unsere Parameter. Wir wir sehen, hängt alles irgendwie voneinander ab :D

Deswegen gehen wir jetzt her, und Setzen von rechts nach Links alles ein :D

mit viel rechnerei, was der Prof uns auch erspart hat, erhalten wir folgende Diffgleichungen:

![[IMG_42F72CC18065-1.jpeg]]

Alternativ, haben wir noch eine andere Notation, falls die Parameter da alle konstant sind :D


Soo :D um jetzt mit DGL rechnen zu können, brauchen wir natürlich Randwerte :D

schauen wir uns die mal an:

![[IMG_140BCBC59062-1.jpeg]] 

schauen wir uns den Kragarm links an,

rechts ist ja klar, dass sich der Balken biegt, und somit die neigung des Querschnittes nicht 0 ist.

links allerdings, haben wir natürlich keine Biegung, weil wir ja eine Feste einspannung haben.

ABER ACHTUNG

jetzt ist die Verdrehung auch 0.

In [[Mechanik B ⚙️]] haben wir gelernt, dass die Ableitung dann 0 ist :D aber ne

Wir dürfen nicht vergessen, dass wir hier immernoch in der Tymoshenko Theorie sind :D

### Beispiel 
Der Prof hat uns auch im Speedrun ein Beispiel vorgerechnet, und ist zu folgendem Ergebnis:

![[IMG_D71B8CAE063E-1.jpeg]]

Dieses $\beta$ schauen wir mal lieber genauer an!

### Berückstichtung der Schubdeformationen
Schauen wir uns diese Schubdeformation doch einmal an:
![[IMG_3BDA635812B0-1.jpeg]]

Wenn dieser Schubfaktor 0 ist, dann haben wir einen Bernoulli-Balken.

Wenn also das $\beta < 0.05$ , ist es so klein, dass wir es eigl 0 annehmen können.


ist es allerdings schon 0.1, dann müssen wir es wieder Betrachten.

Aber keine Angst, in 90% der fälle, ist es soo gering, dass wir sie eigl vernahclässigen können.



