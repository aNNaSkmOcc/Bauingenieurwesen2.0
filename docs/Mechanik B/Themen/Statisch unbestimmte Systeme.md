# 11. Statisch unbestimmte Systeme

ENNNDLICHHH :DDD Hier geht es darum, dass wir endlich anfangen, statisch unbestimmte Systeme berechnen :DD

gucken wir uns folgendes Problem an :DD

![[IMG_9F3B4960B913-1.jpeg]]

Klar hier sehen wir direkt, dass das System statisch unbestimmt ist. Wir haben nur 3 Gleichgewichtsbedingungen zur verfügung aber haben 5 auflagerreaktion -> 2 sind also zu viel höhö

Tja jetzt würden wir sagen : höhöhö sry chef kann ich nicht aaaaaabbberrrr nichts ist unmöglich :DD

### Methode 1: Satz von Castigliano 

Wir benutzen hier einen Speizalfall des 1. Satzes vom Castigliano... der geht folgendermaßen

![[IMG_193BDC15EBA6-1.jpeg]]

Hier das Spezielle ist, dass wir das = 0 setzen. Der Satz von Castigliano wandelt sich dann zum **Satz von Menabrea**

Der Grund, dass wir das 0 setzen ist, dass wir eine Auflagerkraft berechnen, und dieser quasi keine verschiebung hat. 

Der Satz von Menabrea ist allerdings eingeschränkt. Dieser erlaubt es uns nur, Auflagerkräfte zu berechnen und nicht Verschiebungen an beliebigen Stellen :D

gucken wir uns mal ein Beispiel ann

![[IMG_0C3C24E9F77B-1.jpeg]]

Wir haben hier wieder das Moment aus dem System berechnet und es Hoch 2 gesetzt. Dann lösen wir wieder die binomische Formel auf.

Jetzt aufgepasst: Wir bestimmen zuerst die Ableitung vom oberen Term nach groß X und bilden dann anschließend davon das Integral über die länge des Trägers. Das $\frac{1}{EI}$ kann ich vor das Integral ziehen :D. 

Habe ich das Integral bestimmt, setze ich das Integral dann einfach 0 und löse es nach dem großen X auf .

Das Problem von damals war es, das ganze zu automatisieren. Deswegen tendiert man eher zu einer anderen Methode nämlich:

### Methode 2: Prinzip der Virtuellen Kräfte
![[IMG_8D9B523627DA-1.jpeg]]
Auch hier wieder die Grundsätzliche Idee ist, dass man wieder Virtuelle 1-Kraft einführt.

Zunächst haben wir das 0-System, wo wir uns die Auflagerkraft wegdenken und uns eine Virtuelle verschiebung hinmalen. Hier müssen wir den Momentenverlauf berechnen.

Dann, haben wir das 1-System, wo wir dann alle Realkräfte wegdenken und da wo wir die Verschiebung berechnen wollen die Gesuchte Kraft $X_1$ einführen. Davon berechnen wir ebenfalls den Momentenverlauf.

Wir stellen die sogenannte "Kompatiblität auf", wo wir die Verschiebung $f_{10}$  ohne Kraft + Verschiebung $f_{11}$ in Abhängigkeit von $X_1$ rechnen. Dies müssen wir dann wieder = 0 setzen, weil wir ja aufgrund einer Lagerreaktion keine Verschiebungen haben.

Die Indiziereung kommt so zurstande, dass es die verschiebung $f_1$ am 0-System = $f_{10}$ und verschiebung 1 am 1-System = $f_{11}$

##### Vorgehensweise

![[IMG_A7E44A35821B-1.jpeg]]

man berchnet sich wieder beide Momentenverläufe und überlagert diese mit dem Superpositionsprinzip.

![[IMG_C34FA60896BF-1.jpeg]]

Dadurch kriege ich meine verschiebung $f_{10}$ heraus aus dem 0-System heraus.

Um jetzt die verschiebung des 1-Systems herauszufinden, kann ich ganz einfach die Verschiebung des 1-Systems $f_{11}$ mal die gesuchte größe $X_1$ und schon habe ichs.

Nun Addiere ich die beiden verschiebungen und setze diese = 0.

Dann kann ich easy nach $X_1$ auflösen und fertischhhhhhh

Wenn ich jetzt noch den Momentenverlauf berechnen möchte, geht das folgendermaßen:

![[IMG_4958044630A3-1 2.jpeg]]

Viel cooler so oder? Yeeesss haha