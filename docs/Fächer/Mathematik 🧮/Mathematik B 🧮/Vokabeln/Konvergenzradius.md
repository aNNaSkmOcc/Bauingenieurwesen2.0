# Konvergenzradius

Der Konvergenzradius ist in der Analysis eine Eigenschaft einer Potenzreihe die angibt, in welchem Bereich der Potenzreihe Konvergenz garantiert ist.

Aber wie ermittelt man den Konvergenzradius ? Entweder mit dem [[Wurzelkriterium]] (Wenn wir entweder irgendwas mit hoch k haben oder ein Polynom) und mit dem [[Quotientenkriterium]] wenn wir irgendwas mit Fakultäten haben. Wichtig ist, dass wir uns nur das $a_k$ anschauen.

![[IMG_9C55299A89EE-1.jpeg]]

Hier schaut man was man für $\alpha$ rausbekommt. Wenn eine 0 rasukommt ist direkt beste, weil dann konvergiert die Potenzreihe auf ganzem Definitionsbereich.

![[IMG_42202E5DA10B-1.jpeg]]

Hier wieder dasselbe, hier macht man einfach straight das Quotientenkriterium und guckt was man für $\beta$ rausbekommt. Wenn 0 rauskommt ist wieder beste, weil dann ist einfach der Konvergenzradius ganzer Definitionsbereich.

##### Beispiel 1:
$$\sum \limits_{k=1}^{\infty} \frac{k^k}{k!} \cdot x^k$$

Hier haben wir fast die Form einer Potenzreihe. mann kann auch $(x-0)^k$ schreiben. Der Entwicklungspunkt ist also die 0

Da wir hier jetzt also eine Fakultät haben, benutzen wir das [[Quotientenkriterium]].

Dann sollten wir folgendes erhalten:

$$\sum \limits_{k=1}^{\infty} |\frac{(k+1)^{(k+1)}}{(k+1)!} \cdot \frac{k!}{k^k}|$$

da wir wissen, dass die Reihe größer als 0 sein wird, können wir das auch weglassen.

Ja wenn wir das alles auflösen diesdas erhalten wir:

$$(1+\frac{1}{k})^k$$

Wenn wir das jetzt gegen $\infty$ laufen lassen, erhalten wir $e^k$

$e^k$ ist eindeutig größer als 0, also ist unser Konvergenzradius bei $\frac{1}{e^k}$ um den Entwicklungspunkt 0 :)

---



Was ist denn, wenn wir den Konvergenzradius zweier Potenzreihen untersuchen müssen ? Das geht :) Auch bei den Potenzreihen haben wir ein paar regeln:

![[IMG_ABF63EEDACE4-1.jpeg]]

##### Beispiel 2:

![[IMG_02D53DEA84C1-1.jpeg]]

