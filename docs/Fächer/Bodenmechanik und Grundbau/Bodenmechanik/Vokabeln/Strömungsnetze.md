Strömungsnetze modellieren unseren Wasserstrom.

### Beispiel: Spundwand

wie könnte das denn genau aussehen? Schauen wir uns das doch mal an einen Beispiel an:

![[IMG_41E79444AB7C-1.jpeg]]

Relativ wüst oder ? HAHA schauen wir uns das aber mal Schritt für Schritt an:

Zunächst einmal haben wir die Randwerte die dann so ausschauen:

![[IMG_DBD6D0A82B60-1.jpeg]]

Die <mark style="background: #FF5582A6;">Stromlinien</mark> sind hier in rot markiert und die sogenannten <mark style="background: #ABF7F7A6;">Äquipotenziallinien</mark> sind in blau markiert.

Wir haben quasi schon unsere Randlinien... der Strom geht einmal entlang des Referenzniveaus und einmal entlang der Spundwand.

Nur bekanntlich, fließt der Boden nicht nur am Rand.. sondern im ganzen Boden.

Deswegen malen wir natürlich auch da Linien entlang, was dann so aussehen würde:

![[IMG_68694D310587-1.jpeg]]

Jetzt haben wir ja viele Linien nebeneinander... die Flächen zwischen zwei **Stomlinien** nennt sich der sog. **Stromkanal**

In diesem Beispiel hätten wir also 3 Stromkanäle.

Die Anzahl der Stromkanälen, wird mit dem Parameter $n_S$ beschrieben.

So würde das dann aussehen:

![[IMG_9E0E2CEF5989-1.jpeg]]

Nun kommt ein weiterer Schritt dazu, denn außerdem müssen wir die **Äquipotenziallinien** einzeichen 

Wichtig ist, dass wir diese Senkrecht zu den Stromlinien zeichnen und das sieht dann so aus:

![[IMG_0738C35CB6C5-1.jpeg]]

Die Anzahl der **Äquipotenziallinien** wird durch den Parameter **n_P** beschrieben und nennt sich **Potenzialstufen**

Jetzt wollen wir ja die Hydraulische Höhe entlang einer Stromline messen.

Dazu stecken wir überall wo eine **Aäquipotenziallinie** und **Stromlinie** sich kreuzen ein Röhrchen rein was dann so aussieht:

![[IMG_6F27671EE083-1.jpeg]]

Man sieht dass die Höhenunterschiede der einzelnen Rohre alle gleich sind. Um das zu berechnen, kann ich nun einfach hergehen und die Höhe $\Delta H$ nehmen welches den höhenunterschied zwischen den Wasserspiegeln beschreibt und einfach durch $n_p$ rechnen, welches die Anzahl der Potenzialstufen beschreibt.

Dann erhalte ich die größe $\Delta h$ was die unterschiede zwischen den höhen beschreibt.

Fassen wir das ganze doch einmal zusammen:

![[IMG_781E6A047571-1.jpeg]]
### Abschätzung des Volumenstroms
Jetzt haben wir zwar unser Strömungsnetz aufgestellt. Stellt sich nur die Frage, was wir denn daraus abschätzen könnten.

Ein wichtiger Kennwert wäre vielleicht, wie viel Wasser durch so ein Stromkanal fließt.

Das ermitteln wir mit folgender Formel :

![[IMG_5643E61DB4D8-1.jpeg]]

Die Kennwerte sind eigentlich bekannt :D 

Das k beschrieb den [[5. Wasser im Boden#^0be36e|Durchgangskoeffizienten k]]


### weiteres Beispiel
Schauen wir uns doch mal ein weiteres Beispiel an:

![[IMG_847C94B60CF9-1.jpeg]]

Hier haben wir ein sogenannten Betonwehr. Allerdings ist da jetzt eine Spundwand drinne.... allerdings stellt sich hier die Frage wofür mache ich das denn? Naja aus einem ganz einfachen Grund:

Die Spundwand sorgt nämlich dafür, dass ich die Potenziallinien sich halbieren und immer zwei daraus machen. Dementsprechend verdoppeln sich unere Potenzlialstufen.

Das hat den effekt, dass dann der Volumenstrom kleiner wird :D 