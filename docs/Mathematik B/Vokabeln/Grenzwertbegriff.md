# Der Grenzwertbegriff
- Was ist ein Grenzwert ?
    - Zahlenwert, nach dem eine Folge reeller Zahlen hinstrebt ⇒ Limes
    - Uns interessiert, wie sich die Funktionswerte Verhalten, dies bekommen wir hin wenn wir mit einer Folge gaanz nah drangehen.
    - Wenn ein eindeutiger Zahlenwert beim Limes rauskommt, hat es einen Grenzwert sonst nicht
- Die Regel von L’Hospital
    - Die Regel von L’Hospital ist ein sehr guuutees Werkzeug, wenn wir bei der Grenzwertberechnung folgende fälle betrachten müssen:
    - <mark style="background: #FFB8EBA6;">$\lim \frac{0}{0}$</mark> oder <mark style="background: #FFB8EBA6;">$\lim \frac{\infty}{\infty}$</mark> , weil beides gegen Unendlich geht.
    - **Wie macht man das also ?**
		- man leitet den Zähler und den Nenner ab und macht einfach nochmal den Limes
- Wie überprüft man diesen für die Funktionen?
    - **Beispiel 1 (einfaches Funktion):**

        - $$f: \mathbb{R\setminus{1}} → \mathbb{R}, f(x) = \frac{1}{x^2-1} \ x_0 = 1
        $$
        
        - Wenn wir jetzt z.B den Grenzwert an der stelle x_0 = 2 überprüfen möchten, verwenden wir einfach den Limes 🙂
        - Also Würden wir schreiben: $\lim\limits_{x\to 2} \frac{1}{x^2-1}$
        - Hier kann man jetzt einfach überall die 2 einsetzen, und würde $\frac{1}{4-1} = \frac{1}{3}$  erhalten. Also besitzt die Funktion an der Stelle $x_0 = 2$ einen Grenzwert.

			---

    - **Beispiel 2 (einfache Funktion, anderes $x_0$):**
        - Meistens guckt man sich aber die sog. “kritischen Stellen” an, also Zahlen, die ich hier nicht einsetzen darf
            
            $$
            f: \mathbb{R\setminus{1}} → \mathbb{R}, f(x) = \frac{1}{x^2-1} \ x_0 = 1
            $$
            
        - Gucken wir uns nochmal, das beispiel an, diesmal ist $x_0$ aber 1 und nicht wie vorhin 2.
        - Was würde jetzt passieren, wenn ich die 1 in das x einsetze ? wir würden rechnen: $\lim\limits_{x\to 1} \frac{1}{(1)^2-1} = \frac{1}{0} = \infty$
        - $\infty$ ist keine eindeutiger Zahlenwert mehr, also besitzt diese Funktion an dieser Stelle schon keinen Grenzwert mehr.
        
			---
		
    - **Beispiel 3 (Abschnittsweise definierte Funktion):**
        
        - $$
        f(x)=\begin{cases}7x-6& \text{falls }x≤3 \\ 2x^2+3 & \text{falls }x>3 \end{cases}, \text{mit} \ x_0 = 3
        $$
        
        - $x_0$ können wir auch easy ablesen weil da ≤ 3 und > 3 steht.
        - Nun haben wir eine abschnittsweise Definierte Funktion... was machen wa denn da ? ganz easy,
        - Wir betrachten einfach den “linksseitigen-” und den “rechtsseitigen” Grenzwert.
        Also gilt:
        - $\lim\limits_{x\to 3,-}7x-6= 7\cdot3-6 = 15$ (linksseitiger Grenzwert)
        - $\lim\limits_{x\to 3,+}2x^2+3= 2\cdot3^2+3 = 21$ (rechtsseitiger Grenzwert)
        - hier muss der linksseitiger Grenzwert und der Rechtsseitige Grenzwert aber gleich sein... ist es nicht ⇒ Die Funktion besitzt keinen Grenzwert^^

			---

---
