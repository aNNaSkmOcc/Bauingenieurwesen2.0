# Flächenträgheitsmoment und Biegelinie

>[!TIP] Eine wichtige Seite dafür ist:
>[[https://www.studyhelp.de/online-lernen/mechanik/flaechentraegheitsmomente-bestimmen/#_ftn1]]

####  **Das Flächenträgheitsmoment aka. das mystische I**

^a3b6bf

>💡 Das Flächenträgheitsmoment, ist der Querschnittsbedingte Wiederstand, gegen die Verformung in Querrichtung.
    
    
- Axiales Flächenträgheitsmoment (Der Wiederstand gegen normale Biegung):
        
	- ![[Flächenträgheitsmoment und Biegelinie 8ada733f9b6c4e0eb7fb108425d9c9f6/IMG_994DEFE1CAD4-1.jpeg|IMG_994DE.jpeg]]
        
	- Je nachdem wie das Koordinatensystem des Schwerpunkts geht, nimmt man für die horizontale Achse den index an
	- z.B wenn im Schwerpunkt die y-Achse horizontal ist und die z-Achse vertikal, nimmt man $I_y$
	- Wenn im Schwerpunkt die y-Achse vertikal ist und die z-Achse horizontal, nimmt man $Iz$.
- Biaxiales Flächenträghetitsmoment aka. Deviationsmoment (Wiederstand gegen schiefe Biegung)
        
	- ![[Flächenträgheitsmoment und Biegelinie 8ada733f9b6c4e0eb7fb108425d9c9f6/IMG_4CA79F5383CF-1.jpeg|IMG_4CA79F5383CF-1.jpeg]]
        
	- Es wird vor allem zur Ermittlung von Deformationen an asymmetrischen Profilen und zur Ermittlung nichtsymmetrischer Belastungen an beliebigen Profilen genutzt.

- <mark style="background: #FFB8EBA6;">**Beispiel an einem Querschnitt:**</mark> 
	- Betrachten wir nun mal ein Rechteckigen Querschnitt:
            
		![[Flächenträgheitsmoment und Biegelinie 8ada733f9b6c4e0eb7fb108425d9c9f6/IMG_9460E1E6DE7A-1.jpeg|IMG_9460E1E6DE7A-1.jpeg]]
            
	- Das ist unser Querschnitt, und davon sollen wir jetzt das $I_y$ berechnen. $I_y$, weil wie gerade gelernt, die y-Achse die horizontale Achse ist.
        - nun, $I_y$  berechnet sich wie folgt: $I_y = \int \limits_{A} z^2$
            
		![[Flächenträgheitsmoment und Biegelinie 8ada733f9b6c4e0eb7fb108425d9c9f6/IMG_3B96222DA2E4-1.jpeg|IMG_3B96222DA2E4-1.jpeg]]

	- Das Doofe: kein mensch weiß, wie man doppelte Integrale löst. Bei Doppelintegralen sowie immer bei der Mathematik gilt: stets von innen nach außen :)
	- das innere Integral, ist der Schwerpunkt in y richtung und das äußere das Integral in z-Richtung.
	- Als grenzen der Integrale, benutzt man die Abstände links und rechts zur Randfaser, da hier ein Rechteck vorliegt, wo der Schwerpunkt in der Mitte liegt, sind die Randfaser immer jeweils die hälfte.

		![[Flächenträgheitsmoment und Biegelinie 8ada733f9b6c4e0eb7fb108425d9c9f6/IMG_2DAD22B54415-1.jpeg|IMG_2DAD22B54415-1.jpeg]]
            
        - man muss das z^2 nach y Integrieren, deswegen kann man das z als eine Konstante betrachte und hängt einfach ein y hinten dran.
        - Anschließend setzt man da die obere Grenze ein, und zieht die untere Grenze ab und kommt dann auf die rechte Seite von der Gleichung.
        - Danach tut man das aber diesmal nach z integrieren, und das sieht wie folgt aus:
            
            ![[Flächenträgheitsmoment und Biegelinie 8ada733f9b6c4e0eb7fb108425d9c9f6/IMG_A223B63DD443-1.jpeg|IMG_A223B63DD443-1.jpeg]]
            
        - auch hier wieder Integrieren → obere Grenze - untere Grenze → Auflösen und fertiggg
##### Transformierte Koordinatensysteme
- **<mark style="background: #FFB8EBA6;">Einführung</mark> **
	- Okay, Flächenträgheitsmomente rechnen iiist ja schöön und gut ne ?
	- genau ist es aber da gibt es ein Problem, sehen wir uns mal ein Beispiel an:
        
	- ![[IMG_2103DC062363-1.jpeg]]
        
	- Tja... hier haben wir aber zwei Schwerpunkte, und die Formel von gerade eben für $I_y$ und $I_z$, könnte man für das linke rechteck perfekt benutzen. Für das rechte wirds dann doch ein wenig kritisch, denn es muss noch gedreht werden 🙂
	- Lösung Koordinatentransformation!!

- **<mark style="background: #FFB8EBA6;">Drehung</mark>** 

	- ![[IMG_9A0914426D97-1.jpeg]]
        
	- Die Rotation ist also wie beim Spannungs und Dehnungstensor
	- Das Hauptachsensystem lässt sich also wie folgt berechnen:
        
	- ![[IMG_B137DB617DF1-1.jpeg]]
        
	- Das coole ist, wenn das $I_{yz}$ schon 0 ist, dann sind wir bereits auf der Hauptachse und müssen das Koordinatensystem nicht noch zusätzlich drehen.

- **<mark style="background: #FFB8EBA6;">Parallelerschiebung mittels der Steinersätze</mark> **
	- Soo also die Drehung haben wir ja, die war ja recht easy
	- Allerdings, muss das Koordinatensystem vielleicht auch verschoben werden, diesmal ist aber nicht mehr ganz so trivial:
        
	- ![[Bildschirmfoto_2022-04-22_um_16.23.56.png]]

	- schauen wir uns mal das ganze an. Angenommen der schwerpunkt ist nicht in der Mitte sondern oben rechts. Das Problem: Der schwerpunkt ist nicht in der Hauptachse!!
	Lösung: Die Hauptachse entlang dessen Achsen verschieben
	- Die Verschiebung erfolgt mittels der Steinersätze
        
	- ![[IMG_62DFFDE95FB7-1.jpeg]]
        
	- Die $I_y$ und $I_{z}$ sind die Eigenträgheitsmomente
	- Der Steiner anteil, der ist lediglich der Abstand vom Punkt zum neuenpunkt in Axialrichtung.

##### Zusammengesetze Flächen
    
- [Ein video was man sich vielleicht mal anschauen kann](https://www.youtube.com/watch?v=rfbHPa8NHag&t=283s)

    
- ![[IMG_2F1C8C1D9BA9-1.jpeg]]
    
- Hier ist das Rechteck, teilt man wie üblich auch in zwei rechtecke diesdas
- Dann berechnet man den Schwerpunkt
- Dann berechnet man das Flächenträgheitsmoment von jeder Fläche und nimmt als Bezugsachsen, die Achsen die auf dem Schwerpunkt liegen.

##### Flächenträgheitsmoment für dünnwändige Querschnitte (UTIL- Profile, Stahl)
    
- ![[IMG_756FF7DAF415-1.jpeg]]
    
##### DGL der Biegelinie/Messung der Gebrauchstauglichkeit

^4d9e1b

- Wir nehmen dazu die [[Biege-normal-spannung|2. Bernoulli Hypothese]] und leiten sie ab, dann erhalten wir die Krümmung.
        
- ![[IMG_4CF00BFAED2B-1.jpeg]]
        
- Dann stellen wir das mal um nach $-M_y$
        
- ![[IMG_8E363E8EB82C-1.jpeg]]
        
- Man kann das jetzt ganz viel ableiten... Ableitung von -M_y ist -Q und davon die Ableitung ist q(x).
- Die gebrauchstauglichkeit wird dann so gemessen
        
- ![[IMG_9DB3470FBCC8-1.jpeg]]