# Track Release Checklist

> When a Volume Two track locks, run this checklist. Every locked track is a campaign event.

## Pre-Lock

- [ ] Track shaped from raw voice dump
- [ ] Shane reviewed and approved final prose
- [ ] Callbacks to Volume One verified (echoes, not repetition)
- [ ] No manuscript text committed to public repos

## Lock

- [ ] Track marked as LOCKED in volume-two manifest
- [ ] Audio clip generated via ElevenLabs (30-second preview)
- [ ] Best excerpt pulled (2-3 sentences, no spoilers)

## Promo Pipeline

### Content Library Update (mini-shanebrain)
- [ ] Add teaser to `content/teasers.json`:
  ```json
  {
    "id": "teaser-XXX",
    "title": "Track [NUMBER]: [TITLE]",
    "text": "[EXCERPT]",
    "hashtags": ["volumetwo", "noir", "[tracktag]"]
  }
  ```
- [ ] Add behind-scenes note to `content/behind-scenes.json`

### Discord (24-hour exclusive)
- [ ] Post rich embed in `#track-drops`:
  - Track title and number
  - 2-3 sentence teaser
  - "Exclusive — hits other platforms tomorrow"
- [ ] Pin if it's a milestone track (Side A complete, The Flip, etc.)

### All Platforms (next day)
- [ ] X/Twitter: Punchy teaser + #volumetwo
- [ ] Facebook: Track title + description + "Volume 2 is being written in real time"
- [ ] Reddit: Behind-the-scenes of this track's creation (value-first, not promo)
- [ ] LinkedIn: Creative process angle
- [ ] Bluesky: Mirror X post
- [ ] Instagram: Quote card image + teaser caption

### Email
- [ ] Fill in Track Drop email template (Gmail draft exists)
- [ ] Send to subscriber list

### Documentation
- [ ] Update `campaign/VOLUME-TWO-PIPELINE.md` track status table
- [ ] Update `case-study/NUMBERS.md` if metrics available
- [ ] Note in noir-detective-writing-process what was learned

## Milestone Tracks (Bigger Push)

These tracks get amplified treatment:

| Track | Event | Extra Actions |
|-------|-------|---------------|
| First track to lock | "Volume 2 is real" | Reddit AMA, LinkedIn long-form, all platforms same day |
| Side A completion | "Side A is done" | Compilation teaser, Discord listening party |
| Track 003 (The Flip) | The biggest reveal | Tease but don't explain, cryptic posts |
| Hidden Track | "After the silence" | Don't announce — let it be discovered |
| Album Complete | Full V2 launch | Bigger than V1 launch — the audience exists now |

## What NOT to Reveal

- The exact moment of The Flip
- The hidden track's content
- Any complete track text
- The full Side B structure before it drops

**Sell the mystery. The answer is for the reader.**
