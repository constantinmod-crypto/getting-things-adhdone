---
type: bereich
tags: bereich
---
# 💶 Geld

> Ein Bereich ist nie "fertig". Er hat einen Standard, den ich halten will. Ein Projekt dagegen hat ein Ende.

## Warum mir das wichtig ist
(Ein bis zwei Sätze, in deinen eigenen Worten.)

## Gut genug heißt
(Dein Mindeststandard. Nicht perfekt, sondern ausreichend. Zum Beispiel: "Dreimal die Woche 20 Minuten raus.")

## Womit ich mich hier beschäftige
- Was kommt rein, was geht raus (grob)
- Verträge und Abos, die ich prüfen will
- Steuer und Versicherungen
- Rücklage (auch klein zählt)
- Offene Rechnungen

## Wie läuft es gerade? (1 bis 5)
Stand: 

## Nächster kleinster Schritt
- 

## Offene Aufgaben
```tasks
not done
tags include #geld
sort by due
sort by priority
limit 15
```

## Notizen zu diesem Bereich
```dataview
LIST
FROM #geld
WHERE !contains(file.folder, "Vorlagen")
SORT file.mtime DESC
LIMIT 10
```
