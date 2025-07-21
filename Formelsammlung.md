
# Allgemein
## Integrale, Ableitungen
- Ist $a(t)$ konstant, gilt $\int{a(t)}dt = a*t$
- Ist die Änderung von $a(t)$ konstant, gilt $\frac{da(t)}{dt} = \frac{a(t_2) - a(t_1)}{t_2 - t_1}$ für beliebige Zeitpunkte $t_1 \neq t_2$
  - (Praxisrelevanter) Ist zusätzlich $a(t_1) = 0$, gilt $\frac{da(t)}{dt} = \frac{a(t)}{t}$

## Komplexe Zahlen

### Katesisch
$z = x + jy$
- $x = Re\{z\}, y = Im\{z\}$
- Imaginäre Einheit $j² = -1$
  - $\frac{1}{j} = -j$
- Konjugiert $\overline{z}=z^*=x-jy$
  - $\overline{z}$ ist das "konjugiert-Komplexe" von $z$.
- Betrag $|z|=\sqrt{x²+y²}=\sqrt{z \overline{z}}$
- Teilen durch eine komplexe Zahl: Mit konjugiertem Nenner erweitern, dann wird der Nenner reell

### Polar
$z = r e^{j \varphi}, w = R e ^{j \psi}$
- $r = |z|, R = |w|$
- $\varphi = arg\{z\}, \psi = arg\{w\}$

- Multiplizieren: $zw = rR e^{j (\varphi + \psi)}$
  - "Betrag multiplizieren, Winkel addieren"
- Dividieren: $\frac{z}{w} = \frac{r}{R} e^{j (\varphi - \psi)}$
  - "Betrag dividieren, Winkel subtrahieren"

### Umwandlung
- $arg\{z\} = \begin{cases}
  \pi, y = 0 \text{ und } x < 0\\
  2 * arctan \frac{y}{|z| + x}, sonst
\end{cases} = arctan2(x,y)$
  - In der Praxis ist diese Umwandlung nicht nötig. Falls doch, einfach mit normaler Trigonometrie arbeiten

- $x = r*cos(\varphi)$
- $y = r*sin(\varphi)$

## Einheitenpräfixe
|Präfix|Gesprochen|Faktor|
|--|--|--|
|T|Terra|$10^{12}$|
|G|Giga|$10^9$|
|M|Mega|$10^6$|
|k|kilo|$10^3$|
|-|-|$10^0=1$|
|m|milli|$10^{-3}$|
|$\mu$ (u)|mikro|$10^{-6}$|
|n|nano|$10^{-9}$|
|p|pico|$10^{-12}$|

# Grundlagen
## Widerstandsnetze
- Ohm'sches Gesetz: $U=R*I$
  - $[U] = V = Volt$
  - $[I] = A = Ampere$
  - $[R] = \Omega = Ohm$
- Reihenschaltung: $R_{ges} = R_1 + R_2 + ...$
- Parallelschaltung: $\frac{1}{R_{ges}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$
  - Bei 2 Widerständen: $R_{ges} = \frac{R_1 * R_2}{R_1 + R_2} $
  - Bei gleichen Widerständen: $R_{ges} = \frac{R_{teil}}{n}$
- Spannungsteiler: $\frac{U_1}{U_2} = \frac{R_1}{R_2}$
  - Praxisrelevanter: $\frac{Teilspannung}{Gesamtspannung} = \frac{Teilwiderstand}{Gesamtwiderstand}$

## Kirchhoff
- "Alle Ströme die in einen Knoten hinein fließen, fließen auch wieder raus"
  - "Alle Ströme die in ein Bauteil (oder Teilnetz) fließen, fließen auch wieder raus"
- "Potentiale an einem Knoten sind überall am Knoten gleich"

## Leistung/Energie
- Leistung: $P = U*I$, bzw. $p(t) = u(t) * i(t) = \frac{dE(t)}{dt}$, $[P] = W = Watt$
  - Leistung an Widerstand: $P = R*I² = \frac{U²}{R}$
- Energie: $E = \int{p(t)}dt$, $[E] = J = Joule$
  - $1 kWh = 3'600'000 J$

## Wechselspannung
- Allgemein: $u(t) = û*sin(\omega t + \varphi)$
- Kreisfrequenz: $\omega = 2 \pi f$
  - Frequenz $[f] = Hz = Hertz = \frac{1}{s}$
- Effektivwert: $U = \sqrt{\frac{1}{T} \int_{t_0}^{t_0 + T}u²(t)} dt$
  - Bei Gleichspannung: $U = u(t)$
  - Bei sinusförmiger Spannung: $U = \frac{û}{\sqrt{2}}$

# Kapazität/Induktivität

## Kapazität
- Kapazität: $[C] = F = Farad$
- Strom: $i = C \frac{du}{dt}$
  - Bei $C = 1F$ und $i = 1A$ steigt die Spannung um $1V$ pro Sekunde.
- Spannung: $u = \frac{1}{C} \int{i}dt$
- Energie in Kapazität: $E = \frac{1}{2} CU^2$
- Blindwiderstand $X_C = \frac{1}{j\omega C} = -j \frac{1}{\omega C} = \frac{1}{sC}$

### Lade-/Entladekurve
$\tau = R*C$

|Dauer|Lade/Entladestand|
|---|---|
|$1 \tau$|63 %|
|$2 \tau$|86 %|
|$3 \tau$|95 %|
|$4 \tau$|98 %|
|$5 \tau$|99 %|

## Induktivität
- Induktivität: $[L] = H = Henry$
- Strom: $i = \frac{1}{L} \int{udt}$
- Spannung: $u = L\frac{di}{dt} $
  - Bei $L = 1H$ und $u = 1V$ steigt der Strom um $1A$ pro Sekunde.
- Energie in Induktivität: $E = \frac{1}{2} LI^2$
- Blindwiderstand $X_L = j\omega L = sL$








