# World of Worlds · عالم العوالم

> Life stories of real people, told as cinematic videos and a written anthology — with consent first.

**Status:** pre-alpha scaffold (no code yet). **Feasibility rating:** 7/10 as a creative concept.
**Idea:** #11 in the owner's ideas backlog. **Author:** Oussama EL HADJI. Part of the Bosaj ideas portfolio (sibling repo: `dual_portfolio_hub`).

---

## Problem

Everyone carries a story worth hearing, but most are never recorded. Families lose them when elders pass away.

## Why build it (gap analysis)

Oral-history projects exist, but few combine cinematic video, a written book, and a family archive in Arabic and Darija. The software side is the tool that makes production repeatable: interview kit, consent records, transcript, and a publishing site.

## Prior art & open bases to fork

- [TryGhost/Ghost](https://github.com/TryGhost/Ghost) — Open-source publishing platform for the written anthology.
- [openai/whisper](https://github.com/openai/whisper) — Transcribe Arabic/Darija interviews.

## Proposed architecture

1. Interview kit: question sets by theme, release/consent form, recording checklist.
2. Pipeline: raw footage, transcript (Whisper), story outline, edit notes.
3. Archive: private per-family space with consent level per story (private, family, public).
4. Publishing: public site with episodes and written chapters, Arabic-first.

## Tech stack (proposed)

- Next.js or Astro site, Arabic-first RTL
- Whisper transcription
- Supabase for consent records and private archive

## Roadmap

- v0.1 — Interview kit + consent form + 3 pilot stories.
- v0.2 — Transcript and story-outline pipeline.
- v0.3 — Private family archive with consent levels.
- v0.4 — Public site: episodes + anthology chapters.

---

## For LLM agents & contributors continuing this project

This repo is a **scaffold**: README + standard files, no implementation yet. If you are an AI agent asked to "continue developing", read this section first.

- Consent is the product: no story is published without a signed, recorded consent level.
- Store raw footage at original quality; only the delivery copies are compressed.

**Ground rules:** keep this README in sync with reality as you build; prefer forking/reusing the bases above over greenfield code; write tests for anything correctness-critical; never commit secrets (see `.gitignore`); follow Conventional Commits (see `CONTRIBUTING.md`).

## Getting started

```bash
# nothing to run yet — this is a scaffold.
```

## License

[MIT](LICENSE) — © 2026 Oussama EL HADJI
