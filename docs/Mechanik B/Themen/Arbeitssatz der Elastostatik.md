# 9. Arbeitssatz der Elastostatik

Das letzte mal haben wir erstmal gelernt was Arbeit usw ist und uns den [[Arbeitssatz der Statik|Arbeitssatz der Statik]] angeguckt. Damit ein Weg gefunden, wie wir mit der [[Arbeitssatz der Statik#^c052f1|Prinzip der virtuellen Verrückung]] eine Methode gefunden, wie wir unbestimmte Systeme lösen können.

Diesmal witmen wir uns mal dem **Arbeitssatz der Elastostatik** mit dem wir jedes beliebige unbestimmte System lösen können

wir betrachten folgendes System:

![[IMG_00737CEF5D63-1.jpeg|300]]

Ein balken, dass oben eingespannt ist. Außerdem wirkt eine Kraft (in dem Fall eine Normalkraft F).. dementsprechend will der Balken auch um **"u"** länger werden.

Bevor wir das ganze angehen, ist es wichtig, dass wir zunächst mal bisschen was aus der Vergangenheit herauskramen:

![[IMG_4021D1028018-1.jpeg]]

Diese Relation brauchen wir nachher nochmal wenn wir anfangen mit der Arbeit der äußeren Kräfte.

Wir bringen das A auf die andere Seite und erhalten:

![[IMG_4E9CAFE1FEA1-1.jpeg|400]]

<mark style="background: #FFB86CA6;">Wir stellen fest dass der Zusammenhang ein linearer Zusammenhang ist, weil wir hier in der technischen Mechanik sehr kleine verschiebung und sehr kleiner verdrehung haben. </mark> 


### (I) Arbeit der äußeren Kräfte [W]

Okay schauen wir uns dann mal die Arbeit (W) äußeren Kräfte an :DD

Wir haben gelernt, dass man Arbeit berechnet mit: $$\fbox{$W = \int \limits_{0}^{u} F du$}$$

Machen wir dass dann doch mal :DD

![[IMG_3E11B2D7D5AE-1.jpeg|600]]

Wir setzen quasi für unser F das vorhin bestimmte F ein. Allerdings müssen überall wo u steht, $\tilde{u}$ einsetzen, weil das normale u unsere Integrationsgrenze schon ist.

Ja dann integrieren wir einfach und rechnen obere Grenze - untere Grenze.

in das $\frac{EA}{2l}u^2$ setzen wir für das u^2, die Formel für das F umgestellt nach u ein. 

wir können bisschen kürzen und erhalten:

![[IMG_6C0982CBA930-1.jpeg]]

Weil wir bereits gesagt haben, dass wir hier einen linearen Zusammenhang haben, dann ist es ja klar, dass die Arbeit auch Linear ist.

Das können wir auch grafisch darstellen:

![[IMG_EFE70BEFCF1F-1.jpeg]]

wir haben einen linearen Graphen weil wir ja einen linearen Zusammenhang haben.

Das grüne beschreibt die Arbeit.. also das was wir gerade berechnet haben.

es gibt auch das rote... die sogenannte <mark style="background: #FF5582A6;">**"konjugierte Arbeit $W^*$"**</mark> 

Wir können wieder aufgrund unsere erkenntnis, dass wir einen Linearen zusammenhang haben sagen, dass W und W* gleich sind.

Der Einzige Unterschied ist die abhängigkeit der beiden und somit auch nachher der untershcied nach welcher Variable wir integrieren.... 

Beim grünen haben wir eine Funktion in abhängigkeit von u und Integrieren dann auch nach u

Beim roten hingegen, hätten wir eine Funktion in abhängigkeit von F und würden nach F integrieren.

### Arbeit für Momente :
![[IMG_57D11AAACE0B-1.jpeg]]

Das gleiche gilt übrigens auch für Momente ^^ können wir skippen :DD

### (II) Arbeit der inneren Kräfte [$W^{int}$]
Die interne Arbeit ist eigentlich nichts anderes, als das [[Arbeitssatz der Statik#^244e0b|Potenzial]] wie wir gleich sehen werden

schauen wir uns mal ein mini Stück von dem Balken an:

![[IMG_048C26646530-1.jpeg|400]]

Verlängerung ist ja die länge mal die Dehnung $\epsilon$... hier indem fall möchte sich der inf. Balken auch aufgrund der wirkenden Normalkräfte Dehnen.

$W^{int}$ berechnen wir wie folgt:

![[IMG_D325C1A314DF-1.jpeg]]

für $W^{int}$ können wir natürlich die uns bereits berechnete Formel für W hernehmen... also <mark style="background: #FFB8EBA6;">0,5 mal Kraft (N) mal verschiebung (du)</mark> 

wir haben ja schon du berechnet.... diesen Wert können wir natürlich einsetzen.

Das $\epsilon$ können wir auch schon einsetzen, indem wir die ganz oberste Formel nach $\epsilon$ umformen :DD

Somit haben wir unser $W^{int}$... nur für ein Stück.... also gilt mal wieder: wir müssen integrierennnn :DD

![[IMG_1CE9DB3CD60F-1.jpeg]] ^b78c1d

wir setzen das ausgerechnete dW^{int} in das Integral. Da garnichts davon von x abhängt, können wir es vor das Integral ziehen... somit Intgerieren wir die Zahl eins also hängen wir die Integrationsvariable einfach hinten dran :DD

Obere und untere grenze eingesetzt, kommt dann das blau umrahmte raus.

Wir sehen direkt, dass es dasselbe ist wie die Arbeit der äußeren Kräfte also W...

Verglichen mit der Arbeit der Äußeren Kraft, ist es das **Arbeitssatz der Elastostatik**

### Formveränderungsenergie (FÄE) in prismatischen Stäben

Wir kennen nun den Arbeitssatz der Elastostatik und der besagt, dass das Potenzial $\pi$ gleich die verrichtete Arbeit W bzw. $W^{int}$ ist.

nun führen wir ein volumenspez. FÄE $\pi_v$ bzw. das konjugierte FÄE $\pi_v^*$ ein.

Wir nutzen dieses $\pi_v$ bzw. $\pi_v^*$, als vereinfachung für unser tatsächliches Potenzial $\pi$ bzw $\pi^*$

Wir berechnen das folgendermaßen:

![[IMG_C09C81950099-1.jpeg]]

Analog zur Arbeit können wir das Potenzial auch in einem Diagramm darstellen:

![[IMG_01EA408EF5BF-1.jpeg]]

links haben wir wieder wie oben ein Diagramm, wo wir unterhalb des Graphen diesmal das Potenzial $\pi$ und oberhalb des Graphen das konjugierte Potenzial $\pi^*$ beschreiben.

Wir können zwar $\pi$ und $\pi^*$ darstellen..... wir können aber auch hingehen und  $\pi_v$ und $\pi_v^*$ in einem Diagramm darstellen wie das rechts gemacht wurde.

Ob ich jetzt das Rote oder das Grüne betrachte ist wie bei der Arbeit egal. Wichtig ist nur dass ich beim Roten nach $\sigma$ integriere und beim grünen nach $\epsilon$ Integriere sodass sich folgende Formeln ergeben:

![[IMG_BAB47BDA9B88-1.jpeg]]

Das war jetzt sehr Allgemein.... Nun müssen wir uns die Beanspruchung durch Normalkraft, Querkraft, Moment und Torsionsmoment anschauenn :DD

### Beanspruchung durch Normalkraft N:

Schauen wir uns hier mal folgende Situation an:

![[IMG_23BDAF0CAC33-1.jpeg|400]]

Wir haben hier einen Zug- und Druckstab und schauen uns wieder einen inf. kleines Stück an. Zunächst wurde die Normalkraft die links und rechts wirkt, ersetzt als Spannung. Klar wenn links und rechts das inf. kleine stück sich verlängern möchte, ist die Länge dann dx (eigentliche Länge) + du (verschiebung).

Um $\pi$ zu berechnen, brauch ich ja $\pi_v$.. also:

![[IMG_5A20BAF85300-1.jpeg]]

\sigma_x haben wir hier einfach durch  $E \cdot \epsilon$ ersetzt. Wir Integrieren und setzen wieder die obere und untere Grenze ein.

Nun können wir das Potenzial berechen, indem wir das volumenspez. Potenzial Integrieren:

![[IMG_4F811B7F94AC-1 2.jpeg]]

Wir integrieren nach dem Volumen... also ein doppeltes Integral erst über die Querschnittsfläche, dann über die länge.

Somit haben wir uns dann ein \pi berechne, was aber in Verzerrung formuliert ist.

Problem: Viel zu kompliziert :DD

Und jetzt kommt der Plottwist... wir berechnen uns nicht das $\pi$ sondern das $\pi^*$

dazu brauchen wir dann auch einen $\pi_v^*$ was wir dann Integrieren können um $\pi^*$ zu berechnen.

Diesmal benutzen wir die andere Formel: 

![[IMG_ACAC9B0B7C8D-1.jpeg]]

jetzt können wir das auch wieder nach Volumen integieren:

![[IMG_1DC8DC5F103F-1.jpeg]]

die 0,5 können wir direkt als Konstante eh ganz an den Anfang ziehen.

Das $\pi^*$, ist eine konstante und deswegen zieht man es vor die innere Ableitung.

Dann tut man es integrieren und erhält:

![[IMG_CFB4DD41B1AB-1.jpeg]]



### Beanspruchung durch Moment  M = My

Wir betrachten wieder einen kleinen abschnitt eines Balkens:

![[IMG_4B12656D6ED8-1.jpeg]]

klar links und rechts wirken dann momente..

die verschiebung u ist der negative Winkel (-$\beta$) mal z.

Druch [[Biege-normal-spannung#^63736b|Normale bleibt Normale]] ist $-\beta = w'$

Dann brauchen wir noch die Balkenkinematik:

![[IMG_CF1A7FDD0DD7-1.jpeg]]

Auch hier könnten wir uns wieder das $\pi$ anschauen... da käme aber auch wieder was kompliziertes Raus, deswegen schauen wir uns direkt das $\pi^*$ an.

![[IMG_1CFB31679EA4-1.jpeg]]

Wir Integrieren quasi wieder die Dehnung nach der Spannung. Die Dehnung ist ja gleich $\frac{\sigma_x}{E}$. Da wir bereits ein $\sigma_x$ haben, kommt beim Integral irgendwas mit $\sigma_x^2$ heraus. Das \sigma_x können wir jetzt mit der Formel der [[Biege-normal-spannung|Biege-normal-spannung]] ersetzen und erhalten:
### Beanspruchung der Querkraft Q = Qz
Zunächst mal wieder bisschen Stoffgesetz:

![[IMG_51B00B4E6A37-1.jpeg]]

Wir können unsere QUerkraft auch darstellen als:

![[IMG_D56ACF7E12E3-1.jpeg]]

Man stellt das über das $\tau_M$ dar, weil es mal wieder einfacher ist als wenn nicht :DD

zunächst müssen wir wieder das \pi berechnen:
![[IMG_C867B3D0D2CA-1.jpeg]]

Da wir diese komplizierte Darstellung aber nicht mögen, stellen wir das als $\tau_M$ da
![[IMG_DE06526E0B1E-1.jpeg]]

jetzt haben wir unser $\pi_M$ und unser $\pi$. Das Problem ist, dass $\pi_M$ einen Korrekturfaktor \kappa enthält. Dieser muss so gewählt sein, dass $\pi_M$ und unser $\pi$ gleich sind:

also muss gelten:

![[IMG_DFC13050F319-1.jpeg]]

Das können wir dann so berechnen:

![[IMG_4A2F484C7AF0-1.jpeg]]

### Superposition für FOrmänderungsEnergie für Balken

Jetzt können wir alles was wir haben zusammenführen:

![[IMG_05C9737F6EBE-1.jpeg]]