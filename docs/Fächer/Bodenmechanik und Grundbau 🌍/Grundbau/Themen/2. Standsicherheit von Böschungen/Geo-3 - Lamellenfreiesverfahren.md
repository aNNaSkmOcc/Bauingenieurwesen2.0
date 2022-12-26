### Allgemeines
Das Lamellenfreie verfahren ist wie der Name schon sagt, ein verfahren, wo wir den Boden halt nicht in verschiedene Lamellen unterteilen, sondern, Immer Schrittweise Kräfte berechnen und diese dann miteinander addieren.

Im prinzip sieht unser Gesamtsetup so aus:

![[IMG_4D5FF0F8EF76-1.jpeg|400]]

### Treibende Kräfte
##### 1. Vertikalkräfte 

Diese Resultieren meist aus der Auflast und den Eigengewicht :D 

Wir berechen das Eigengewicht folgendermaßen :

![[IMG_D010A981318E-1.jpeg]]

Das Eigengewicht berechnet sich meist aus der Querschnittsfläche mal der Wichte :D 

Die Auflast ist dann einfach die Resultierende von unserer Linienlast :D

Das miteinander verrechnet, ergibt sich dann als unser R1 :D

##### 2. Strömungskraft
Nun haben wir ja noch die Strömungskraft, die auf den Boden wirkt, die wir ja natürlich auch berückstichtigen müssen :D

schauen wir uns das mal anhand des Kraft-Ecks mal an:

![[Bildschirm­foto 2022-12-09 um 08.45.24.png]]

Wir sehen unsere in Schritt 1 berechnete Resultierende R1.

Dazu, kommt jetzt aber ja die Strömungskraft, welche dann zusammen mit R1, zu R2 resulitert.

Noch ein kleiner Einblick, wie man denn $F_{s,k}$ also die Strömung berechnet:

![[Bildschirm­foto 2022-12-09 um 08.46.46.png]]

##### 3. Kohäsion
Jetzt kommt ja noch die Kohäsion dazu :D 

Zunächst einmal easy wieder im Krafteck dargestellt:

![[Bildschirm­foto 2022-12-09 um 08.48.51.png]]

Da haben wir wieder unsere Resultierende R3, und die kohäsion c.

Auch hier, erhalten wir dann die neue Resultierende R3, die wir mit R2 + c erhalten.

gucken wir uns jetzt an, wie wir das berechnen, und wieso die kohäsion nicht direkt auf der Oberfläche angreift, sondern etwas weiter unten:

unsere Kohäsion wirkt nicht direkt an der Gleitfläche, um auf der sicheren Seite zu sein, weil wir dann beidem Momentengleichgewicht ein größeres Moment haben.

schauen wir uns mal die Formeln an:

![[Bildschirm­foto 2022-12-09 um 08.55.41.png]]

Hier berechnen wir einmal die Resultierende der Kohäsion einmal

wie funktioniert die Formel ?
Damit wir ein Rechtwinkliges Dreieck haben, und unsere allbekannten trigonometrischen Funktion sin cos tan benutzen können, wurde erstmal um den winkel $\psi$ eine Winkelhalbierende gezogen, welches auch die gestrichtelte Wirkungslinie der Kohäsion halbiert.

Daher kommt erstmal die $\cdot 2$ ins spiel.

Den rest, bekommen wir dann durch den sinus.

das $r_c$ ist unser Hebelarm :D 

##### 4. Das "Auflager" 
Jetzt kommt zum Schluss noch ja die joa art "Auflagerkraft" Q dazu. Diesen müssen wir natürlich ebenfalls berücksichtigen.

Diese Betrachten wir nicht direkt bei der vertikalen Kraft, weil diese sich von dieser unterscheidet, auch wenn es eine Vertikale Kraft ist.

Auch dieser hat natürlich ein Moment :D den Hebelarm dafür berechnen wir folgendermaßen:

![[Bildschirm­foto 2022-12-09 um 15.10.17.png]]

Das coole ist, dass diese immer den Reibungskreis berührt :D



Jetzt haben wir all unsere Zutaten zusammen und könnten nun den Nachweis führen.

Da gibt es 2 Arten von

##### 1. Nachweis - Partialsicherheit (Oldschool)
![[Bildschirm­foto 2022-12-09 um 15.15.19.png]]

##### 2. Nachweis - Ausnutzungsgrad
Das ist schon die etwas akutellere Nachweismethode :D

Es gilt, wie auch sonst immer:

$$\boxed{\mu ≤ 1}$$

Wenn das nämlich erfüllst ist, dann hält das Bauteil :D

Setzen wir also mal die Zutaten für das Kochrezept ein:

![[Bildschirm­foto 2022-12-09 um 15.18.16.png]]

Jetzt haben wir also oben die Einwirkenden Momente, und unten die Wiederstandsmomente :D






