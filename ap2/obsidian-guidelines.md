Obsidian Best Practices for AP2 Vault

Ziele: klare Struktur, leicht publishbare Artikel, gutes Linking, Templates und Export-Pipeline.

Structure
- One theme = one note (ap2/notes/<Thema>.md)
- Supporting material in folders: ap2/diagrams, ap2/research, ap2/revision, ap2/templates
- Use frontmatter for publish-ready notes (title, description, author, publish_ready)

Linking
- Create a central index (ap2/overview.md) linking to all theme notes.
- Within each theme note, link to related topics using Obsidian-style [[Note Title]] links.
- Use backlinks to discover loose connections; create MOC (map of content) notes for major clusters.

Tagging
- Follow ap2/tags.md taxonomy. Ensure each theme note has: Topic tag, Format tag (#Format.Article), Status tag.

Templates
- ap2/templates/theme-template.md — frontmatter + headings (Zusammenfassung, Aktivitäten, Artefakte, Prüfungsaufgaben, Tags, Nächste Schritte)
- ap2/templates/anki-card-template.md — Q/A front/back template

Publishing
- Notes with publish_ready: true are export-ready for Quartz/Static sites.
- Images should be stored in ap2/diagrams and referenced with relative links.

Automation
- ap2-daily-work should: create/improve notes, add links, generate diagrams, update MOCs, and propose one workflow improvement per run.

References
- Obsidian vault organization guides, MOC patterns, Zettelkasten principles (will fetch links automatically).
