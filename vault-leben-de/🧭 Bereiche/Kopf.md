---
type: bereich
tags: bereich
---
# 🧠 Kopf

> Ein Bereich ist nie "fertig". Er hat einen Standard, den ich halten will. Ein Projekt dagegen hat ein Ende.

## Warum mir das wichtig ist
(Ein bis zwei Sätze, in deinen eigenen Worten.)

## Gut genug heißt
(Dein Mindeststandard. Nicht perfekt, sondern ausreichend. Zum Beispiel: "Dreimal die Woche 20 Minuten raus.")

## Womit ich mich hier beschäftige
- Wie geht es mir gerade wirklich
- Therapie, Coaching, Austausch
- Routinen, die mich tragen (Morgen, Abend)
- Was mich triggert oder überfordert
- Was mir hilft (siehe [[🧠 Mein Betriebshandbuch]])

## Wie läuft es gerade? (1 bis 5)
Stand: 

## Nächster kleinster Schritt
- 

## Offene Aufgaben
```tasks
not done
tags include #kopf
sort by due
sort by priority
limit 15
```

## Notizen zu diesem Bereich
```dataview
LIST
FROM #kopf
WHERE !contains(file.folder, "Vorlagen")
SORT file.mtime DESC
LIMIT 10
```
