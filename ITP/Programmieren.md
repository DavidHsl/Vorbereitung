---
tags:
  - Abschluss
  - BS
  - Programmieren
---
# Java
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
if (sumstd < cpulimit) {
  MessageBox.Show(message, title);
}
```

