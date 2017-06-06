# Python
Python Einführung: http://www.thomas-guettler.de/vortraege/python/einfuehrung.html

## Datentypen

| Datentyp | Code | Erklärung|
|--|--|--|
| Integer	| `i = 1`	| Ganzzahl |
| Float	| `f = 0.1`	| Gleitkommazahl |
| String	| `s = 'hallo'`	| Zeichenkette |
| Liste	| `l = [1, 2, 3]`	| Veränderbare Liste |
| Tuple	| `t = (1, 2, 3)`	| Unveränderbare Liste |
| Menge	| `z = set([1, 1, 2, 2, 3]) --> set([1, 2, 3])`	| Menge (ohne Dopplungen)|
| Dictionary |	`d = {1: 'eins', 2: 'zwei', 3: 'drei'}`	| Auch Hash oder assoziatives Array  genannt. |

### Typ-Umwandlungen
* int(), float(), string()

### User input
* `raw_input()`: liefert ein String
* `input()`: liefert ein int oder double
* Im Zweifelsfall `type()`verwenden

### Operatoren
http://www.python-kurs.eu/python3_operatoren.php

| Operator | Name |
|--|--|
| +, - |	Addition, Subtraktion	|
| *, %	| Multiplikation, Rest |
| <, <=, >, >=, !=, == | Vergleichsoperatoren |
| or, and, not	| Boolsches Oder, Boolsches Und, Boolsches Nicht |

## Control Strukturen
### If else
```
if x < 0:
  x = 0
  print 'Negative changed to zero'
elif x == 0:
  print 'Zero'
elif x == 1:
  print 'Single'
else:
  print 'More'
```

Siehe: https://docs.python.org/2/tutorial/controlflow.html

## Lists