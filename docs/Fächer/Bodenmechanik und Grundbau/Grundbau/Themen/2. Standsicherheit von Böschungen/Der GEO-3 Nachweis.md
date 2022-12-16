Fangen wir zunächst einmal an, mit dem **GEO-3** Nachweis. Mit diesem, weisen wir nämlich nach, dass die Gesamtkonstruktion hält.

### Geo-3 Nachweis, für Böschungen
Hier gehen wir naütürlich nach der **DIN 4084:2009**.

Für die geraden Gleitflächen, betrachten wir die Kräfte.
![[IMG_A884A16763F7-1.jpeg]]

Für die gekrümmten Gleitflächen, betrachten wir die Kräfte.
![[IMG_A884A16763F7-1 3.jpeg]]

Was wir jetzt noch wissen ist, dass wir die 

#### Gerader anwinkel


##### Fall: überall gleicher Boden
Schauen wir uns also mal den einfachsten Fall an:

![[IMG_6DFCC2A3E70B-1.jpeg|300]]

Stellt sich jetzt also mal die Frage, welche Kräfte denn so wirken:

![[IMG_2FAA95749E62-1.jpeg|300]]

Natürlich wirken hier die Erddrücke. Hier wirken sie von beiden seiten.... Also haben wir den **ruhenden Erddruck**

![[IMG_34224225D617-1.jpeg|300]]

Außerdem wirken natürlich Eigengewichte. Die Kraft des Eigengewichts können wir folgendermaßen aufteilen:

zum einen haben wir eine Normalkomponente $N_d$ die genau Senkrecht zur geneigten Fläche wirkt.

Außerdem, haben wir dann die Tangentialkomponente $T_d$, die genau entlang der geneigten Fläche wirken.

Was wir noch zum Schluss haben ist, eine wirkennde Kraft $Q_d$, diese ist so eine Art Auflager für uns :D

Hier ist es wichtig, die treibenden Kräfte infolge Eigengewicht zu berechnen... diese berechnen wir folgendermaßen:

![[IMG_709BE647C1F1-1.jpeg]]

Die **Treibende Kraft $E_d$** haben wir jetzt also, berechnen wir uns jetzt auch den Wiederstand dagegen... also die **rückhaltende Kraft**

![[IMG_B08686AB3F0A-1.jpeg]]

Die Rückhaltende Kraft , ist eigentlich nichts anderes als das maximale $T_d$, welches ja aus dem Eigengewicht resultiert.

Das N, können wir ersetzen durch :

![[IMG_330CAFE323C8-1.jpeg]]

Sodass sich unser $R_d$ berechnen sich lässt als:

![[IMG_330CAFE323C8-1 2.jpeg]]

Jetzt müssen wir ja den Nachweis führen ob das ding hält.....

Das Ding hält ja, wenn der Wiederstand größer ist, als die Einwirkung.

Das heißt also, wir überürpfen folgendes:

![[IMG_4289F9724969-1.jpeg|400]]

---

##### Fall: Boden mit Wasser
Schauen wir uns jezt mal einen etwas komplexeren Fall an:

![[IMG_457F3FD12848-1.jpeg|250]]

Hier ist das jetzt so, dass wir nicht überall den gleichen Boden haben, sondern eine Bodenschicht, und darunter eine Schicht Wasser.

Diesmal haben wir 2 Eigengewichte die wirken... einmal vom Boden und vom Wasser.

Außerdem haben wir eine Strömungskraft $F_{s,d}$

ganz Analog wie vorhin, haben wir hier auch eine Normalkraft, eine Tangentialkraft und eine Auflagerkraft Q.

Die Auflagerkraft Q, wirkt aber nicht gerade wie vorhin. Wieso ist das so?

Schauen wir uns mal das KraftEck an:

![[IMG_58C033E540C6-1.jpeg]]

Ich hab da die Beiden Eigengewichte + die Strömungskraft.

Daraus resulitert dann eine Diagonale Kraft wenn man die miteinander addiert.

Die Auflagerkraft $Q_d$, muss dann genau so groß sein wie die Resuliterende.

Da sind im prinzip der **treibende- und einwirkende Kraft** fast gleich.

Schauen wir uns das doch mal an:

<mark style="background: #FFB86CA6;">Die treibende Kraft, also die Einwirkung berechnet man so:</mark>

![[IMG_413EB455766B-1.jpeg]]

sollte eigentlich recht simpel sein :D Einmal die Strömungskraft, und dann die beiden Eigengewichtskomponenten, in richtung des Stroms.

Die rückhaltende Kraft, also den Wiederstand berechne ich dann so:

![[IMG_42AA15CB4E0E-1.jpeg]]

Die Resultierende Normalkraft dafür, berechnen wir dann so :

![[IMG_AED7F12C06CB-1.jpeg]]

Jetzt können wir auch wieder einfach den Nachweis folgendermaßen Führen:

![[IMG_7A5C0AB8D3E2-1.jpeg]]

---

##### Fall: Alles komplett Wasser D:

![[IMG_95C9C5D48E03-1.jpeg|250]]

Dieser Fall, wäre son worstcase haha 

Hier ist der Prof jetzt nicht noch komplett noch auf alle Rechenschritte eingeangen.

Allerdings, sieht der Nachweis dafür jetzt so aus:

![[IMG_65D4812D36B5-1.jpeg|400]]

Der anteil mit dem d kürzt sich weg, und für $\gamma_w$ setzen wir 0.5 ein.

Somit kommt dann das raus, was im gelben Kästchen steht.




#### Kreisförmige Gleitfläche

Joo :D schauen wir uns jetzt mal an, wie man denn eine Kreisförmgie Gleitfläche berechnet und nachweist.

Man könnte das mit dem [[Geo-3 - Lamellenverfahren]]  oder mit dem [[Geo-3 - Lamellenfreiesverfahren]] machen.