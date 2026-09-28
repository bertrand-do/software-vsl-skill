# VSL production and motion

## Plan the evidence before animation

Create a beat sheet containing narration, on-screen line, visual evidence, approximate duration, claim supported, and source. Capture current product states only after confirming that the script and UI agree. Label fixture or example data honestly. Never expose customer data, credentials, or live keys.

Use a small visual system: two type roles, a restrained palette, consistent safe margins, and a few repeatable scene types. One effective software VSL used short editorial headlines, real product crops, a high-contrast accent/neutral palette, and scene types for intro, problem, reveal, demo, resources, guarantee, offer, and CTA. These are useful patterns, not required branding.

## Animate the big lines

- Split on-screen headlines into one to three short lines. Each line should carry a complete, concrete thought.
- Enter lines sequentially with fast, damped motion; use scale, opacity, or horizontal movement consistently.
- Highlight one decisive line or word with the accent color. Avoid coloring every benefit.
- Anchor visual changes to actual spoken-word timings rather than arbitrary seconds.
- Keep copy readable after its entrance. Motion should mark a beat, reveal evidence, or guide focus.
- During demos, let the UI dominate. Use camera crops or pans to focus attention without hiding the state needed to verify the claim.
- When the finished output is the strongest proof, play it unobstructed. Pause narration and preserve its own sound long enough for the viewer to judge it.
- Respect title-safe areas, captions, mobile scaling, and reduced-motion behavior in the surrounding player.

## Narration and timeline

Preserve exact narration inputs, voice/model settings, provider request IDs, returned alignment, audio hashes, and generation status. One owner should handle paid generation. Resume completed or uncertain jobs; never delete metadata to force a fresh charge.

When revising an existing narration, regenerate only changed sentences when the voice supports clean splicing. Include adjacent text as prosody context. Listen to every seam and replace the whole paragraph only when the sentence splice remains audible.

Build scene duration from the final audio alignment. If sections are cut, update audio, word timings, captions, timeline hosts, animation anchors, music ducking, and final fade together. Old offsets become invalid after an upstream edit.

## Verification

- Run the composition's type, asset, and render checks.
- Inspect frames from the rendered master, not only development snapshots.
- Watch with sound from beginning to end; listen at every splice and transition.
- Verify captions against final audio and visible claims.
- Confirm no black gaps, clipped lines, stale frames, drift, missing fonts, or unreadable demo crops.
- Measure streams, dimensions, runtime, loudness, peaks, file size, and hashes when relevant.
- Test the actual page player: explicit sound start, restart behavior, native controls, captions, escape/close, viewport pause, poster, reduced motion, desktop, and phone width.
- Preserve a high-quality master separately from the web encode.

Animation can make a clear script easier to follow; it cannot rescue vague writing. Complete a script-only editorial pass before investing in motion or paid voice generation.

## Working evidence

The production lessons come from building the Reelocal front-end VSL (a 2:08 demo-led video; about 4.8% of tracked sales-page visitors bought at launch) and two upsell videos, plus a comparison study of live software-launch VSLs. They are practice-derived rules, not a universal formula.
