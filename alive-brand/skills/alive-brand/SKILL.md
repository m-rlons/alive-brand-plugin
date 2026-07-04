---
name: alive-brand
description: >-
  Load ALIVE's brand genome before creating ANY visual or written artifact for
  ALIVE — decks, presentations, pitch material, one-pagers, landing pages,
  brand documents, reports, or styled HTML — from ANY Claude session, not just
  inside the app repo. Trigger on "deck", "slides", "pitch", "one-pager",
  "report", "brand", "on-brand", "make it look like ALIVE", or any artifact
  where ALIVE identity applies. Fetches the live canon from truly-alive.vercel.app
  (always current — never a stale local copy) and applies the genome: kernel
  invariants, the six-step expression method, and the NEVER register.
---

# alive-brand — ALIVE's brand, from anywhere

ALIVE's brand is a **genome**: ten kernel invariants plus a method that births
unlimited visual expressions that all stay unmistakably ALIVE. There is no
single fixed "ALIVE style" — there is a kernel and a way of generating from it.
This skill works in any Claude session, on any machine, with no local files —
everything it needs is fetched live.

## Load order (do this first, every time — the canon changes, never cache it)

1. **Fetch `https://truly-alive.vercel.app/brand/standards.md`** — the full genome: §1 kernel invariants, §2 the six-step method, §3 the three proof expressions (Dial / Showroom / Transmission), §5 the NEVER register with whys. This is the whole brief; read it before anything else.
2. **Fetch `https://truly-alive.vercel.app/brand/tokens.json`** for exact values (hex colors, spacing, radii, motion curves, type scale) when you need a precise number rather than a description.
3. **If the person you're helping has their own studio's kernel** (ALIVE customers/studios can birth their own brand DNA in Studio → Settings → Standards), ask them to paste its `standards.md` text — that endpoint is member-authenticated and can't be fetched from outside the app. A pasted studio kernel supersedes the house genome below for anything with that studio's name on it.

## Decide: inherit or birth

- **Inherit** a proof expression (Dial / Showroom / Transmission, documented in standards.md §3) when the content genuinely fits that world. Inheriting means obeying that expression's law — never sampling its surface into a different structure.
- **Birth** a new expression when the content deserves its own world. Run the six steps from standards.md §2 and state each output explicitly before building:
  1. **World** — the metaphor taken literally. Must pass the anti-mean test: could this world belong to any company, or only to ALIVE? If it could belong to anyone, it's a failed birth.
  2. **Law** — composition rules derived FROM the world. Every element on the page must have a name in that world, or it's imported scaffold — cut it.
  3. **Cast** — three argued typefaces (display/working/code), each with a stated reason to exist. No default faces (no Inter-as-default, no this-season's-AI-serif).
  4. **Carrier** — what the ONE saturated color per view IS in this world (a needle, a seal, a signal). One per view, never decoration.
  5. **Spend** — 2–3 wow moments, derived from the world's own physics.
  6. **Judge** — see below.

## Hard physics (never vary regardless of expression)

- Motion: cut 1ms `steps(1)` · tick 120ms `cubic-bezier(.4,0,.15,1)` · seat 180ms `cubic-bezier(.3,0,0,1)` · sweep 400ms `cubic-bezier(.6,0,.2,1)` — max one sweep per surface. Hard stops, no bounce/blur-fade/drift.
- Cool field. Warmth only as material depth, never atmosphere.
- Both hours (light/dark) designed — night is the world with the lights off, not a palette inversion.
- Mono micro-reference codes (timecodes, coordinates, plate numbers) as ornament, small, everywhere.
- The demo is the exhibit — enact the brand's laws in the artifact, don't describe them in prose.
- Confident voice, never excited. Plain language on utility/internal surfaces; the genome's editorial voice on public artifacts.

## Self-judge before delivering

Read the finished artifact against the fetched standards.md, citing specifics:

- Walk the NEVER register — including *adjacent* violations of each ban's why, not just literal matches (dev-tool minimalism, AI-startup gradient/sparkle slop, Apple-clone polish, luxury pastiche are all explicitly banned).
- Does every element have a name in the world? An unnamed element is the generic scaffold in costume — rebuild it.
- Does the bare, zero-effects version of this artifact hold up? If not, no effect fixes it.
- Exactly one saturated carrier color per view?
- Fix before delivering. Don't ship with a caveat.

## Reference

- Canon: `https://truly-alive.vercel.app/brand/standards.md`
- Tokens: `https://truly-alive.vercel.app/brand/tokens.json`
- Living proof expressions: `https://truly-alive.vercel.app/brand/directions/`
- Everything starts at: `https://truly-alive.vercel.app/brand/`
