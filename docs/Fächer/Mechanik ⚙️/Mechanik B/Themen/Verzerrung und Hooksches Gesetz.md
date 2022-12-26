# 1. Verzerrung und Hooksches Gesetz

#### Spannung, Verzerrung(Dehnung) und das Stoffgesetz im Fachwerksstab:
**Schnittgrößen:**

![[IMG_F62EC5B534C6-1.jpeg]]

- Hier im Stab sind nur die Normalspannungen, weil ein Stab nur Zug und Druck in Normalrichtung (Querschnittsrichtung) aufnehmen kann.
- da kein n(x) wirkt, wäre das Integral und somit auch der Verlauf Konstant

**(Normal-)Spannungen:**

![[IMG_E9F78F0118B5-1.jpeg]]

- Spannung bedeutet “Kraft Pro Fläche”. G(x) errechnet sich ja dadurch, dass man N(x) (Normalspannung) geteilt durch A(x) (Fläche) berechnet.
- Hier sieht man auch, dass die Spannung auch Konstant ist, weil bei der Berechnung ein Konstanter Wert rauskam.

**Verschiebungen:**

![[IMG_88A3A618EFFC-1.jpeg]]

- Eine Verschiebung ist, wenn die sogenannten “Materiellen Punkte” ihre Lage verändern, aufgrund einer derart starken Belastung sodass es zu einer Belastung kommt.
- Die Verschiebung, wird mit einem Vektor $u(x)$ beschrieben.
- Das gestrichtelte Rechteck ist hat die Länge ℓ und es wirkt keine Normalkraft.
- Nun wirkt eine Kraft, heißt also das gestrichelte Rechteck wird auseinandergezogen oder zusammengedrückt. Hier wird es um ein ℓ gezogen bzw. links und rechts 1/2 ℓ.
- Die Länge der Formveränderung wird dann über die Funktion u(x) (in dem Fall      u(1/2 ℓ))
- Solange das Bauteil Homogen (überall selber Baustoffe) ist der Verlauf linear.

**Verzerrungen (Längendehnung):**

- ![[IMG_09802515890A-1.jpeg]]

- Die Verzerrung (Dehnung) ist das resultat aus der Verschiebung. Wichtig ist dabei zu beachten, dass sich durch die Verzerrung, der Mittelpunkt des Objekts ändert.
- Der Verzerrungsverlauf wird beschrieben mit einer Funktion $ε(x)$ beschrieben. Es ist die Ableitung der Verschiebung.
- Das Ingenieurdehnmaß beschreibt dann, um wieviel sich der ganze gedehnt hat.

**Stoffgesetz Elastizität:**

- ![[IMG_3D343EACF4AB-1.jpeg]]

- Hier sieht man ein Spannungs-Dehnungsdiagramm für alle Metalle. (linear elastisch)
- Man betrachtet nur das Elastische eines Bauteils, weil man nicht möchte, dass das Objekt in seiner Veränderten (plastischen) Form bleibt.
- **Stoffgesetz: $G = E*ε$** , das E ist das E-Modul und ist Materialabhängig. Je größer das E-Modul ist, desto steifer wird das Bauteil.
- **E-Modul: E = $\frac{σ}{ε}$**

#### Unterschied zwischen G - ε(Spannung - Dehnmaß) und (Kraft - Verschiebung):

1. **Stab mit Querschnitt $A_1$:**

![[IMG_7A29C97D1BBC-1.jpeg]]

- Hier sieht man zwei Graphen, der eine beschreibt das Verhältnis zwischen Kraft und Verschiebung und die andere zwischen Spannung und Dehnmaß.
- Aber was ist, wenn zwar das Material gleich bleibt aber sich der Querschnitt bleibt ?

2.  **Stab mit Querschnitt $A_2$:**

![[IMG_B1290288E7BB-1.jpeg]]

- Diesmal ist der Querschnitt größer, material ist gleich.
- Hier sieht man, dass diesmal der F - u Graph Steiler ist als davor, einfach weil man durch die Stärke des Stabs mit selben Kraft weniger ausrichten kann.
⇒ Man guckt sich Material und Struktur an.
- Das Spannungs - Dehnungs diagramm bleibt aber gleich, weil es das gleich Material ist.
⇒ Man guckt sich nur das Material an
    
#### Wofür braucht man das Stoffgesetz:
- stat. unbestimmte Systeme
- Gebrauchstauglichkeitsnachweis
- Verteilungen der Spannungen
- allgemeine 3D-Probleme

#### Allgemeiner Verzerrungszustand:
- Der allg. Verzerrungszustand ist ein Tensor 2. Stufe (wie bei Spannungen)
⇒ Verschiebungsgradient ^^

![[IMG_E17106B2BD5F-1.jpeg]]

- ε ist immer symmetrisch
- Nun unterteilt man zwischen den “Normalen-Komponenten”, und “Neben-Komponenten”.

**Normalenkomponenten (Verzerrung):**

![[IMG_879E6C317FC6-1.jpeg]]

↳ Leichtes muster was man sich merken kann ^^

![[IMG_6E8F7D9436F2-1.jpeg|300]]

**Nebenkomponenten(Scherung):**

![[IMG_CA080AB61F96-1.jpeg]]

- bei den Nebendiagonalen muss man ein wenig vorsichtig sein ^^
- auf den Verschiebungsgradientenmatrix achten !!, erst (Zeile , Spalte) und dann durch das Transponierte (Spalte , Zeile).
- die Klammer wird ersetzt durch ein γ ersetzt

![[IMG_5BFC1CEF2725-1.jpeg]]


↳ Genau wie bei der Spannung, hat man auch “Hauptzerrungen”, “Schubzerrungen” und Morscher Kreis ^^
    
**Verallgemeinetes Elastitätsgesetz:**

- Diesmal hat man einen Tensor 4. Ordnung ⇒ sikis
- Man kann das ganze aber auch invertieren, dementsprechend ist es Analog 😊

![[IMG_F0F7BC3E0B2D-1.jpeg]]

Beispielaufgabe:

![[IMG_2CE3B33D88A8-1.jpeg]]
        
**Hookisches Gesetz mit Temparatureinwirkungen:**
- Neben Spannungen kann auch ein Wärmeeinfluss zu Dehnungen im Bauteil führen.
- Um dies formal zu erfassen, gilt es das Hookesche Gesetz um einen weiteren (thermischen) Term zu ergänzen.
    
![[IMG_BF780407FA07-1.jpeg]]

- Die Spannung ändert sich nie, die Verformung aber wohl.
- Erst bei Behinderung der Verzerrung, z.B bei entsprechende Lagerung (z.B Feste einspannug) entstehen Spannungen (Risse, Dehnfugen).