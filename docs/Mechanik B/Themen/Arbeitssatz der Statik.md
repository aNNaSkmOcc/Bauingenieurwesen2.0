# 8. Arbeitssatz der Statik

### Arbeit einer Kraft

Zunächst einmal müssen wir den Begriff "Arbeit" in der Mechanik verstehen.

Mechanische Arbeit brauchen wir deswegen, um zu messen, wie groß der Energieaufwand ist den wir reinstecken um ein Objekt zu bewegen.

Schauen wir uns mal folgende Situation an:

![[IMG_38E75FF0D8B1-1.jpeg]]

Wir haben hier zunächst mal einen materiellen Punkt auf einer beliebigen Strecke, der uns ein Objekt beschreibt

Außerdem haben wir Ortsvektoren r, die den Startpunkt, materiellen Punkt und den Endpunkt beschreiben.

Nun wirkt eine Kraft F auf diesen materiellen Punkt. Dieser bewegt sich um dr.

Um die Arbeit W zu berechnen gibt es 2 fälle:

![[Bildschirmfoto 2022-05-30 um 14.40.10.png|400]]

Übertragen auf unser beispiel, wirkt die Kraft nicht mit unserer kleinen Bewegungsrichtung dr überein... deswegen benutzen wir dir Formel mit Cosinus, die sogenannte **inkrementielle Arbeit**

<mark style="background: #FF5582A6;">Anmerkung: dW = 0 ⟺ F ⊥ dr </mark> 

Wir wollen natürlich die Arbeit über die  gesamte Strecke berechnen also was könnte man machen? genauuu Integrieren :)

![[IMG_291DF32E090D-1.jpeg]]

Die einheit dafür ist Nm oder auch Joule :)

##### Beispiel 1:

![[IMG_604B99E64397-1.jpeg|300]]

Wir sollen jetzt die aufgewendete Arbeit berechnen:

Dazu stellen wir erstmal die Gleichung auf:

![[IMG_880BF1C8BC50-1.jpeg]]

Der Vektor W geht von 0 bis eine beliebige stelle s. Das können wir jetzt einmal für die Kraft G1 und Kraft G2 machen und zusammenaddieren.

![[IMG_E075CBFC7531-1.jpeg]]

Nun können wir die Werte einsetzen

Außerdem wurde der Teil mit G2 auch in parallel und senkrecht aufgeteilt, weil wir die Kraft G2 in diese aufteilen.

Beim Teil mit G1, kommt als Winkel 0 grad hin, weil die ja straight in s richtung geht.

Bei $G_{2||}$ kommt als Winkel auch 0, weil die Komponente ja auch in s richtung zeigt.

Bei $G_{2⊥}$ allerdings, kommt als Winkel für den Winkel 90 hin, weil diese Komponente senkrecht zu s ist.

Weil cos(0°) ja 1 ist kann man das wegkürzen.

Außerdem kann man die Komponente wo die 90° steht auch wegstreichen, weil dort die Wd 0 ist.

---

### Arbeit eines Moments

Arbeit eines Moments kann man so vorstellen, dass man einen Schraubenzieher Dreht und diese Angewendete Kraft misst.

Die Arbeit eines Moments ist aber analog zur Arbeit einer Kraft:

![[IMG_70CEF42A2065-1.jpeg]]

---


### Arbeit einer konservativen Kraft
Zunächst einmal müssen wir klären, wass den eine **konservative Kraft**

eine konservative Kraft ist eine Kraft, die konstant <mark style="background: #FFB86CA6;">die ganze Zeit Konstant</mark> bleibt.

Quasi wenn wir eh wissen, dass die Kraft konstant bleibt, können wir sie auch jedes mal vor das Integral ziehen.

Eine Aufgabe mit einer konservativen Kraft berechnen wir wie folgt:

![[IMG_D33496058D97-1.jpeg]]

Also wir stellen wieder unser Integral auf... diesmal ist F ja konstant und wir ziehen ihn deswegen vor das Integral.

dementsprechen müssen wir das Integral von 1 bilden.. das ist dann einfach die variable nach der wir Integrieren wollen selbst.

schließlich setzen wir da die Grenzen ein und Klammern das F aus. 

das ($r_E - r_A$) ist ja nichts anderes als unsere verschiebungsmatrix. Deswegen ersetzen wir diesen Ausdruck durch den Buchstaben u

die Arbeit einer konservativen Kraft hat allerdings auch einige Konsequenzen.

1. Die Arbeit ist wegunabhängig
2. Wenn Anfangspunkt und Endpunkt gleich sind, dann ist $\oint dW = 0$
3. Ist der Anfangspunkt bei 0, so ist $W = F \cdot r$

##### Beispiel 2
Schauen wir uns wieder ein Beispiel an:

![[IMG_C6779C3FD52F-1.jpeg]]

Hier haben wir wieder ein Objekt was um h nach unten fällt :)

Wir haben wieder eine Strecke mit Startpunkt A und Endpunkt B

wie berechnen wir das jetzt ? ja wieder wie folgt:

![[IMG_FBB734D76D52-1.jpeg]]

Auch wieder hier (Kraft mal StreckeAnfang) - (Kraft mal StreckeEnde)

Wir setzen für das G und das r unsere Werte ein.

Wir stellen fest, dass das <mark style="background: #FF5582A6;">$e_x$ und $e_z$</mark> und <mark style="background: #FF5582A6;">$e_y$ und $e_z$</mark> senkrecht zueinander sind und somit 0 ergeben und wegfallen.

Am Ende bleibt nur noch das $-G z_E$ übrig.

Das Gleiche dann auch mit $-G z_A$, sodass man wieder das G ausklammern kann.

Diesmal haben wir keine verschiebung u, sondern eine verschiebung über die höhe h.

Dementsprechend lautet das Ergebnis: mgh aka. Potenzielle Energie. ^2b41bf


### Potenzial

^244e0b

Was ist Potenzial? Potenzial ist einfach die gespeicherte Energie in einem Objekt.

Die konservative Kraft, lässt sich über aus Potenzial $\pi$ ableiten

![[IMG_6CB47FAE2EB8-1.jpeg]]

schauen wir uns direkt mal ein Beispiel an:

![[IMG_97578AB3B353-1.jpeg]]

Das Potenzial kann man aber noch besser anhand der hookschen Feder zeigen:

![[IMG_A176E424DB8C-1.jpeg]]

Zunächst einmal müssen wir wissen, dass das Federgesetz F = c mal u ist.

Um das W zu bestimmen, intregrieren wir nach du. das F können wir ersetzen durch unser c * u.

Dann kriegen wir für das W quasi raus das $-\frac{1}{2} \cdot cu^2$

Das Potenzial ist ja -W, also $\frac{1}{2} \cdot cu^2$, die negative Ableitung nach u ergibt dann wieder -cu passt alsloooo




### Arbeitssatz
Der Arbeitssatz erlaubt uns statisch Unbestimmte zu lösen.

Dieser besagt, dass 

![[IMG_09F951249158-1.jpeg]]

= 0 sein muss.

das $\delta u$ und das $\delta \phi$ sind:
- **nur gedacht**
- möglichst klein
- und geometrisch zulässig

Den Arbeitssatz können wir uns nun zurnutze machen. Dieses zurnutze machen, um damit Lagerreaktionen zu rechnen, nennt sich auch **Prinzip der virtuellen Arbeit**

---

### Prinzip der Virtuellen Arbeit

^c052f1

Wir machen uns quasi jetzt das Arbeitsgesetz zur nutze und rechnen damit Lagerkräfte aus :)

![[IMG_A7B412585D2E-1.jpeg]]

wir stellen direkt Fest, dass das System statisch unbestimmt ist :)

Wir wollen das Auflager B berechnen

![[IMG_27D134992F25-1.jpeg]]

wir entfernen das Auflager und klar wenn das Auflager da weg ist tut sichs verschieben. Wir dürfen die Richtung aber aussuchen.

![[IMG_246247BCEB91-1.jpeg]]

Da wir sonst wieder das Problem haben, dass wir wieder zwei umbekannte haben, müssen wir das alles versuchen durch eine Unbekannte darzustellen mtittels Strahlensätze

![[IMG_11EA528F6A0A-1.jpeg]]