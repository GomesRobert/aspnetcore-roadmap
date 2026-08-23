# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is **not a software project** — it's a personal ASP.NET Core / .NET 10 learning roadmap kept as Markdown, plus the user's own progress log. There is no build, lint, or test tooling, and none should be introduced unless the user explicitly asks for a companion code project.

## Structure

- `README.md` / `README.en.md` — the canonical roadmap (PT-BR and English versions), a 43-module curriculum from fundamentals through advanced architecture. These two files must stay in sync with each other in structure and content, differing only by language.
- `aspnetcore-roadmap/README.md` / `aspnetcore-roadmap/README.en.md` — the user's **personal working copy** of the same roadmap. This is where Robert checks off items (`[ ]` → `[✅]`) and appends his own free-text notes/summaries in Portuguese directly after a checked item, e.g.:

  ```markdown
  - [✅] Git   Git e uma ferramenta de versionamento que permite que varias pessoas trabalhem no mesmo projeto...
  ```

  Do not "clean up," reformat, correct grammar/spelling in, or overwrite these personal notes unless explicitly asked — they are the user's own learning record, not documentation prose. When helping the user study or update this file, preserve their voice and only edit the specific item(s) they're working on.

## Document conventions (apply when editing either README)

- Priority markers: 🔴 Essential, 🟠 Important, ⚪ Optional/advanced. Keep these consistent when adding or reorganizing topics.
- Each of the 43 modules is wrapped in a collapsible `<details>` block with an `<a id="...">` anchor right before it; the anchor slugs differ between the PT-BR file (accented/Portuguese slugs like `#modulo-01`, `#fundamentos`) and the EN file (`#module-01`, `#fundamentals`). When adding a new module or section, add matching anchors and update both the root and (if applicable) the mermaid diagrams and the "macroáreas / main areas" index table.
- Mermaid `flowchart` diagrams are used for the high-level overview and the guide-project progression — mirror any structural change in the roadmap into these diagrams in both language files.
- The roadmap is licensed CC BY-NC-SA 4.0 and adapted from Moien Tajik's AspNetCore-Developer-Roadmap; keep the attribution in the References section intact.

## Working across the two READMEs

When the user asks to add/change a topic in the canonical roadmap, mirror the edit into **both** `README.md` and `README.en.md` (translating, not copying verbatim). Do not propagate canonical-roadmap edits into `aspnetcore-roadmap/README*.md` automatically — that pair is the user's personal checklist and may intentionally lag behind or diverge (e.g., partially checked off, annotated with notes).
