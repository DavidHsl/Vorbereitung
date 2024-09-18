---
tags:
  - Abschluss
  - BS
  - Programmieren
---
# Java
## 3 Arten der Schleifen
### while-schleife
```java
while (i < nummer) {
  // tut etwas bis die variable die gefragte nummer ereicht
}
```

**Bedeutung**
Das `i` steht für eine variable die früher im Programm definiert wurde.
Die `nummer` ersetzt du mit dem wert einer Zahl in diesem Beispiel

**Beschreibung**
Diese Art von Schleife (übersetzt `Solang`-schleife) führ denn Code in den geschweiften Klammern solang aus wie der wert in den normalen Klammern Wahr ist. Also z.B. `5 < 10` währe *wahr* aber `10 < 10` währe *falsch*.

### for-schleife
```java
for (int i = 0; i < nummer; i++) {
  //tut etwas so oft wie die nummer in der variable
}
```
**Bedeutung**
- Das `int i = 0;` initalisiert und definiert die *Variable* mit dem Wert von `0` und wird nur am anfang der Schleife ausgeführt
- Das `i < nummer;` ist ähnlich wie die Wahrheitsprüfung in [[#while-schleife|while-schleife]] und prüft am anfang nach jedem durchlaufe der Schleife.
- Das `i++` steht für das was er am ende jedes Durchlaufes der Schleife macht.

**Beschreibung**
Diese Art von Schleife (übersetzt ``)

### do-while-schleife
```java
do {
  //tut etwas einmal und dann so oft bis die variable den wert der nummer ereicht
} while (i < nummer)
```




## Aufgabe 1
```java
for (int i = 0; i < 24; i++) {
  sumTemp = sumTemp + usedRam[i];
}
avgUsedRam = sumTemp / 24;

if (avgUsedRam >= 75) {
  MessageBox.Show(message, title);
}
```

## Aufgabe 2
```java
for (int i = 0; i < 24; i++) {
  if (usedCPU[i] >= 80) {
    sumstd = sumstd +1;
  }
}
cpulimit = 18;
if (sumstd > cpulimit) {
  MessageBox.Show(message, title);
}
```

