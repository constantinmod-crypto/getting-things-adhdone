---
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
tags: wochenrueckblick
---
<%* await tp.file.rename(tp.date.now("GGGG-[W]WW")) %>
# Wochenrückblick <% tp.date.now("GGGG-[W]WW") %>

## Das habe ich geschafft (letzte 7 Tage)
```tasks
done after <% tp.date.now("YYYY-MM-DD", -7) %>
sort by done
```

## Das ist liegen geblieben
```tasks
not done
due before today
sort by due
```

## Drei Fragen
1. Was lief gut? 
2. Was hat mich ausgebremst? 
3. Was nehme ich mir für nächste Woche vor (maximal 3)? 

## Bereiche-Check (kurz, 1 bis 5)
Gesundheit: · Geld: · Beziehungen: · Zuhause: · Arbeit: · Lernen: · Freizeit: · Kopf: 

## Inbox
- [ ] [[📥 Inbox]] leeren oder wenigstens anschauen
