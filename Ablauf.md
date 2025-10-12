
### Der Ablauf enthält nur Notizen für mich
Es könnte also sein, dass er nicht ganz so hilfreich ist, wie du erwartest.
Du kannst ihn trotzdem zur groben Orientierung nutzen.

### Vorsicht
Ich neige dazu, vom Ablauf abzuweichen.
Die Themen bleiben die Selben, nur kommen mal Punkt dazu, oder verschwinden.


## 0. Organisatorisches
- Einmal die Readme.md durchgehen

Antworten des Fragebogens besprechen
- BJT kannte niemand
- "Die gefährlichsten Selbsteinschätzungen"
- Kaum Schüler dabei

## 1. Grundlagen
### Ohmsche Widerstandsnetze
- Strom, Spannung und Widerstand (Beispiel Druckluft)
  - Ohmsches Gesetz
  - Ideale Quellen
- Parallel- und Reihenschaltung (Zusammenfassen von Widerständen)
  - Vereinfachte Formel: "mal durch plus"
- Spannungspotential
  - Reihenschaltung von Spannungsquellen/Stromquellen
- Kirchhoffsche Gesetze, besonders in Bezug aufs Potential
  - "Strom der in ein Bauteil fließt, fließt auch wieder raus"
  - "Unabhängig vom Weg des Stroms, das Potential an jedem jeweiligen Knoten ist am gesamten Knoten gleich"
- Übung 1.1
*Stand Einheit 1*
- Spannungsteiler
  - "Hoch- und Runterziehen" von Spannungen
  - "Teil / Gesammt = Teil / Gesammt"
- Übung 1.2

### Leistung, Energie
- Unterschied/Zusammenhang von Leistung und Energie (Beispiel Wasserfluss)
- "Grafisch integrieren/ableiten"
- Elektrische Energie
- Übung 1.4

### Wechselspannung
- Kurze Wiederholung des Sinus
  - Winkel-Einheit
- Parameter einer Sinus-Spannung\
*Ende Einheit 2*
- Effektivwert
- Übung 1.3

## 2. Kapazität, Induktivität
### Kapazität
- Was ist Kapazität?
  - Größe der Kapazität
  - Physik dahinter (Auch Dielektrikum)
- Zusammenhang zwischen Strom und Spannung
- Kapazität als Energiespeicher
- Ladekurve
- Kapazität an Sinusspannung
- Parasitäre Kapazitäten
- Arten von Kondensatoren
  - Auf LCSC anschauen\
*Stand Einheit 3*
- Ladekurve (Tabelle)
- Reihen-/Parallelschaltung
- Energie im Kondensator
- Übung 2.1

### Induktivität
- Induktion
- Selbstinduktion
  - Das Magnetfeld durch anderen Leiter abbauen (Trafo)
  - Sättigung
- Zusammenhang zwischen Strom und Spannung
  - "Trägheit" des Stroms
    - Induktivitäten ausschalten
    - Snubber-Kapazitäten
- Energie in einer Spule
- Parasitäre Induktivitäten
- Prinzip eines Schwingkreises
- Reihen-/Parallelschaltung\
*Stand Einheit 4*
- Übung 2.2

## 3. Komplexe Größen (Vorerst übersprungen)
### Komplexe Zahlen
#### Katesische Darstellung
- Zahlenebene
- Imaginäre Einheit j
- Addition, Subtraktion
- 1/j = -j
- Division durch Erweitern mit komplex Konjugiertem
- Betrag
- Wurzeln aus negativen Zahlen

#### Polardarstellung
- Betrag, Winkel
  - Euler-Schreibweise
  - Winkel-Schreibweise
- Multiplikation, Division
- Umrechnen in kartesische Darstellung

## 4. Komplexe Wechselstromrechnung und passive Filter (Vorerst übersprungen)
### Impedanznetze
- Komplexe Drehzeiger
  - Frequenz weglassen, wenn alle Frequenzen gleich sind
- Blindwiderstand
- Impedanz
- Berechnung von Impedanznetzen
- Scheinleistung, Blindleistung, Wirkleistung
  - Leistungsfaktor
- Übung 4.1

### Filter


## 5. Halbleiter
- Allgemeine Anforderungen an Schalter (Strom, Spannung, R_on, Geschwindigkeit)
- Strom-/Spannungsverlauf an Schaltern
  - "Halbleitender Zustand" (Verluste)
- Motivation: Relais

### Dioden
- Elektrische Funktion von Dioden
- Strom-Spannung-Kennlinie
  - "Konstante" Vorwärtsspannung
  - Verluste in Dioden
- Parallelschalten von Dioden
- *Einheit 5*
- Andere Diodenarten
  - Shottky-Dioden
  - LEDs
    - Hochleistungs-LEDs
  - Zener-/Lawinendioden
  - PIN-Dioden
  - Diacs
- Übung 5.1

### Transistoren
#### MOSFET
- Grundlegende Funktion
  - N-Kanal, P-Kanal
- N-Kanal vor die Last platziert
  - Bootstrapping
- *Einheit 6*
- Rückwärts-Diode
- Transistor-Kennlinie
  - Transistoren auf LCSC raussuchen (IRF3205PBF)
- Parasitäre Kapazitäten
  - Miller-Effekt
  - Überschwingen am Gate
  - Gate-Treiber
- Übung 5.2
- *Einheit 7*

#### BJT
- Ersatzschaltung (zwei Dioden)
- Transistor-Kennlinie
  - Verstärkungsfaktor h
- Optokoppler

#### Thyristoren
- Ersatzschaltung (FlipFlop)
- Funktionsweise
- Triacs
  - Nutzung in Phasenanschnittssteuerung

#### IGBT
- Ersatzschaltung
- Transistor-Kennlinie
- Fehlende Rückwärts-Diode

## 6. Grundlegende Halbleiterschaltungen
- Gleichrichter
- Darlington-Transistor
  - Sziklai-Paar
- Stromspiegel
  - Verbesserung der Genauigkeit
- *Einheit 8*
- Einschaltverzögerung
  - Ausschaltverzögerung als Übung
- Logik-Invertierer
- Linearer Spannungswandler
- H-Brücke
- Verpolungsschutz mit FET

## 7. Operationsverstärker
- Grundlegende Funktion
  - Realer Operationsverstärker

### Schaltungen ohne Gegenkopplung
- Schmitt-Trigger
- ST-Oszillator
  - PWM-Oszillator
- *Einheit 9*

### Schaltungen mit Gegenkopplung
- Mittkopplung, Gegenkopplung

#### Nicht-invertierend
- Spannungsfolger
- N. inv. Verstärker
  - (kurz ansprechen) Filter
- Präzisions-Halbwellen-Gleichrichter
- Übung 7.1

#### Invertierend
- Herleiten derartiger Schaltungen
  - Offset-Spannung
- Addierer
- Subtrahierer
- Integrierer
- Differenzierer
- Nicht-ideale OpV
- *Einheit 10*
- Übung 7.2, als Beispiel zeigen

### 555-Timer-Schaltungen
- Grundfunktion des 555-Timers
  - https://dwma4bz18k1bd.cloudfront.net/tutorials/_1200x630_crop_center-center_82_none/555-timer-tutorials-thumbnail.png?mtime=1715167497
- Astabiler Multivibrator (Grundfunktion)
  - Problem mit Asymmetrie
- Symetrischer atabiler Multivibrator
  - PWM-Generator
- Monostabile Kippstufe
- Varianten des IC: TS555, LMC555, XL7555

## 8. Mikrokontroller
- Unterschied Datenblatt und technische Referenz (Handbuch)
- Register im Allgemeinen
- Projekt in STM32-Cube anlegen
- Clocks
  - Lesen bei positiver Flanke, Ausgabe bei negativer Flanke
- Interrupts
- HAL
- GPIO
  - Pull-Up, Pull-Down
  - Open-Drain-Modus
- Timer
  - PWM erzeugen
- A/D-Wandler
  - Kanal-Multiplexen
- Kommunikation
  - UART (USART)
    - Schnittstelle: RS485
  - I²C
  - SPI
- DMA
- Low-Power-Modes
- EEPROM
- Flash-Speicher
- CRC
- RTC
- RTO
