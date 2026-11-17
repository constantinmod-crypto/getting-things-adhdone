---
obsidianUIMode: preview
tags: dashboard
---
# 💡 Ideen

Jede Notiz mit dem Tag `#idee` taucht hier auf. Ideen müssen nicht umgesetzt werden. Sie dürfen einfach da sein.

```dataview
TABLE WITHOUT ID file.link AS Idee, dateformat(file.ctime, "dd.MM.yyyy") AS Datum
FROM #idee
SORT file.ctime DESC
```
