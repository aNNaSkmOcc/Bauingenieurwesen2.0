# 2. Biege-normal-spannung

^ecf15f

### <mark style="background: #FFB8EBA6;">**Querbalken (einfache Biegung)**</mark> 
- Einfache Biegung: Belastung und Geometrie des Bauteils sind so, dass entweder v(x) (Verschiebung in y-Richtung) oder w(x) (verschiebung in z-Richtung) auftreten.
- Der Querbalken nimmt Schubspannungen auf.

- ![[IMG_6BBC98AB491E-1.jpeg]]

- u(x) ⇒ verschiebung in x-Richtung
- v(x) ⇒ verschiebung in y-Richtung
- w(x) ⇒ verschiebung in z-Richtung

- ![[IMG_6BBC98AB491E-1_2.jpeg]]

- **Balken oben:**
	- oben bei N ≠ 0, Q = 0, M = 0 haben wir den Fall, dass wir ein Fachwerksstab haben.
	- dort haben wir entweder nur Zug oder Druck.
	- Dort berechnet man die Spannung einfach $G_x = \frac{N}{A}$ (siehe 1. Semester)
- **Balken unten:**
	- Diesmal haben wir eine Querbelsatung und Moment, welches auf den gesamten Balken wirkt.
	- Wenn der Balken sich nach unten biegt, wirkt oben Druck (Balken wird kürzer) und unten Zug (Balken wird länger)
	- Wie man das berechnet weiß man hier noch nicht.

### <mark style="background: #FFB8EBA6;">**Vorraussetzungen, um Biegungen per Hand zu berechnen**</mark> 
1. Prismatischer Stab mit gerade Balkenachse → Homogene Balken
2. Dünner Stab: $\frac{L}{h} ≥ 10$
3. Querschnitt darf nicht ausbeulen
4. Sehr kleine Verschiebungen ⇒ Darf also nur leicht durchbiegen, sodass die Theorie passt
5. Material muss homogen sein, gleiche struktur haben also gleich beslastbar sein.

- => Wenn eine Regel gebrochen wird, muss man auf Software zugreifen.

---
    
### <mark style="background: #FFB8EBA6;">Herleitung der ganzen Formeln für Biegespannung berechnen (nochmal anschauen)</mark> 

##### **Annahme: Alle Punkte eines Querschnitts, erfahren die selbe Biegung**  

- ![[IMG_CAA207ACB2F0-1 1.jpeg]]


Das geht nur, weil der Balken sich nur minimal Biegten tut.


- oben links sieht man einen Schnitt aus einem Balken
- der Dicke senkrechte Strich ist der Querschnitt.
- Wenn man den Balken jetzt biegt sieht man, dass der Querschnitt sich logischerweise verschiebt und die Punkte im schrägen Querschnitt auch alle untereinander sind.
⇒ $w_1 = w_2 = w_3$

---
		

##### Annahme: Querschnitte bleiben gerade, verdrehen sich aber. (1. Bernoulli Hypothese)**  
        
- ![[IMG_1BF12AE1D4FD-1.jpeg]]

- die verschiebungen der Punkte auf dem Querschnitt werden mit der Funktion u(x,z) beschrieben, weil die Punkte in x Richtung geschoben werden, und Querschnitt parallel zur z-Achse ist.
- Man rechnet den Winkel mit dem Tangenz: u(x,z) ist die Gegengathete und z ist die ankathete, das ist ungefähr β groß
- Wenn man jetzt nach u(x,z) auflöst, erhält man dise -β(x). Das minus kommt dadurch zustande, dass das u(x,z) positiv und z aber negativ ist.
- die Dehnung berechnet man, indem man u(x,z) also -β(x) nach x ableitet (Siehe formel für Verzerrungen Vorlesung 1).
- Die Gleitung berechnet man ebenfalls nach der Formel aus Vorlesung 1, das -β(x) bleibt aber unverändert, da man eine Funktion abhängig von x nach z ableitet und da passiert garnix ^^
  

##### Annahme: Normale bleibt Normale (2. Bernoulli - Hypothese)  ^63736b
        
- ![[IMG_56E3B6D24872-1.jpeg]]

- Der Querschnitt ist logischerweise senkrecht (90°) zur x Achse. Wenn der Balken sich aber verbiegt (minimal natürlich), soll die Mittellinie
- Hier haben wir 2 Winkel, einmal eine die die drehung des Querschnitts beschreibt und eine die Verdrehung der x-Achse.
- rechts die Funktion erklärt uns, dass die Steigung und somit auch den Winkel von Alpha der Funktion w(x). Sie heißt so, weil der Balken sich in w Richtung bewegt.
- Damit die normale gleich Normale bleibt, müssen sich der Querschnitt und die x Achse aka. der Balken also gleichzeitig bewegen.
- Für den Bernoulli-Balken müssen Gleitungen vernachlässigt werden.

- ![[IMG_2C72A0E4266B-1.jpeg]]

- Hier wird die Spannung weggelassen und die Dehnung mit dem davor errechnet aus (2) ersetzt.	

### <mark style="background: #FFB8EBA6;">**Berechnung von $σ_x$ aus Schnittgrößen**</mark> 
- Bei den Schnittgrößen, haben wir ja immer das Biegemoment des Bauteils berechnet. Das Biegemoment ist aber lediglich der Querschnitt der verteilten Spannung. Also gilt:
$\int \limits_{A}^{} \sigma_x(x,z) \ \cdot \ z$ , Man nimmt $\sigma_x$ mal z, weil man das Moment, Kraft mal Hebelarm berechnet. Das Integral dient lediglich nur dazu das Moment auf die Fläche zu verteilen.

- ![[IMG_10D601E4C313-1.jpeg]]

- Nun kann man das $\sigma_x(x,z)$ mit dem vorhin berechneten erstezen und erhalten:

- ![[IMG_E712D3AC8C67-1.jpeg]]

- Das Integral ergibt hier das “Flächenträgheitsmoment $I$”, sodass die Formel nun lautet:

- ![[IMG_072E83C17230-1.jpeg]]

- Das $E \cdot I$nennt man die “Biegesteifigkeit”
- Das $\beta'(x)$ ist dann die “Elastische Krümmung $\kappa$”, kann sein, dass man diese auch berechnen muss ^^
- Nun kann man das $\beta’(x)$ ersetzen mit $-\frac{M_y}{E \cdot I_y}$ sodass das $\sigma_x$ dann lautet:

- ![[IMG_04535A4732B7-1.jpeg]]

- Das E-Modul und das - kürzen sich weg, sodass nur noch $\sigma_x = \frac{M_y}{I_y} \cdot z$ bleibt.
- $M_y$ ist das Biegemoment um die y-Achse
- $I_y$ ist das Flächenträgheitsmoment
- z ist der Abstand vom Querschnittschwerpunkt zum Rand
- W ist das Wiederstandsmoment
- Hier aber ist das die Formel, für die Allgemeine Biegespannung.
- Um die BiegeNormalspannung zu bekommen, müssen wir einfach die Normalspannung des Balkens hinzufügen sodass die endgültige Formel aussieht wie:

- ![[IMG_541D4430A8EE-1.jpeg]]

- ![[IMG_76C3A7CED710-1.jpeg]]

- ![[IMG_C4C28EC0302A-1.jpeg]]

- Dies sähe dann so skizziert aus

- ![[IMG_362B897377A9-1.jpeg]]

- nun wüssten wir z.B wo wir überall Bewehrung legen müssten ^^

---
        
### <mark style="background: #FFB8EBA6;">**Neutrale Faser**</mark> 
- Die Neutrale Faser, stelle im Querschnitt, wo keine Spannung da ist
⇒ $\sigma_x \stackrel{!}{=} 0$
- Man setzt die Formel für die Biegenormalspannung gleich 0 und löst nach z auf, sodass man weiß, an welcher Stelle im Querschnitt die neutrale Faser ist.

### <mark style="background: #FFB8EBA6;">**Schiefe Biegung**</mark> 
- Nun belasten wir den Balken nicht von einer Richtung, sondern von mehreren.
- Nun haben wir auch nicht nur eine Achse wo sich das Bauteil hinbiegt, sondern 2. Somit sieht die Gleichung folgendermaßen aus:

- ![[IMG_3AA10E7181AD-1.jpeg]]

- <mark style="background: #FFB8EBA6;">Rezept für die berechnung mit schiefen Biegungen:</mark> 
	1. Bestimmung Hauptachsen
	2. Zerlegung in $q$ in $q_z$ und $q_y$ ⇒ Berechnung der Biegemomente $M_y, M_z$
	3. Berechnung von $\sigma_x$
	4. Resultierende Durchbiegung
		
		
		