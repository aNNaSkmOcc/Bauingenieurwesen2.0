# Differenzierbarkeit

bevor wir eine Funktion ableiten können, müssen wir erstmal auch gucken ob eine Funktion ableitbar ist. Im abi wurde das nicht so oft behandelt, weil die meisten Funktionen ehh Differenzierbar, also ableitbar sind. Aaber weil wir nicht mehr in der Schule sind und alles immer Nachweisen müssen, ist auch das hier wichtig

---

Nun... wie überprüft man eigentlich die Differenzierbarkeit?

zunächst muss man den [[Ableitungen#^1903b2|Binomialkoeffizient]] überprüfen ob der überhaupt existiert.

Bei einer Abschnittsweise definierten Funktion allerdings, muss man wieder den **rechtsseitigen** und den **linksseitigen** Binomialkoeffizienten bilden.

Schauen wir uns dazu mal eine ein Beispiel an:

- **Beispiel:**
	- ![[IMG_9A11EC1FCF13-1.jpeg]]
	- dies sei mal unsere Abschnittsweise definierte Funktion.
	- Für $x < 1$ und $x > 1$, können wir schon direkt sagen okay die Funktion ist als Polynom differenzierbar, weil polynome ja Differenzierbar sind. jetzt müssen wir uns aber die kritische Stelle bei $x_0 = 1$ anschauen.

	- wir wenden den Binomialkoeffizienten für links und rechts an:
	- **Linksseitiger Grenzwert (LDW) :**
	- ![[IMG_B4A6590262E9-1.jpeg]]
	- **Rechtsseitiger Grenzwert (RDW) :**
	- ![[IMG_B4A6590262E9-1 2.jpeg]]
	- => Der linksseitige und rechtsseitige Grenzwert ist gleich, also ist die Funktion differenzierbar.

	- **Fazit:**
		1. Kritische stelle ermitteln
		2. gucken ob an der Stelle der LGW und der RGW gleich sind 

---

Wichtig ist zu wissen, dass bei 2 Funktionen die n-mal differenzierbar sind, die Verknüpfung derer ebenfalls n-mal differenzierbar ist.

![[IMG_B2F909498A50-1.jpeg]]