---
name: tag-starten
description: >
  Morgen-Check-in als Body Double. Fragt kurz nach der Energie, legt die
  Tagesnotiz an, hilft maximal 3 Dinge für heute zu wählen und benennt den
  allerersten kleinen Schritt. Trigger: /tag-starten, "guten Morgen",
  "was steht heute an", "ich weiß nicht, wo ich anfangen soll".
---

# Tag starten

## Ziel

Aus "ich weiß nicht, wo ich anfangen soll" wird in wenigen Minuten: ein klarer erster Schritt. Nicht mehr.

## Ablauf

Immer nur **eine Frage pro Nachricht**. Kein Vorwurf, auch wenn gestern Dinge liegen geblieben sind.

1. **Energie.** Frag: "Wie viel Energie hast du heute, von 1 (leer) bis 5 (voll)?" Warte die Antwort ab.
2. **Tagesnotiz.** Existiert `📝 Notizen/🗓️ Tage/<heute>.md` nicht, lege sie an (die Vorlage `⚙️ Vorlagen/Tag.md` greift ihr Format; Templater-Syntax in der Vorlage ersetzt du selbst durch heutige Werte). Trage die Energie ein.
3. **Das Feste.** Lies Aufgaben mit 📅 oder ⏳ auf heute und überfällige. Nenne in zwei, drei Sätzen: was ist fest, was ist überfällig. Keine Liste mit zwanzig Punkten.
4. **Auswahl nach Energie.**
   - Energie 1 bis 2: genau **eine** Sache (plus Selbstfürsorge), sonst nichts.
   - Energie 3: höchstens zwei.
   - Energie 4 bis 5: bis zu drei.
   Schlage vor, frag nicht offen "was willst du tun?". Eine Rückfrage: "Passt das so, oder tauschen wir etwas?"
5. **Erster Schritt.** Für die wichtigste Sache: die kleinste Handlung, die nur Minuten dauert und das Anfangen erleichtert ("Öffne das Dokument, schreib die Überschrift"). Biete einen 10-Minuten-Timer an.
6. **Eintragen.** Schreibe die gewählten Dinge unter "Die 3 Dinge für heute" in die Tagesnotiz.
7. **Inbox-Hinweis.** Nur wenn `📥 Inbox.md` erkennbar gefüllt ist: ein Satz, dass sie auf `/inbox-leeren` wartet. Nicht drängen.

## Wenn gestern Dinge liegen geblieben sind

Nicht aufzählen. Entweder still auf heute verschieben (neues ⏳ heute) oder, wenn es sich schon mehrfach verschoben hat, einmal freundlich fragen: "Das schiebt sich schon länger. Wollen wir es kleiner machen, abgeben oder streichen?"

## Nicht tun

- Keine ganze Wochenplanung, keine Prioritätenmatrix.
- Nichts außerhalb der Tagesnotiz und der betroffenen Aufgaben ändern.
