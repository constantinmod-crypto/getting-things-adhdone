---
obsidianUIMode: preview
tags: dashboard
---
# 🏠 Start

> Du musst nicht alles sehen. Nur das Nächste. Cmd/Strg + E zum Bearbeiten.

**Schnell:** [[📥 Inbox]] (alles reinwerfen) · [[🆘 Überforderungs-Protokoll]] · [[🎲 Dopamin-Menü]] · [[🧠 Mein Betriebshandbuch]]

## 🎯 Jetzt dran (heute, überfällig, maximal 7)
```tasks
not done
(due today) OR (scheduled today) OR (due before today)
sort by priority
sort by due
limit 7
```

## ⭐ Wichtig, aber ohne Termin (maximal 5)
```tasks
not done
no due date
no scheduled date
priority is above none
sort by priority
limit 5
```

## ⏳ Ich warte auf andere
```tasks
not done
tags include #warten
sort by created
limit 10
```

## 🚀 Aktive Projekte
```dataview
TABLE WITHOUT ID file.link AS Projekt, bereich AS Bereich, dateformat(file.mtime, "dd.MM.") AS "Zuletzt angefasst"
FROM "🚀 Projekte"
WHERE type = "projekt" AND status = "aktiv"
SORT file.mtime DESC
```

## 🧭 Lebensbereiche
[[🧭 Bereiche/Gesundheit|💪 Gesundheit]] · [[🧭 Bereiche/Geld|💶 Geld]] · [[🧭 Bereiche/Beziehungen|❤️ Beziehungen]] · [[🧭 Bereiche/Zuhause|🏠 Zuhause]] · [[🧭 Bereiche/Arbeit|💼 Arbeit]] · [[🧭 Bereiche/Lernen|📚 Lernen]] · [[🧭 Bereiche/Freizeit|🎨 Freizeit]] · [[🧭 Bereiche/Kopf|🧠 Kopf]]

## 💡 Ideen
```dataview
LIST
FROM #idee
SORT file.ctime DESC
LIMIT 5
```
