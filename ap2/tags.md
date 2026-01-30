AP2 Tag-System

Ziele: konsistente Tags für Navigation, Publishing und Anki-Export

Tag-Gruppen:
- Themen: #ap2 #Anforderungsanalyse #Softwareentwicklung #Datenbanken #Web #Testing #Deployment #Security #UX
- Format: #Format.Article #Format.RevisionCard #Format.Diagram
- Status: #Status.Draft #Status.Reviewed #Status.PublishReady
- Priority: #Priority.Core #Priority.Supplement #Priority.DeepDive

Usage:
- Jeder Artikel erhält: 1 Thema-Tag, 1 Format-Tag, 1 Status-Tag, optional Priority-Tag
- Before publishing: set `#Status.PublishReady` and add frontmatter (title, description, author, publish_ready: true)

Examples:
- Anforderungsanalyse.md → #Anforderungsanalyse #Format.Article #Status.Reviewed #Priority.Core
- Datenbanken & SQL.md → #Datenbanken #Format.Article #Status.Reviewed #Priority.Core

I'll enforce tag usage in ap2-daily-work and add tag corrections automatically when obvious.
