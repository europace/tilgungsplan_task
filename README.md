# Aufgabenbeschreibung

## Implementierung eines Tilgungsplans

Bitte entwickle ein Programm, das durch die Eingaben

* des Darlehensbetrages
* des Sollzinses (in Prozent)
* der anfänglichen Tilgung (in Prozent)
* der Zinsbindung (in Jahren)

den Tilgungsplan eines Darlehens mit gleichbleibender Rate erstellen kann. 

Diese tabellarische Übersicht zeigt dir, wie ein Tilgungsplan aufgebaut ist:

| Datum | Restschuld | Zinsen | Tilgung(+)/Auszahlung(-) | Rate |
| ----- | ---------: | -----: | -----------------------: | ---: |
| 30.11.2015 | -100.000,00€ | 0,00€ | -100.000,00€ | -100.000,00€ |
| 31.12.2015 | -99.833,34€ | 176,67€ | 166,66€ | 343,33€ |
| 31.01.2016 | -99.666,38€ | 176,37€ | 166,96€ | 343,33€ |
| ... | ... | ... | ... | ... |
| 31.10.2025 | -77.949,76€ | 138,07€ | 205,26€ | 343,33€ |
| 30.11.2025 | -77.744,14€ | 137,71€ | 205,62€ | 343,33€ |
| Zinsbindungsende | -77.744,14€ | 18.943,74€ | 22.255,86€ | 41.199,60€ |

(Zinsbindung: 10 Jahre, Sollzins: 2,12%, Anfängliche Tilgung: 2%)

Ein Tilgungsplan besteht aus einer Reihe von Einträgen, wobei der erste die Auszahlung des Darlehens widerspiegelt. Jeder (weitere) Eintrag besteht aus einem Datum, der Restschuld, den Zinsen, der Tilgung bzw. Auszahlung sowie der Rate. Die Auszahlung soll immer am letzten Tag des aktuellen Monats erfolgen. Die erste Tilgung erfolgt am letzten Tag des darauffolgenden Monats.

Die Zahlungen eines Tilgungsplans sind monatlich darzustellen. Zum Ende der Zinsbindung sind die Restschuld sowie die geleisteten Zahlungen von Interesse.

Zur Eingabe und Ausgabe reicht ein einfaches Textinterface.

## Was wollen wir sehen?

Wir wollen einen Eindruck bekommen, wie du an eine Aufgabe herangehst, die typisch für Europace ist.

Dazu gehört, die bewusst deutschen und nicht vollständig spezifizierten Anforderungen zu verstehen und die Logik in Code umzusetzen.

Die Wahl der eingesetzten Technologien ist dir freigestellt. Bedenke aber, auf welche Stelle du dich bewirbst.

Bitte sende uns das Ergebnis in Form des Quellcodes zu, idealerweise gleich als Link zu einem Repo (z.B. hier auf Github) oder als ZIP gepackt.

## What do we want to see?

We want to get an impression of how you approach a task that is typical for Europace.

This includes understanding the intentionally German and not fully specified requirements and implementing the logic in code.

The choice of technologies used is up to you. But consider which position you are applying for.

Please send us the result in the form of the source code, ideally as a link to a repo (e.g. here on Github) or packed as a ZIP.
