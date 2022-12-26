### Allgemeines
Bei der [[4. Verkehrserzeugung|Verkehrserzeugung]] und der [[5. Verkehrsverteilung|Verkehrsverteilung]] habe ich quasi die Prognose Fij Matrix berechnet, die die Quell und Zielverkehre für den gesamten Verkehr abbildet.

In der Verkehrsaufteilung, soll es nun darum gehen, dass ich denn gesamten Verkehr in seine einzelnen Verkehrssyyteme Aufteile.. ich möchte abschätzen können, wer welches Verkehrssystem benutzt.

Quasi, möchte ich verschiededene Fij-Matritzen haben... z.B eine Fij matrix für PKW, eine für ÖPNV usw usw.

Bei der Verkehrsaufteilung, beschränken wir uns dabei natürlich nur auf den Personenverkehr.

Diese könnten sein:

- **Nicht motorisierter Individualverkehr:**
	- Fußgänger
	- Radfahrer

- **Motorisierter Individualverkehr:**
	- Kraftfahrzeuge

- **Öffentlicher Personenverkehr:**
	- Bus
	- Bahn
	- Taxi

### 1. Schritt Aufteilung des motorisierten und nicht motorisierten Verkehrs.
schauen wir uns doch mal an, genau ich das denn jetzt mache.... wie genau, teile ich den Verkehr denn auf ? 

Zunächst einmal, teilen wir den Verkehr in mororisierten und nicht motorisierten Verkehr. Dies könnte beispielsweise so aussehen:

![[Bildschirm­foto 2022-11-05 um 11.16.31.png]]

>💡wichtig sei gesagt, dass zu dem Nicht motrosierten Verkehr nur Fahrrad oder Fahrrad gilt.

### 2. Schritt: Aufteilung in IV(Individualverkehr) und ÖV(Öffentlicher Verkehr)

Wenn wir nun den nicht-motorisierten Verkehr von dem Gesamtverkehr abgezogen haben, wollen wir nun den motorisierten Verkehr in IV(Individualverkehr) und ÖV(Öffentlicher Verkehr) aufteilen.

Wir können ganz leicht den ÖV-Anteil des Gesamtverkehrs wie folgt abziehen:

![[Bildschirm­foto 2022-11-05 um 11.24.12.png]]

Was passiert hier ? wir berechnen das Verhältnis Öffentliches Verkehr zum Gesamtverkehr.
jetzt wurden hier aber keine Einflussgrößen usw. berücksichtigt.

### Verschiedene Modellklassen
[[konventionelle Modal-Split Modelle]]

[[Logit Modell]]

---

Hier noch ein Paar wichtige Punkte, zum Modal-Split:

>💡Modelle des Modal-Split, müssen der Realität immer gerecht sein.

>💡Rechnung erfolgt in der Regel getrennt nach Fahrtzwecken

