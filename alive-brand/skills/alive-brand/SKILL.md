---
name: alive-brand
description: >-
  Load ALIVE's brand system before creating ANY visual or written artifact for
  ALIVE — decks, presentations, pitch material, one-pagers, landing pages,
  brand documents, reports, or styled HTML — from ANY Claude session, not just
  inside the app repo. Trigger on "deck", "slides", "pitch", "one-pager",
  "report", "brand", "on-brand", "make it look like ALIVE", or any artifact
  where ALIVE identity applies. The brand has THREE LAYERS: the house (who
  ALIVE is), the craft laws (kernel + NEVER), and the engine (the method that
  births expressions for produced/client work). Decide the layer FIRST —
  artifacts that speak as ALIVE wear the house, never a generated world.
---

# alive-brand — ALIVE's brand, from anywhere

The ALIVE brand system has three layers. **Deciding which layer an artifact
belongs to is the first design decision:**

- **Layer 1 — the house** (`/brand/`): who ALIVE is. The studio of light and
  glass. **Every artifact that speaks AS ALIVE** — the seed deck, pitch,
  landing, docs about ALIVE — wears the house. Never an engine world.
- **Layer 2 — the craft laws** (standards.md §1 kernel + §5 NEVER): judge
  everything against them, house or generated.
- **Layer 3 — the engine** (standards.md §2 method; proofs Dial / Showroom /
  Transmission): fully-opinionated generated worlds for **produced and client
  artifacts** — lookbooks, client decks, deliverables, customer brands.

## Load order (do this first, every time)

The full canon ships WITH this skill — no login, no network needed:

1. **Read `canon/standards.md`** (in this skill's directory) — layers 2–3:
   §1 kernel invariants, §2 the six-step method, §3 the three proof
   expressions (Dial / Showroom / Transmission), §5 the NEVER register with
   whys. This is the whole brief; read it before anything else.
2. **Read `canon/tokens.json`** when you need an exact value (hex colors,
   spacing, radii, motion curves, type scale) rather than a description.
   `canon/kernel.json` is the machine-readable kernel.
3. **In the app repo itself** (`truly-alive`), prefer the live source:
   `public/brand/standards.md` + `public/brand/tokens.json` from the checkout.
4. **If your session can fetch URLs**, the always-current canon mirror is
   `https://raw.githubusercontent.com/m-rlons/alive-brand-plugin/main/alive-brand/skills/alive-brand/canon/standards.md`
   (same path for `tokens.json` / `kernel.json`) — use it if you suspect the
   installed copy is stale.
5. **Customer/studio kernels** (ALIVE studios can birth their own brand DNA in
   Studio → Settings → Standards): ask for the studio's `standards.md` text —
   a pasted studio kernel supersedes the ALIVE house for anything with that
   studio's name on it.

## The house (layer 1 — artifacts that speak as ALIVE)

From `/brand/`'s own law: deep cinematic canvas (`#08080a` night / `#fafafa`
day), ~90% zinc chrome, glass planes (translucent + `blur(20px)
saturate(1.4)` + hair border — never flat cards where glass belongs),
**chromatic light as THE carrier** (cyan/teal/indigo/violet additive light
marks the machine working; nothing else wears it), spacious variable DM Sans
(light display ~220 with `<b>` ~560 as the emphasis — never flat-bold walls)
+ JetBrains Mono codes, living motion (settle `cubic-bezier(.16,1,.3,1)`,
blur-to-focus entrances, breathe, drift — no bounce), both hours designed,
mono micro-codes as ornament.

## Inherit or birth (layer 3 — produced/client artifacts)

- **Inherit** a proof expression (Dial / Showroom / Transmission, standards.md
  §3) when the content genuinely fits that world. Inheriting means obeying
  that expression's law — never sampling its surface into a different
  structure.
- **Birth** a new expression when the content deserves its own world. Run the
  six steps from standards.md §2 and state each output explicitly before
  building:
  1. **World** — the metaphor taken literally. Must pass the anti-mean test.
  2. **Law** — composition rules derived FROM the world. Every element must
     have a name in that world, or it's imported scaffold — cut it.
  3. **Cast** — three argued typefaces (display/working/code), each with a
     stated reason to exist. No default faces.
  4. **Carrier** — what the ONE saturated color per view IS in this world.
  5. **Spend** — 2–3 wow moments, derived from the world's own physics.
  6. **Judge** — see below.

## Hard physics (engine kernel — never vary across expressions)

- Motion: cut 1ms `steps(1)` · tick 120ms `cubic-bezier(.4,0,.15,1)` · seat
  180ms `cubic-bezier(.3,0,0,1)` · sweep 400ms `cubic-bezier(.6,0,.2,1)` —
  max one sweep per surface. Hard stops, no bounce. (The HOUSE voices motion
  as living — settle/blur-to-focus/breathe/drift — per `/brand/` §04; the
  shared invariant: designed and purposeful, never bounce, never decoration.)
- Cool field. Warmth only as material depth, never atmosphere.
- Both hours designed — night is the world with the lights off, not a
  palette inversion.
- Mono micro-reference codes (timecodes, coordinates, plate numbers) as
  ornament, small, everywhere.
- The demo is the exhibit — enact the brand's laws in the artifact, don't
  describe them in prose.
- Confident voice, never excited. Plain language on utility/internal
  surfaces; editorial voice on public artifacts.

## Self-judge before delivering

Read the finished artifact against the canon, citing specifics:

- Confirm the layer call: speaks as ALIVE (house) vs produced/client
  (engine). Wrong layer = rebuild, not restyle.
- Walk the NEVER register — including *adjacent* violations of each ban's
  why, not just literal matches (dev-tool minimalism, AI-startup
  gradient/sparkle slop, Apple-clone polish, luxury pastiche all banned).
- Engine work: does every element have a name in the world? An unnamed
  element is generic scaffold in costume — rebuild it.
- Does the bare, zero-effects version of this artifact hold up?
- Exactly one saturated carrier per view? (House: chromatic light marks the
  machine working, nothing else wears it.)
- Fix before delivering. Don't ship with a caveat.

## Reference

- Canon (bundled): `canon/standards.md` · `canon/tokens.json` · `canon/kernel.json`
- Canon (live mirror): `https://raw.githubusercontent.com/m-rlons/alive-brand-plugin/main/alive-brand/skills/alive-brand/canon/`
- The living house + proof expressions: `truly-alive.vercel.app/brand/` and
  `/brand/directions/` (internal-only — signed-in @alive.inc; optional, the
  bundled canon is sufficient to build)
