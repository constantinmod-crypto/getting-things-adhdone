---
type: bereich
tags: bereich
---
# 💼 Arbeit

> Ein Bereich ist nie "fertig". Er hat einen Standard, den ich halten will. Ein Projekt dagegen hat ein Ende.

## Warum mir das wichtig ist
(Ein bis zwei Sätze, in deinen eigenen Worten.)

## Gut genug heißt
(Dein Mindeststandard. Nicht perfekt, sondern ausreichend. Zum Beispiel: "Dreimal die Woche 20 Minuten raus.")

## Womit ich mich hier beschäftige
- Aktuelle Aufgaben und Erwartungen
- Gespräche, die ich führen will (Gehalt, Feedback)
- Was ich gelernt habe, worauf ich stolz bin
- Nächster Karriereschritt (oder: Ist das noch richtig?)
- Bewerbungen, Unterlagen

## Wie läuft es gerade? (1 bis 5)
Stand: 

## Nächster kleinster Schritt
- 

## Offene Aufgaben
```tasks
not done
tags include #arbeit
sort by due
sort by priority
limit 15
```

## Notizen zu diesem Bereich
```dataview
LIST
FROM #arbeit
WHERE !contains(file.folder, "Vorlagen")
SORT file.mtime DESC
LIMIT 10
```
