Die kinematische Methode, ist eines der 2 möglichkeiten, um Erddrücke zu berechnen.

Dabei, betrachten wir zunächst einmal einfachheitshalber den sogenannten **Rankine-Fall**, wo die Wand **genau** senkrecht ist und wir keine neigung haben.

Somit, wirkt bei dem Rankine-Fall, der Erddruck auch horizontal.


### Aktiver Erddruck

Wir betrachten zunächst einmal den aktiven Druck.

schauen wir uns den aktiven Druck mal an:

![[IMG_76881B06AFD0-1.jpeg]]

links wirken dann die Kräfte. in der Mitte, wurden jeweils immer die resultierenden der Kräfte berechnet.

Q setzt sich zusammen aus T (Scherspannung) und N(Normalspannung)

Q, G und E können wir jetzt in ein sogenanntes Kraft-Eck eintragen :D

Die Formeln für die einzelnen Kräfte sehen dann so aus:

![[IMG_2CBC03EB4E9F-1.jpeg]]

Die Formel für das E, brauchen wir jetzt am meisten.

Woher weiß ich denn jetzt, genau, die Neigung der Wand ?

Theoretisch, muss ich jetzt für jede Wandneigung einen Versuch durchführen und den maximalen aktiven Erddruck bemessen.

Wie kann ich denn noch extrempunkte, in dem Fall die Hochpunkte bemssen ?

Na einfach Ableiten und gleich 0 setzen :D

Das wurde dann hier gemacht:

![[IMG_540D64FB3BC3-1.jpeg]]

Wichtig ist hier wieder, dass das hier die lösung von Coloumb für den Rankine Fall, also dem Fall, dass die Wand gerade ist.

Was ist denn jetzt also, wenn wir eine geneigte Wand haben ?

im prinzip, ist es das gleiche:

![[IMG_7759CC50A0D9-1.jpeg]]

Was sich ändert ist, dass natürlich alle Kräfte ihre Neigung ändern. 

Dadurch, ist der Beiweirt $K_a$, natürlich eine richtig beschissene Formel, die wir sicher nicht rechnen möchten

Schauen wir uns das mal als bild alles an:

![[IMG_7759CC50A0D9-1 1.jpeg]]

Ich habe nicht zu viel versprochen als ich gesagt habe, der Beiwert sieht beschissen aus haha

Aber wir wären keine Ingenieure, wenn wir nicht auch dafür Tabellenwerke hätten :D

![[IMG_9622BC50D68D-1.jpeg|400]]

Kommen wir aber mal zurück, zu der Frage wie wir das jetzt nachweisen ?

Was haben wir in Mechanik gemacht ? wenn wir geneigte Komponenten haben?

Wir haben die immer in Komponenten aufgeteilt höhö

Also haben wir die Komponenten $E_{ah}$ (Horizontal) & $E_{ah}$ (Vertikal)

Aber auch die Aufteilung ist nicht schwer, gucken wir uns die berechnung für $E_{ah}$ einfach mal an:

![[IMG_9FA258C91995-1.jpeg|400]]

Was sich jetzt nur noch geändert hat ist, dass wir nur einen anderen Beiwert haben, den lesen wir im endeffekt genau so ab, nur dass wir jetzt $\alpha$ & $\beta$ ≠ 0 haben.

Schauen wir uns doch jetzt mal Realen fall an:

![[IMG_D249EFBB4085-1.jpeg|400]]

Jetzt haben wir oben eine Linienlast und auch eine Kohäsion.

Diese müssen wir natürlich auch berücksichtigen.

dann sieht die Allg. Formel, für den Erddruck nämlich so aus:

![[IMG_8EA943BBEED9-1.jpeg]]

Das schöne ist, dass wenn ich eine Kohäsion habe, diese abgezogen wird. Somit kommt die Kohäsion uns zu gute und verringert unsere Einwirkung :D

Ich habe natürlich einmal den Eigengewichtsanteil. Außedem haben wir jetzt noch zusätzlich den Anteil von Kohäsion und Auflast :D

Diese haben natürlich auch Erddruckbeiwerte.

Einmal für Nutzlast:

![[IMG_60F364C9C583-1.jpeg]]


Und natürlich auch für Kohäsion:

![[IMG_60F364C9C583-1 2.jpeg]]

#### Standhöhe

Was auch wichtig ist, die freie Standhöhe. Diese gibt nämlich an, wie tief ich Buddeln kann, bis das loch von oben einstürzt.

![[IMG_0D5F54EF4046-1.jpeg]]

Das aber nur mal so Nebenbei :D

Jetzt ist es ja so, dass wir vereinfacht die lineare Gleitfläche annehmen. 

In der realtität ist es aber so, dass wir gekrümmte Gleitflächen haben...

![[IMG_AC52B4D5AC60-1.jpeg|400]]

Es ist jetzt aber so, dass es bei den aktiven Drücken so wenig unteschied macht, dass es eigentlich egal ist dass wir die Vereinfachung als ein lineares annehmen :D

### passive Erddrücke
Jetzt haben wir natürlich auch die passiven Erddrücke am start :D

nochmal zur Wiederholung: Die passiven Erddrücke sind quasi der wiederstand :D

Im Grunde genommen, ist es einfach nur das gleiche, nur dass sich überall die Vorzeichen ändern.

Deswegen werde ich nicht so krass drauf eingehen:

Schauen wir uns auch hier mal den Rankine Fall mit nur Eigengewicht an:

![[IMG_E601F624EFB9-1.jpeg]]

![[IMG_EF719176D37D-1.jpeg]]

Der Erddruckbeiwert lässt sich dann so berechnen

Das wäre wieder unser passiver Erddruck, in dem Rankine fall ohne auflast und kohäsion.

Natürlich haben wir auch einen verallgemeineterten Fall in der Praxis:

![[IMG_7A13EAE2E024-1.jpeg]]

Sieht eigl hier genau gleich aus wie davor aus.

Der einzige Unteschied hier ist, dass hier dir kohäsion nicht abgezogen, sondern draufgerechnet wird.

In dem fall, kommt die Kohäsion uns auf jedenfall zu gute.

Auch hier können wir die Druckbeiwerte berechnen. Die Formel ist natürlich auch richtig kagga :D

![[IMG_74013748DAC4-1.jpeg]]

Auch hierfür gibt es Tabellen :D

![[IMG_DB621822E0B6-1.jpeg|400]]


Jetzt haben wir bei den passiven Kräften allerdings ein kleines Problem,

gerade haben wir bei den aktiven Kräften ja einfach die annahme getroffen, dass wir das linear annehmen können oder ? 

Tja lieber leser :D hier geht das leider nicht mehr ^^

Leider ist das bei den passiven Kräften so, dass wir sonst auf der zu unsicheren Seite wären :D.

Deswegen müssen wir hergehen, und wirklich die genaue Gleitfläche berechnen.

![[IMG_A530BFC090A2-1.jpeg|250]]

Dann sehen unsere Erdruckbeiwerte natürlich auch anders aus :

![[IMG_A62660C2F404-1.jpeg]]

Der Druckbeiwert, ist eh abhängig vom Winkel.

die anderen Parameter, könnten wir jetzt auch irgendwie berechnen, allerdings gibt es auch hierfür Tabellen :D

![[IMG_C03353960D48-1.jpeg]]
