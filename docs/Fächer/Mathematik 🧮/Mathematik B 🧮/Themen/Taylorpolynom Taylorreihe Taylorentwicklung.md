# Taylorpolynom/Taylorreihe/Taylorentwicklung
    

- **6.4 Was ist ein Taylorpolynom**:

	- ![[Bildschirmfoto_2022-04-05_um_07.26.19.png|Bildschirmfoto 2022-04-05 um 07.26.19.png]]

	- Taylorreihen ist eine spezielle Potenzreihe.
	- Man kann jede beliebige Funktion ungefähr als die Taylorreihe bzw. als Taylorpolynom darstellen, weil es einfacher ist mit Polynomen zu rechnen als mit keinen 🙂
	- das Taylorpolynom 1. Ordnung ist immer die Tangente der Funktion und die Tangente der Funktion ist immer das Taylorpolynom 1. Ordnung.
	- Je mehr polynome man hat, desto genauer approximiert man die Funktion.

		---

	- Schauen wir uns die allgemeine Definition mal an:
	- das erste Polynom mit der hoch 0, wäre das Taylorpolynom 1. Ordnung.
	- das erste **und** zweite zusammen, wären zusammen das Taylorpolynom 2. Ordnung. usw usw.

	- ![[Bildschirmfoto_2022-04-05_um_07.31.44.png|Bildschirmfoto 2022-04-05 um 07.31.44.png]]

	- Gucken wir uns dieses Beispiel mal an:
	- nur das x alleine besitzt ein unsichtbares hoch 1, somit ist alleine nur dieses x, das Taylorpolynom 1. Ordnung.
	- das erste und zweite polynom zusammen ergeben das Taylorpolynom 3. Ordnung, weil die höchste Potenz dieser beiden die hoch 3 ist.
	- und alle Polynome in diesem Beispiel zusammen, ergeben dann das Taylorpolynom 5. Ordnung, weil die höchste Potenz die hoch 5 ist.
	- wie kommt man aber von dem sin(x) auf die Polynomfunktion?

		- ![[Bildschirmfoto_2022-04-05_um_07.26.19.png|Bildschirmfoto 2022-04-05 um 07.26.19.png]]

		1. Weil wir ein Taylorpolynom 5. Ordnung haben wollen, müssen wir die Funktion 5 mal ableiten.
		2. Nun setzen den Startpunkt t_0 in jeden dieser Ableitungen ein.
		3. Nun kommen die Ergebnise aus Schritt 2, in den Zähler der Allgemeinen Funktion.
		4. die potenz der Klammer wird auch erhöht


		>[!TIP] 0! ist laut definition immer 1 **!!Wichtig!!**

	</aside>
        
- **6.4 Taylorreihe / Taylorentwicklung:**
    
    - ![[Bildschirmfoto_2022-04-05_um_07.26.19.png|Bildschirmfoto 2022-04-05 um 07.26.19.png]]
    
    - Ein Taylorpolynom mit Polynom k. Ordnung, bildet genau die Funktion wieder ab
    - Eine Taylorreihe im Entwicklungspunkt $x_0 = 0$ nennt man auch “McLaurin-Reihe”.
    - Die Kunst ist es hierbei jetzt herauszufinden, z.B ohne zu wissen was die 26. Ableitung einer Funktion ist, wie die 27. Ableitung einer Funktion aussieht.
    
		---
    
    - Wie macht man das jetzt ?
    
    	- ![[Bildschirmfoto_2022-04-05_um_08.49.05.png|Bildschirmfoto 2022-04-05 um 08.49.05.png]]
    
    	- Man guckt sich z.B die Funktion f(x) = sin(x) an
        	1. Man leitet die Funktion einfach paar mal ab und versucht irgendwelche muster zu erkennen. die ableitung von sin(x) ist cos(x)... da könnte man also schon direkt aufhören.
		-  **Nun der Trick:** 
			- Cosinus ist ja nix weiter, als die Verschiebung von sinus um $\frac{π}{2}$ verschoben.
			- Aaaalso ist cos(x) ja nix weiter als sin(x+$\frac{π}{2}$) 
            	⇒ $f’(x) = cos(x) = sin(x+\frac{π}{2})$.
			- Nun die zweite Ableitung:
            	⇒ $f’’(x) = -sin(x) = sin(x+2\frac{π}{2})$.
			- Und die dritte Ableitung:
			⇒ $f’’’(x) = -cos(x) = sin(x+3\frac{π}{2})$
			- Wir erkennen hier ein Muster, dass sich die konstante vor der $\frac{π}{2}$ immer um einen erhöht. Schon sind wir fertig. Wir können also nun direkt sagen, was z.B die 27. Ableitung von f(x) ist.
			- Unser Taylorpolynom lautet dann:
                
			- ![[Bildschirmfoto_2022-04-05_um_09.25.24.png|Bildschirmfoto 2022-04-05 um 09.25.24.png]]
               
    
- **Coole Tricks von Heinzner:**

	- Wenn man eine Polynomfunktion gegeben hat, und dann das Taylorpolynom davon bestimmen musst, ist die Polynomfunktion auch die Taylorfunktion
	- Wenn man eine Funktion gegeben hat, die binomischen Formel ähneln, kann man das mit dem Binomialkoeffizienten machen:

	- ![[IMG_6B0ADB5739C9-1.jpeg]]

	- Mal ein anderes beispiel:

		![[IMG_316159D32F9E-1.jpeg]]