# Software VSL skill

A skill for Claude Code (and Codex) that writes and produces **video sales letters that convert**, not just motion demos that look good.

Right now everyone is using Opus 5.5 to make motion videos. They look great. Most of them won't sell anything, because there's no story, no real demo and no offer.

This skill puts the story first and the motion last.

## Where it comes from

- **Reelocal (2026):** the front-end VSL built with this process. About **4.8%** of tracked sales-page visitors bought at launch.
- **Youzign 2.0 (2016):** I scripted and recorded that launch VSL myself. The launch did around **$100k on day one**.

Built by [Bertrand Diouly](https://x.com/BertrandDiouly).

## What it does

1. **Claims ledger first.** Every price, limit, speed and result gets checked against the real product before a word is written.
2. **Story before motion.** A 12-beat direct-response structure (hook, problem, agitation, mechanism, demo, proof, offer, guarantee, action), adapted for software where the demo often comes early.
3. **Script-only audit.** Read the narration alone, then the on-screen lines alone. Each beat must add meaning.
4. **Beat sheet.** Narration, on-screen line, visual evidence and the claim it supports, per beat.
5. **Voice, then word-timed motion.** Scenes are built from the final audio alignment. Big lines change on spoken beats. The real product UI carries the demo.
6. **QA with sound.** Watch the rendered master end to end, check every claim, caption and splice, then test the actual page player on phone and desktop.

Also covers short upsell (OTO) and downsell videos.

## Install

**Claude Code**
```
git clone https://github.com/bertrand-do/software-vsl-skill.git
cp -R software-vsl-skill/software-vsl ~/.claude/skills/
```

**Codex**
```
cp -R software-vsl-skill/software-vsl ~/.codex/skills/
```

Then ask: *"Use the software-vsl skill to script a VSL for [your product]."*

## Notes

"Ryan Deiss-style" names an influence, not an exact formula. Motion tooling is up to you (Remotion, HyperFrames, After Effects). The skill never publishes, generates paid voice or deploys anything without your say-so.

License: MIT.
