

## 1. Dioden / LEDs
1. Eine LED mit $3.2V$ Vorwärtsspannung soll mit einer $9V$-Blockbatterie betrieben werden. Die LED ist für $20mA$ ausgelegt. Zeichne die Schaltung und bestimme einen passenden Vorwiderstand.
   1. Welche Leistung muss dieser Vorwiderstand mindestens aushalten können?
   2. Du hast dich vertan, die LED hat eigentlich eine Vorwärtsspannung von $5V$. Wie viel Strom fließt stattdessen?
2. Eine LED hat eine Vorwärtsspannung von $3.2V$, eine Andere $2.8V$. Beide LEDs werden parallel hinter einen gemeinsamen Vorwiderstand geschaltet. Welche der beiden LEDs leuchtet? Erkläre, warum nicht beide leuchten.
3. Wie verlaufen die Potentiale an den markierten Knoten in folgender Schaltung, wenn der Umschalter betätigt wird? (Kondensator zu beginn entladen)\
![](../assets/images/2025-08-03-12-35-59.png)
4. Die Diode ist ideal, hat also eine Vorwärtsspannung von 0V. Der Schalter wird zu beginn geschlossen und kurz danach wieder geöffnet. Wie verläuft der Strom durch die Induktivität (Zu beginn entladen)?\
![](../assets/images/2025-08-13-11-15-42.png)
   1. Wie verläuft der Strom, wenn die Diode nicht ideal ist?
   2. Welchen Einfluss hat die Vorwärtsspannung der Diode auf den Stromverlauf?
   3. Die meisten Schaltdioden haben eine Vorwärtsspannung von 0.7V. Wie könnte man trotzdem eine höhere Vorwärtsspannung erzeugen?
   4. Welches Problem könnte entstehen, wenn die (reale) Diode zu langsam ist?

## 2. MOSFET

Alle Transistoren in dieser Übung sind N-Kanal MOSFETs.

1. Ein ETechnik-Anfänger nutzt ein MOSFET (Treshold-Spannung $3V$, Kanalwiderstand gering), um seine Zimmerlampe ein- und auszuschalten:\
![](../assets/images/2025-08-20-11-03-04.png)\
Wieso funktioniert diese Schaltung nicht?
2. Gegeben ist folgende Schaltung, mit welcher eine Lampe ein- und ausgeschaltet werden kann:\
![](../assets/images/2025-08-20-10-53-09.png)\
Die MOSFETs sind **real** (nicht ideal). Der rechte MOSFET hat eine Treshold-Spannung von $5V$, der Linke $1.3V$.
Der linke Umschalter ist der Ausgang eines Mikrocontrollers, welcher entweder 0V, oder 1V ausgeben kann.\
Wieso benötigt die Schaltung 2 MOSFETs? Man könnte den Ausgang des uC ja auch direkt mit dem rechten MOSFET verbinden, oder?
3. Gegeben ist folgende Schaltung:\
![](../assets/images/2025-08-17-19-05-04.png)\
Der MOSFET hat eine Treshold-Spannung von $4V$, die Diode ist eine Zener-Diode mit $10V$ Rückwärtsspannung. Bestimme an jedem der 4 Knoten das Potential.
