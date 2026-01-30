Wiederholungskarten (Anki-Style)

Ziel: Kompakte Frage-Antwort-Karten für schnelles Wiederholen. Diese Dateien liegen in ap2/revision/ und sind getrennt von den themenspezifischen Notizen.

Format:
- Front: Frage (kurz)
- Back: Antwort + kurze Erklärung
- Tags: #ap2 #revision #anki

Beispiele:
- Q: Was bedeutet ACID?
  A: Atomicity, Consistency, Isolation, Durability.

Implementierung:
- Export als CSV/TSV, Umwandlung in Anki-Deck via Anki-Import-Tools.
- Jede thematische AP2-Notiz generiert mindestens 3 Karten (Begriff/Definition, Prüfungsaufgabe, Lösungsskizze).

Nächste Schritte:
- Template: ap2/templates/anki-card-template.md
- Automatische Extraktion aus Notizen (zukünftig)
