# Verbundträger

Hier geht um ein Inhomogenes Bauteil was wo wir die Biegenormalspannungen berechnen möchten.

Die allgemeine Formel lautet ja:

$$\sigma (y,z) = \frac{N}{A} + \frac{M}{I_y}\cdot z$$

- Wir hangeln uns jetzt durch diesen bereich der die Spannung eines Stabes beschreibt ($\frac{N}{A}$) und dann für ($\frac{M}{I_y}\cdot z$)

	

---

#### Zug und Druckstäbe

WIchtig bei den Zug und Druckstäben ist, dass wir keine Krümmung haben, sprich, wir haben nur eine Dehnung in Querschnittsrichtung.

Außerdem ist dadurch, dass wir keine Krümmung haben, die Dehnung also das $\epsilon$ Kosntant.

- betrachten wir mal folgenden Querschnitt:

![[IMG_4FB5149273F7-1.jpeg|300]]

Wie ist denn die Dehnung? Wir haben vorhing gesagt, dass die Dehnung Kosntant sei. der Dehnungsverlauf sähe dann in etwa so aus:

![[Bildschirmfoto 2022-04-29 um 09.57.25.png|175]]

Eigentlich recht verständlich :)

Aber wie würde denn der Spannungs verlauf aussehen ? schauen wir uns dass mal an:


![[Bildschirmfoto 2022-04-29 um 10.05.30.png|175]] 

Hier ist der Verlauf nur abschnittsweise Senkrecht. Aber wieso ist das so?

Klar! wir haben ja einen inhomogenen Querschnitt, sodass der Spannungsverlauf garnicht senkrecht sein kann. Der Prof hat einfach mal gesagt, dass der Obere Querschnitt weicher sei. klar, wir brauchen weniger Kraft und somit auch weniger Spannung, um diese Teilfläche zu verformen als die untere Teilfläche, welche ja steifer und somit auch schwerer zu verformen ist.

Klar mit gesundem Menschenverstand können wir den Spannungs und den Dehnungsverlauf zeichnen.... aber wir als Ingenieure müssen diesen verlauf den wir gezeichnet haben ja auch als Zahlenwert angeben und unsere Rechnungen ja auch nachweisen diesdas. 

Also.. wie berechnen wir hier denn den Spannungsverlauf? Na mit dem ganz einfachen Stoffgesetz:

$$ \sigma = E \cdot \epsilon $$

Das Problem ist jetzt aber, dass wir das Epsilon nicht kennen haha :) Tja pechgehabt geht nicht nh? klar geht das nur wie?

Okay okay... Was steht mir der Spannung denn in verbindung? richtööög die Normalkraft... schauen wir uns mal die Normalkraft an:

![[Bildschirmfoto 2022-04-29 um 10.12.31.png]]

Okay was hat der Prof hier gemacht? gehen wir das mal schritt für schritt durch Los gehts #martinTU 

1. Wieso das Integral? Ja ganz einfach... was ist denn die Normalkraft eigentlich ? Wir haben ja gesagt, die Normalkraft ist die Resultieeeerende der Normalspannung, also der Spannung die in x-Richtung über die gesamte Querschnittsfläche geht. Und was ist die Resultierende einer Flächenlast? der Flächeninhalt!! Also... die Normalkraft ist einfach die Spannung über die ganze Querschnittsfläche verteilt. Jetzt haben wir aber Sigma 1 und Sigma 2, weil wir hier auch zwei unterschiedliche Teilquerschnitte mit unterschiedlichen Spannungen haben.

2. Eine Zeile drunter, hat er dann einfach da ein "A" drangehängt, weil wir ja nach "A" integrieren... zur hilfe kann man sich das als ein x vorstellen es ist aber die Fläche.
3. Eine zeile wieder drunter, hat der Prof das Stoffgesetz angewendet und das Sigma mit dem <mark style="background: #FFB8EBA6;">$E \cdot \epsilon$</mark> erstezt.

4. Da wir ein konstante Dehnung haben, also das Epsilon überall gleich ist, kann man das Epsilon einfach Ausklammern und wir erhalten dann Die Normalkraft.
5. Außerdem, hat man die Dehnsteifigkeiten "EA" der einzelnen Teilflächen auch zusammgefasst als $\overline {EA}$.

6. Wir wollen aber das Epsilon haben, deswegen bringen wir $\overline {EA}$ auf die andere Seite und erhalten dann die Dehnung:
![[Bildschirmfoto 2022-04-29 um 10.35.17.png]]

- Mit der Formel bekommen wir eigentlich zwei nütliche Dinge:

![[Bildschirmfoto 2022-04-29 um 10.39.58.png]]

- Nun danach hat der Prof diese "Wichtung eingeführt:"

![[Bildschirmfoto 2022-04-29 um 10.52.35.png]]

Die Wichtung lautete also:
$$n_i = \frac{E_i}{E_1}$$

das obere $E_i$, beschreibt das E-Modul der einzelnen Schichten, und das E_1 das E-Modul der ersten Schicht. Wieso weshalb warum, weiß keine sau haha

Man löst das dann aber nach $E_i$ um und Kann damit dann weiterarbeiten.

1. Man kann das jetzt nun in die Dehnsteifigkeiten der einzelnen Flächen einsetzen  $\overline {EA}$. 

2. Dann hat der Prof das $E_1$ wieder ausgeklammert und das was in der Klammer noch steht, wird zusammengefasst, als die idealisierte Querschnittsfläche.

3. Daraus folgt dann, dass was in der letzten Zeile steht.

4. Das kann man dann in die Spannungsformel einsetzen:

![[Bildschirmfoto 2022-04-29 um 12.38.10.png]]

Okay... nun haben wir eine Formel, womit wir die Spannung und somit auch die Normalkraft berechnen können.... Wir wissen aber nicht wo die Normalkraft bei inhomogenen Querschnitten angreift :(

schauen wir uns mal diese Ansicht an:

![[Bildschirmfoto 2022-04-29 um 12.51.52.png|300]]

wir haben uns einen ideellen Schwerpunkt gesetzt, wo die Resultierende der Spannung also die Normalkraft wirken könnte. Dies ist aber nicht der geometrische Schwerpunkt, denn der wäre bei einem Rechteck ja immer in der Mitte.

Nun Splitten wir die Normalkraft auf:

![[Bildschirmfoto 2022-04-29 um 13.00.41.png|300]]

Von vorne geblickt, sieht der Querschnitt mit dem geometrischen und ideellen Schwerpunkt dann so aus:

![[Bildschirmfoto 2022-04-29 um 13.03.43.png|300]]

jetzt gilt es nur noch ein Momentengleichgewicht zu erstellen... wir haben ja vorhin gesagt, dass wir die Normalkraft splitten möchten. Somit würde das Momentengleichgewicht um den geometrischen Schwerpunkt "S" so aussehen:

![[Bildschirmfoto 2022-04-29 um 13.09.59.png]]

#### Reiner Biegebalken

den Normalspannungsteil der Biegenormalspannungsformel haben wir jetzt abgehakt. Nun kommt der andere Biegespannungsteil.

Wir betrachten zunächst mal nur die Biegemomente um den ideellen Schwerpunkt 

wir treffen hier die gleichen Annahmen wir beim homogenen Biegebalken auch.. also Normale bleibt normale

alsoo Los gehts #martinTU 

schauen wir uns wieder mal den Querschnitt an:

![[Bildschirmfoto 2022-04-29 um 16.05.12.png]]

1. Wir drehen hier um den ideellen Schwerpunkt. Durch die Bernoulli Annahme "Normale bleibt Normale", hat sich der Querschnitt einfach die Dehnung ist. 

2. Streng genommen, verschieben wie die Puntkte einfach. Die Funktion die wir wird vom Buchstaben u (wegen x) beschrieben, außerdem schieben wir in x richtung und nach unten zeigt das $\overline z$ deswegen lautet die Funktion für die verschiebung $u(x, \overline z)$

4. Die Dehnung, ist die Ableitung von der verschiebung. Okay wir haben zwar einen linearen verschiebungsverlauf und die Ableitung einer linearen Funktion ist ja eine Konstante... aber ka :=) ist halt so meinte der.

1. Der Spannungsverlauf ist auch hier wieder klar. Wir haben eine lineare Funktion die den Spannungsverlauf beschreibt, allerdings ist auch hier wieder versetzt linear aufgrund der Materialänderungen. Nehmen wir an, dass die obere jetzt ein wenig steifer ist als unten.... Man muss für oben also mehr Kraft aufwenden als unten.

Zeichnen ist wieder easy aber wir wollen das auch berechnen können ^^

![[Bildschirmfoto 2022-04-29 um 17.04.27.png|550]]

5. Hier leiten wir u einfach ab, um die Drehung zu bekommen :)

6. Jetzt können wir hier die Dehnung wieder für unser Hooksches Gesetz ($\sigma = E \cdot \epsilon$) benutzen

Dann gehts also so weiter:

![[Bildschirmfoto 2022-04-29 um 17.17.05.png|500]]

Okay Was hat der Prof hier jetzt schon wieder gemacht ?

Eigentlich muss man nur verstehen, wieso er integriert hat, und was er integriert hat. 

1. Der Prof hat das ähnlich wie bei der Normalspannung oben, das quasi für die einzelnen Teilflächen aufgeteilt, und hat ein Momentengleichgewicht um die x-Achse aufgestellt.
2. Dann hat er wieder eingesetzt diesdas

3. Somit ist er auf Trägheitsmomente gekommen, und hat quasi das $E \cdot I$ für die beiden Querschnitte als $\overline {EI}$ (Biegesteifigkeit des Verbundbalkens zusammengefasst.)

also bekommen wir raus:

![[Bildschirmfoto 2022-04-29 um 17.45.39.png]]

Das können wir also jetzt wieder benutzen um die Spannung auszurechnen und erhalten:

![[Bildschirmfoto 2022-04-29 um 18.03.46.png]]

![[Bildschirmfoto 2022-04-29 um 18.06.23.png]]