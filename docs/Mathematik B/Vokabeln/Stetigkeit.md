# Stetigkeit
### Stetigkeit in $\mathbb{R}$

>[!TIP] Man sagt, eine funktion ist stetig, wenn man sie mit einem Stift durchzeichnen kann ohne sie abzusetzen.

- Wichtige stetigkeiten die man direkt kennen sollte:
	- $$\frac{1-cos(x)}{x^2} = \frac{1}{2}$$

- <mark style="background: #FFB8EBA6;">**Funktionen die Automatisch stetig sind:**</mark> 
        
	- ![[IMG_62A978563A1D-1.jpeg]]  
	<mark style="background: #FFB8EBA6;">- Verrechnen von 2 stetigen Funktionen, ergibt wieder eine stetige Funktion.</mark> 

- **<mark style="background: #FFB8EBA6;">wie überprüft man die Stetigkeit für Funktionen</mark> **
	- Beispiel: abschnittsweise definierte Funktion
        
	- $$
	f(x)=\begin{cases}2& \text{falls }x≤2 \\ \frac{x+4}{3} & \text{falls }x>2 \end{cases}, \text{mit} \ x_0 = 2
	$$
        
	- Hier haben wir wieder eine Abschnittsweise defininerte Funktion.

	1. Wir überprüfen, ob die Funktionsvorschriften überhaupt Stetig sein können.
        In dem Beispiel können sie das, die obere ist konstant und die untere Funktion ist ein Polynom.

	2.  Wir kontrollieren suchen wieder den linksseitigen und den rechtsseitigen Grenzwert und gucken ob diese gleich sind

		---

        **In dem Beispiel:** 
		$\lim \limits_{x \to 2,-} 2 = 2$ (Rechtsseitiger Grenzwert)


		$\lim \limits_{x \to 2,+} \frac{x+4}{3} = \frac{6}{3} = 2$ (Linksseitiger Grenzwert)


		⇒ Hier ist der linksseitige und der Rechtsseitige Grenzwert gleich ⇒ Grenzwert existiert.

	1. Wir ermitteln noch den Funktionswert der kritischen Stelle:
        **In dem Beispiel:**
        $f(2) = 2$ (weil für x ≤ 2, die Funktionsvorschrift 2 gilt).
	1. Ergebnisse Auswerten:
        **In dem Beispiel:**
        ⇒ Da hier der Grenzwert und der Funktionswert gleich sind, ist diese Funktion stetig.

- **<mark style="background: #FFB8EBA6;">Stetigkeitsergänzung</mark> **
   
    - >[!TIP] Hier beschäftige ich mich mit der Frage, wie man eine Funktion an nicht definierten (Kritischen)Stellen trotzdem stetig ergänzen kann.
    
    
    - **Vorraussetzungen für eine Stetigkeitsergänzung :**
        1. Die Funktion muss stetig sein (falls nicht, stetigkeit prüfen)
        2. Die Funktion muss einen Grenzwert besitzen
    - Dann geht man einfach hin, und wählt den Wert für die kritische Stelle so, dass diese gleich dem Funktionswert und dem Grenzwert ist. Dann ist die Funktion ja weiterhin stetig ^^

    - Beispiel:
        
		- $$
        f: \mathbb{R} \setminus{0} \to \mathbb{R} \ \text{mit} \ f(x)=\frac{1-cos(x)}{2*x^2} \ \text{mit} \ x_0 = 0
        $$
        
		1. Wir wissen ok, die Funktion ist Stetig, weil die Funktion ein Quotient aus 2 stetigen Funktionen ist.
        1. Nun müssen wir den Grenzwert überprüfen:

        - Also gilt:
        
			- $$
        \lim\limits_{x\to 0} \frac{1-cos(x)}{2*x^2} 
        $$
        
			- Wenn wir hier die Kritische Stelle einsetzen würden, würden wir oben 0 erhalten und unten auch 0, somit würden wir den Grenzwert von $\frac{0}{0}$ untersuchen ⇒ [[Stetigkeit und Differenzierbarkeit c4a815c13d3d4bdfae9fec73dd6a5f08.md|Satz von L’Hospital]]

			- Nach dem Satz von L’Hostpital, erhalten wir einen Grenzwert von $\frac{1}{4}$.
			- Joa dann ist klar, dass wir für die kritische Stelle, den Funktionswert einfach 1/4 setzen müssen, damit die Funktion weiterhin stetig ist.
			Somit würde die Funktion lauten:
        
        $$ f(x)=\begin{cases}\frac{1-cos(x)}{2*x^2}  & \text{falls }x \not= 0 \\ \frac{1}{4} & \text{falls }x = 0 \end{cases}$$
		
		---

### Stetigkeit in $\mathbb{R}^n$

Hier ist das Problem, dass wir das nicht wie bei den Funktionen aus den $\mathbb{R}$ einfach wie oben beschrieben die stetigkeit prüfen können, indem wir uns den linksseitigen und rechtsseitigen Grenzwert anschauen diesdas, weil wir hier im $\mathbb{R}^n$ aus unendlich vielen Richtungen betrachten können.

Also geht man das ganze ein wenig anders an. Folgende Aufgabe betrachten wir uns mal folgende Aufgabe :
![[IMG_7CA7AD23E112-1.jpeg]]

Man stellt zunächst eine Vermutung auf, und guckt ob man die stetigkeit Zeigen oder wiederlegen muss.

hier in dem Fall können wir erstmal ein Parameter eliminieren indem wir uns $f(x,x)$ einsetzen und das dann gegen 0 laufen lassen.

![[IMG_C6014DB351B6-1.jpeg]]

Wir sehen, dass die Funktion einen Grenzwert hat, und somit wissen wir, dass wir die Stetigkeit aufjedenfall für ein **beliebiges** $f(x_0,y_0)$ zeigen müssen.

Es muss gelten:

![[IMG_B7BD0FDA1FD7-1 2.jpeg]]


