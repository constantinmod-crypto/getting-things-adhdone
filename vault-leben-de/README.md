# 🧠 Mein Leben-und-Kopf-Vault

Ein fertiger Obsidian-Vault, um Leben und Gehirn zu ordnen. Gebaut für Köpfe, die nicht gern pflegen: **Du schreibst grob auf, Claude räumt auf.**

## Die Idee in 30 Sekunden

1. **Alles in die Inbox.** Ein Ort für jeden Gedanken, roh und unsortiert.
2. **Claude sortiert mit dir**, ein Punkt nach dem anderen (`/inbox-leeren`).
3. **Die Startseite zeigt nur das Nächste**, nie alles auf einmal.
4. **Acht Lebensbereiche** (Gesundheit, Geld, Beziehungen, Zuhause, Arbeit, Lernen, Freizeit, Kopf) halten das Große im Blick. **Projekte** haben ein Ende.
5. **Wenn es zu viel wird**, gibt es einen festen Ablauf: [[🆘 Überforderungs-Protokoll]].

## Einrichten (5 Minuten)

1. In Obsidian: *Ordner als Vault öffnen* und diesen Ordner `vault-leben-de` wählen. (Oder den Inhalt in einen neuen, leeren Vault kopieren.)
2. *Einstellungen → Community-Plugins* aktivieren und diese vier installieren:
   - **Templater**
   - **Tasks**
   - **Dataview**
   - **Force note view mode** (`obsidian-view-mode-by-frontmatter`)
3. Plugin-Einstellungen prüfen (sind vorbelegt, falls nicht):
   - Templater: Template-Ordner `⚙️ Vorlagen`, "Trigger on new file creation" an, Ordner-Vorlagen an (`📝 Notizen` = Standard, `🗓️ Tage` = Tag, `🗓️ Wochen` = Woche, `🚀 Projekte` = Projekt).
   - Tasks: Global Filter `#task`, "Set created date on every added task" an.
   - Dataview: "Enable JavaScript Queries" ist nicht nötig, alles läuft ohne.
   - Kern-Plugin *Tägliche Notizen*: Ordner `📝 Notizen/🗓️ Tage`, Format `YYYY-MM-DD`, **keine** Vorlage eintragen (Templater übernimmt das).
4. `🏠 Start` öffnen und als Startseite festlegen (optional mit dem Plugin *Homepage*).
5. Claude Code im Vault-Ordner starten (`claude`) und `/tag-starten` ausprobieren.

## Was ist drin

| Datei / Ordner | Wofür |
|---|---|
| `🏠 Start` | Dashboard: jetzt dran, wichtig, wartend, aktive Projekte |
| `📥 Inbox` | Der eine Ort zum Einwerfen |
| `✅ Aufgaben` | Ablage für lose Aufgaben (nicht lesen, nur per Ansicht) |
| `🧭 Bereiche/` | Acht Lebensbereiche mit Mindeststandard und offenen Aufgaben |
| `🚀 Projekte/`, `🗄️ Archiv/` | Aktive und fertige Projekte |
| `📝 Notizen/` | Alles andere, flach: Tage, Wochen, Ideen, Anhänge |
| `🆘 Überforderungs-Protokoll`, `🎲 Dopamin-Menü`, `🧠 Mein Betriebshandbuch` | Kopf-Notizen für schwere Tage und zum Kennenlernen deiner Muster |
| `⚙️ Vorlagen/` | Tag, Woche, Projekt, Standard |
| `.claude/skills/` | `/tag-starten`, `/inbox-leeren`, `/wochenrueckblick` |
| `CLAUDE.md` | Spielregeln für Claude (Ton, Struktur, Aufgabenformat) |

## So benutzt du es im Alltag

- **Morgens:** `/tag-starten`. Energie sagen, 1 bis 3 Dinge wählen, ersten Schritt machen.
- **Tagsüber:** Alles, was dir einfällt, in die [[📥 Inbox]]. Mehr nicht.
- **Wenn die Inbox voll ist oder der Kopf schwirrt:** `/inbox-leeren`.
- **Einmal pro Woche:** `/wochenrueckblick`. Zehn Minuten reichen.
- **Wenn alles zu viel ist:** [[🆘 Überforderungs-Protokoll]], dann [[🎲 Dopamin-Menü]].

Neue Aufgaben schreibst du so (oder lässt Claude sie schreiben):

```
- [ ] Zahnarzttermin ausmachen #task #gesundheit 📅 2026-12-05 🔼
```

## Anpassen

Alles ist Text. Ordner umbenennen geht, dann `CLAUDE.md`, Skills und Templater-Ordnerzuordnung mitziehen. Mehr Hintergrund zur Technik hinter Templater, Tags und Dashboards steht in `../docs/vault-setup.md`.
