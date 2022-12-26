Die **indirekte Methode** ist halt auch eine Möglichkeit, wie man Setzungsprognosen treffen kann.

Vorteilhaft ist die indirekte Methode deswegen, weil man sie gut mit Tabellenkalkulationsprogrammen wie Excel programmieren kann.

Hierbei geht man her, und teilt den Boden in einzelne Schichten auf...

Das sieht dann ungefähr so aus:

![[IMG_B58ABB17578E-1.jpeg]]

Die Anzahl der Schichten, ist dank Computern heutzutage Egal. Sinn machts aber da wo mehr passiert, wo man genauer schauen muss, mehr Schichten zu machen als bei den anderen.

Wir schneiden uns ein kleines Element heraus und haben da die rote belastung, welches das Eigengewicht beschreibt.

Nun packen wir ein Fundament drauf die von der blauen Last beschrieben wird.

Dann beschreibt man auch das wieder mit einer Spannungs, Dehnungs, linie :D

### Kochrezept
Hier mal ein Kochrezept, wie man es eigentlich macht :
![[IMG_793A1F9537E2-1.jpeg]]
1. Man Unterteilt natürlich die Schichten in mehrere Teilschichten.

2. Dann berechne ich die Spannung **infolge Eigengewicht** ($\sigma'_0(z)$) und **infolge zusätzliche Last** ($\Delta \sigma'_0(z)$). Anschließend Addiere ich sie Zusammen und erhalte $\Delta \sigma'_1(z)$

>$\sigma'_0(z)$  nimmt mit der Tiefe zu, während $\Delta \sigma'_0(z)$ immer mehr Abnimmt.

Wie tief man gehen sollte, gibt es eine kleine Faustregel :

>Es reicht aus, wenn wie so tief gehen, dass ($\Delta \sigma'_0(z)$) nur noch 20% von ($\sigma'_0(z)$)  ist.

3. Nun kann man für jede Schicht das Steifemodul berechnen.. das geht dann so:

![[IMG_C21B6FC8DB04-1.jpeg]]

Ich hab auch hier wieder eine Spannungs Dehnungslinie. 

Sigma 1 und Sigma 2 sollten auch klar sein :D 

Mann nimt aber weder Sigma 1 noch Sigma 2... man nimmt die mitte von den beiden :D 

Die Mitte von den beiden, wäre dann das $\sigma'_{av}$

4. Nun kann ich für jede Teilschicht die Dehnung berechnen:
![[IMG_93C84643A730-1.jpeg]]

5. Mit der Dehnung dann die Setzung berechnen:
![[IMG_2091DA1505E4-1.jpeg]]

6. Uuuund die Setzungen aufsummieren:
![[IMG_639EBAB2AE92-1.jpeg]]

### Berechnung für starre Fundamente
Auch hier, ist die Berechnung nur für starre Fundamente möglich. ich könnte aber auch durch paar kurdische Tricks das ganze für starre Fundamente berechnen:

![[IMG_9D88EFD801DE-1.jpeg]]


