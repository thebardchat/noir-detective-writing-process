# You Probably Think This Book Is About You — Writing Process

Governed by the [TheShaneBrain Constitution](https://github.com/thebardchat/constitution).

## What This Repo Is

This is the **public process repo** for a two-volume noir vignette book. It documents the AI-human writing pipeline — how raw voice dumps become shaped prose. The actual manuscript lives in a **private repo** and is not included here.

**DO NOT include manuscript text, scene content, track lyrics, plot details, or spoilers in this repo. Ever.**

## The Pipeline

```
1. Shane talks (live dictation while driving, walking, living)
2. Raw voice → transcript (messy, fragmented, multilingual, real)
3. Claude shapes the transcript → noir third-person prose
4. Shane approves / redirects / riffs more
5. Track locks → audio generation (ElevenLabs)
6. Album compiles when it compiles
```

## Sacred Rules — DO NOT BREAK THESE

### Content Protection
1. **NO manuscript text in this repo.** No scene content. No track lyrics. No monologues. No "samples" that contain actual prose from the book. Not even a paragraph.
2. **NO spoilers.** Do not describe plot twists, character reveals, structural tricks, or hidden scenes. The reader discovers these by reading the book.
3. **NO character backstories.** The characters in the book have detailed histories. None of that goes here. Refer to them by their roles only (the detective, the old man, the garbage man, etc.).
4. **NO draft files.** No scene-XXX.md or track-XXX.md files. Those belong in the private repo only.

### What CAN Go Here
1. **Process documentation** — how the pipeline works, how voice dumps become prose
2. **Templates** — blank scene/track templates (no content filled in)
3. **Structure descriptions** — how the book is organized (acts, sides, etc.) without revealing what happens in them
4. **Technical setup** — tools used (Pi 5, Claude, ElevenLabs, Piper TTS)
5. **Voice & tone rules** — the stylistic guidelines, without examples pulled from the manuscript
6. **The CLAUDE.md itself** — this file, the rules, the constitution
7. **Sanitized examples** — original prose written specifically for this repo to demonstrate the style. NOT pulled from the book. Clearly marked as "demo, not from the book."
8. **Cover art** — promotional images are fine

### Voice Rules (for anyone collaborating)
1. **Noir third person.** The detective narrates but is not above it — he's in it too.
2. **Short punches followed by long runs.** Cadence matters.
3. **No lectures. No sermons.** Witness, don't judge.
4. **Humor is dry**, placed where the reader doesn't expect it.
5. **Callbacks land as echoes**, not repetition. Same image, different weight.
6. **No names.** The detective is never named. Neither is anyone else (with rare, intentional exceptions).
7. **Shape Shane's voice, don't reimagine it.** When processing raw voice dumps, the shaped version should be exactly what Shane is thinking, transcribed into his cadence. Polish and connect, don't invent.

### The Raw Voice Pipeline
- Shane records voice while driving, walking, or living
- Transcripts are messy: fragments, multilingual bleed-through, background noise, checkout beeps, tangents
- Claude's job is to find the scene inside the noise — the image, the feeling, the observation — and press it into noir prose
- The raw material is the authority. If it's unclear, ask. Don't guess.
- Foreign language fragments are intentional and meaningful. Interpret them, don't discard them.

## Technical Stack

| Tool | Purpose |
|------|---------|
| Raspberry Pi 5 (16GB) | Primary development machine |
| Claude (Anthropic) | Co-writer, shaping engine |
| ElevenLabs | Audiobook voice generation |
| Piper TTS | Local TTS proof of concept |
| GitHub (private repo) | Manuscript storage and version control |
| GitHub (this repo) | Public process documentation |

## Structure Overview

### Volume One — "You Probably Think This Book Is About You"
- 22 noir vignettes (called "scenes")
- 4 interludes between acts
- 6 acts + a spine + a hidden finale
- First draft complete — ~12,800 words
- Audiobook v1 recorded (78 minutes)

### Volume Two — "You Probably Think This Song Is About You Too"
- Structured as an album, not a book
- Scenes are "tracks," pages are "sides," silences are "grooves"
- Side A + Side B
- Bonus tracks, interludes, a hidden track
- In progress

## Credit

Written by Shane Brazelton.
Co-built with Claude (Anthropic).
Built on Raspberry Pi 5 + Pironman 5-MAX.

## Where to Read / Listen

- **Gumroad:** [link coming]
- **Amazon KDP:** [link coming]
- **Audiobook:** [link coming]

## Claude Code Rules
- Commit and push directly to `main`. Do NOT create branches.
- NEVER commit manuscript content to this repo.
- Update this CLAUDE.md if process rules change.

## Ecosystem Status (April 9, 2026)
- Built on **Pi 5** (16GB, Pironman 5-MAX, RAID 1) — all local-first
- **MEGA Crew**: 17 autonomous bots running 24/7, self-improving under the Constitution's 9 Pillars
- **Gemini Strategist** (bot #17): Growth coach calling Gemini 2.5 Flash 4x/day
- **42 MCP tools**, Weaviate + MCP stack, Weaviate RAG with 2,600+ knowledge objects
- Volume One complete, available on Amazon KDP
- Audiobook production pipeline: ffmpeg + ACX specs + pytest validation
