# Minsu Vault — personal Obsidian workspace

Hello — i'm Minsu, an automated study assistant and vault maintainer. i help collect, organize, and maintain markdown notes, templates, and research artifacts in this private Obsidian vault.

## What this repository currently contains

- `Notes/` — The primary collection of markdown notes and drafts. Each file is a standalone note used for personal study, writing, or drafting. Files may vary in topic and completeness.
- `Research/` — Reference lists and source-tracking files. Stores links and pointers to external resources; not all sources are downloaded.
- `Diagrams/` — Image assets and generated diagrams referenced by notes.
- `Revision/` — Exports and working files for revision materials (e.g., CSVs intended for Anki import).
- `Templates/` — Note and export templates used to create new content with a consistent structure.
- `memory/` — Agent memory and configuration files used by Minsu. Contains notes about automation, profiles, and task configuration. This folder may include personal metadata; handle with care.

## Purpose of the vault

This vault is a single-source workspace for drafting, iterating, and storing markdown content. It is intended to be a living workspace — notes are edited, improved, and versioned over time. The vault is private and used for development, study, and content preparation.

## How i (Minsu) work with the vault

- i run scheduled maintenance tasks (configurable) that can create, improve, and commit notes. I only modify files in this repository with your permission or as configured by cron jobs you've approved.
- I keep a small set of templates and a research folder to track sources and artifacts.
- I commit and push changes to the private remote when appropriate and notify you of major updates.

## Safety & privacy

- This repository must not contain secrets, API keys, or credentials. Keep secrets in `~/.config/`.
- The vault is private by default. Publishing or sharing content should be done intentionally, with proper attribution to original sources.

## Practical notes

- To open this vault in Obsidian, use the `Notes/` folder as the root of your vault.
- Use the `Templates/` folder to create new notes with the expected structure.
- If you want me to stop automatic commits or change schedules, tell me and i'll update the automation settings.

---

If you want a German version of this README or a short badge that shows publishing status, say so and i'll add it. 🦞