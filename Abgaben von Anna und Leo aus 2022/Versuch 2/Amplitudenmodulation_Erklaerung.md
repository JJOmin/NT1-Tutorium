
# Erklärung zur Amplitudenmodulation (AM) mit Träger

## Grundlagen der Amplitudenmodulation
- **Trägersignal:** Das Trägersignal ist eine Sinuswelle mit hoher Frequenz \( f_c \). Es wird verwendet, um die Information des Nachrichtensignals zu „tragen“.
- **Nachrichtensignal:** Das Nachrichtensignal ist eine Sinuswelle mit niedriger Frequenz \( f_m \), die die eigentliche Information darstellt.

Die modulierte Welle entsteht durch Multiplikation der Amplitude des Trägersignals mit der Amplitude des Nachrichtensignals. Die allgemeine Formel für eine voll durchmodulierte AM-Welle ist:
\[
s(t) = A \cdot (1 + m \cdot \sin(2\pi f_m t)) \cdot \sin(2\pi f_c t)
\]
Hierbei bedeuten:
- \( A \): Maximale Amplitude des Trägersignals
- \( m \): Modulationsgrad, hier \( m = 1 \) (voll durchmoduliert)
- \( f_c \): Frequenz des Trägersignals
- \( f_m \): Frequenz des Nachrichtensignals

---

## Warum ist die Zeichnung so?
- **Frequenzverhältnis:** Die Trägerfrequenz \( f_c \) ist hier 10-mal so hoch wie die Nachrichtensignalfrequenz \( f_m \). Deshalb gibt es genau 10 Schwingungen des Trägersignals pro Periode des Nachrichtensignals.
- **Hüllkurve:** Das Nachrichtensignal (rote Linie) legt die Hüllkurve des modulierten Signals fest. Da \( m = 1 \), wird die Amplitude des Trägers vollständig zwischen \( 0 \) und \( 2A \) variiert.
- **Mathematische Multiplikation:** Die Amplitude des Trägers \( A \cdot \sin(2\pi f_c t) \) wird mit \( (1 + \sin(2\pi f_m t)) \) skaliert, wodurch die Sinus-Hüllkurve entsteht.

---

## Parameter \( A \) und \( m \) in der Zeichnung
- **\( A \):** Die maximale Amplitude des Trägers wird durch den höchsten Punkt der grünen Wellenlinie dargestellt (auf der vertikalen Achse als \( A \) markiert).
- **\( m \):** Der Modulationsgrad \( m = 1 \) bedeutet, dass die Amplitude des Trägers von \( 0 \) bis \( 2A \) reicht. Das sieht man daran, dass die modulierte Welle die Hüllkurve vollständig ausfüllt, ohne „Abstände“ dazwischen.

---

## Signalbestandteile in der Zeichnung
- **Grüne Linie:** Das modulierte Signal, das durch Multiplikation der Trägerwelle mit der Hüllkurve entsteht.
- **Rote Linie:** Die obere Hüllkurve, die direkt vom Nachrichtensignal kommt (\( 1 + \sin(2\pi f_m t) \)).
- **Blaue Linie:** Die untere Hüllkurve, die symmetrisch zum roten Signal verläuft (\( 1 - \sin(2\pi f_m t) \)).

---

## Fazit
Die dargestellte Kurve ergibt sich direkt aus der mathematischen Beschreibung der Amplitudenmodulation. Durch das Verhältnis \( f_c = 10 \cdot f_m \) gibt es 10 Trägerschwingungen pro Periode der Hüllkurve. Der Modulationsgrad \( m = 1 \) sorgt dafür, dass die Amplitude des Signals vollständig moduliert wird, wodurch die grüne Linie der roten (Hüllkurve) exakt folgt.
