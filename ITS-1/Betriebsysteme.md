---
tags:
  - BS
  - its-1
  - betriebsystem
  - os
---
Unter einem Betriebssystem versteht man eine Computer mit dem Kernal und allen wichtigen Systemkomponenten.
# Kernal

## Prozessorverwaltung

## Speicherverwaltung

## Dateiverwaltung

## Geräteverwaltung

# Schichten
![[OS.png]]
# Eigenschaften
## Multitasking
Bedeutet das der Rechner aus Anwendersicht Mehrer Programme gleichzeitig verarbeiten kann. 
## Schedualing
Der Scheduler regelt die die zeitliche Ausführung
mehrerer Prozesse in Betriebssystemen.
Er teilt dem Prozessor mit, wann welcher
Prozess auszuführen ist.
Jeder Prozess wird nach einer bestimmten
Abarbeitungszeit unterbrochen (Zeitscheibe,
time slice). Dann ist der Prozess inaktiv und ein
anderer Prozess wird aktiv. Erhält er wieder eine
Prozessorzuteilung, so ist er wieder aktiv und
setzt seine Arbeit fort.
Meistens haben alle Zeitscheiben die gleiche,
feste Dauer. Über eine variable Zeitzuteilung
können Prozesse priorisiert werden.

## Mehrprozessorbetrieb
Wenn das OS mehrere CPUs verwendet.

# Übungen

## 1
Ein OS besteht aus unterschiedlichen Schichten. 
Diese schichten sind die Hardware schicht, worin sich die Physische hardware deines Systems befindet.

Danach gibts die Kernal schicht worin sich die Treiber und Systemkritsche Software stücke befinden wie zum Beispiel Dateisystem

Nun kommen wir zur Userspace (Anwendungsschicht) worin sich alle Benutzerbezogenen Programme sich befinden.
