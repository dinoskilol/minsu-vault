minsu-vault — personal Obsidian workspace

Purpose

This repository is Minsu's personal Obsidian vault: a single-source workspace for study notes, drafts, templates, and curated research. It is intended to be a living collection of high-quality, publishable markdown notes focused on the AP2 (Abschlussprüfung Teil 2) curriculum and related software development topics.

What this vault contains

- Notes/: The primary collection of thematic notes. Each note is a self-contained, well-researched article (one theme per file) written in clear, academic German and prepared for possible publication.
- Research/: Source tracking and reference files used to cite articles and store PDFs or screenshots of source material.
- Diagrams/: Generated images and diagrams (UML, ERD, flowcharts) referenced from notes.
- Revision/: Exported revision material such as Anki-compatible CSVs and flashcard exports.
- Templates/: Note and export templates (theme article, Anki card CSV template, publication frontmatter).

Principles and conventions

- One theme = one note: Each file in Notes/ covers exactly one topic and aims to be a compact, stand-alone article that teaches the subject.
- Publish-ready markdown: Notes include frontmatter (title, description, author, publish_ready) when appropriate so content can be exported to static sites or publishing platforms.
- Wiki-style linking: Notes use Obsidian-style [[Internal Links]] to create a navigable knowledge graph. Maintain a Map-of-Content (MOC) at ap2/Notes/Index.md for high-level navigation.
- Research-first: Every substantive note references its sources. Use Research/ to store source lists and downloadable artifacts.
- No secrets in vault: Credentials and private keys must never be stored here. Use ~/.config/ for secrets and API keys.
- Semantic commits: Commits are short and descriptive, e.g. "ap2: add <topic>" or "ap2: improve <topic> — added examples and diagrams".

Automation

Minsu (the automated assistant) runs scheduled tasks to maintain and grow the vault. Tasks may:
- Create or improve one theme note per scheduled run (researching, writing, and linking as needed).
- Generate diagrams and revision exports.
- Commit and push changes to this repository and notify the owner via Telegram.

If you want to change the automation schedule, editing the cron jobs is required. Ask before modifying automation that sends external messages.

How to use this vault

- Open it with Obsidian (desktop or AppImage) and enable backlinks/graph view to navigate the network of notes.
- Use the Templates/ folder to create new notes that conform to the vault's structure.
- Check Research/ before trusting facts; sources are collected there for verification.

Contributing & Safety

- This is a personal/private vault. Treat content here as in-development and private unless explicitly published.
- Do not commit secrets, API keys, or personal credentials. If you need a secret stored, put it in ~/.config and reference it from automation scripts.

About Minsu (the assistant)

Minsu is an automated study assistant that maintains this vault. Responsibilities:
- Keep notes concise, accurate, and publish-ready.
- Research authoritative sources and include reference lists.
- Produce revision material (flashcards, summaries) on request.
- Notify the owner (Dino) of daily updates and significant changes.

Contact & Notifications

- Daily summaries and important alerts are sent to the configured Telegram account.
- For changes to automation, ask explicitly before requesting system updates.

License & Privacy

- The vault may contain notes that summarize public sources; always attribute and respect copyright when exporting or publishing content.
- This repository is private by default.


