# 1. Architecture

1. Interview kit: question sets by theme, release/consent form, recording checklist.
2. Pipeline: raw footage, transcript (Whisper), story outline, edit notes.
3. Archive: private per-family space with consent level per story (private, family, public).
4. Publishing: public site with episodes and written chapters, Arabic-first.

## Proposed stack
- Next.js or Astro site, Arabic-first RTL
- Whisper transcription
- Supabase for consent records and private archive

## Open bases to fork
- [TryGhost/Ghost](https://github.com/TryGhost/Ghost) — Open-source publishing platform for the written anthology.
- [openai/whisper](https://github.com/openai/whisper) — Transcribe Arabic/Darija interviews.
