# ALIVE Standards — the DNA

**Version 2.1 · 2026-07-04 · served at `/brand/standards.md`**

This is not a style guide. It is the brand system's canon — and the system has **three layers. Deciding which layer an artifact belongs to is the FIRST design decision**, before anything in this file applies:

| Layer | What | Where | Governs |
|---|---|---|---|
| **1 · The house** | Who ALIVE is — the studio of light and glass: deep canvas, zinc chrome, glass surfaces, chromatic light as the carrier of the machine working, spacious variable DM Sans + mono codes, living motion, both hours | [/brand/](/brand/) | **Every artifact that speaks AS ALIVE** — the app, the seed deck, pitch pages, the landing, docs about ALIVE itself |
| **2 · The craft laws** | The kernel (§1) + NEVER (§5) — what keeps anything we ship from being slop | this file | Everything, house or generated |
| **3 · The engine** | The six-step method (§2) that births fully-opinionated expressions; three proofs at [/brand/directions/](/brand/directions/): THE DIAL, SHOWROOM, TRANSMISSION | §2–§4 of this file | **Produced and client artifacts** — lookbooks, client decks, generated deliverables, customer brands (§7) |

The engine is the point of §2 onward: an expression is a complete, self-consistent visual world, and the three proofs look nothing alike while every one is unmistakably ALIVE. That variability is a **product capability** — what ALIVE constructs for the things it produces. It is not a license to re-costume ALIVE's own identity: **an artifact that speaks as ALIVE wears the house, never an engine world.** (This confusion shipped a company deck in a generated world once. Layer first, then method.)

**Consume it:**

| You are | Do this |
|---|---|
| An agent making a visual artifact | **Decide the layer first.** Speaks as ALIVE → the house ([/brand/](/brand/)); judge against §1 + §5. Produced/client artifact → inherit an expression (§3) or birth one (§2); judge against §1 + §5. |
| A teammate building anywhere | Fetch `https://truly-alive.vercel.app/brand/standards.md`. The house is live at `/brand/`; the proof expressions at `/brand/directions/`. |
| Claude Code in this repo | The `alive-brand` skill runs this decision + method automatically. |
| A renderer serving a customer brand | Same method, different kernel — see §7. |

**Precedence:** this document plus the house page govern new work. Where the shipped app disagrees, the app predates the house's articulation and is migration debt, not canon (§8) — the exception is engineering truth (tokens.css values, component APIs), which stays authoritative until the app's migration to the house completes.

**Motion voicing per layer:** K4's machined physics are the engine's law verbatim. The house voices motion as **living** — settle, blur-to-focus, breathe, drift — declared on [/brand/](/brand/) §04; that page is the authority for house motion. The shared invariant across layers: motion is designed and purposeful, never bounce, never decoration.

---

## 1. The kernel — invariants that make anything ALIVE

These never vary. Every expression, however wild, obeys all ten. This is the DNA test: strip any one of these and the artifact stops being ours, no matter how good it looks.

**K1 · Precision-instrument soul.** Craft carried inside engineering — the Patek principle. Restraint outside, richness exactly where it counts. If it doesn't feel machined AND cared for, it fails.

**K2 · One meaning-carrier per view.** Exactly one saturated element, and it is semantically loaded — a decision made visible. In the proofs: a seconds hand, an entire room, a rubber stamp. The red family (oxblood `#6b1420` → signal `#b3241c`) is the house carrier. Color is never decoration; when everything is quiet, one red thing means something.

**K3 · Cool field.** Cold papers, metals, onyx, ink. Warmth may exist only as material depth — oxblood, burl, walnut — never as atmosphere. No golden-hour washes, no warm grain, no honey light.

**K4 · Machined motion.** Four moves: **cut** (1ms, `steps(1)`) · **tick** (120ms, `cubic-bezier(.4,0,.15,1)`) · **seat** (180ms, `cubic-bezier(.3,0,0,1)`) · **sweep** (400ms, `cubic-bezier(.6,0,.2,1)`, at most one per surface). Hard stops. No bounce, no blur-fades, no drift, no wobble after landing. Loops are continuous rotation only. Each expression may *voice* these differently (crown click, bearing roll, stamp thunk) but the physics are fixed.

**K5 · Argued faces.** Every typeface can say why it exists — a manifesto, a commission, a history. Faces are cast per expression like actors. The era's defaults (Inter-class, SF-class, the AI-startup serif of the month) are disqualified by definition.

**K6 · Micro-reference discipline.** Mono codes, coordinates, plate numbers, calibres — metadata as ornament, small and everywhere. The artifact knows its own reference number.

**K7 · The demo is the exhibit.** Surfaces enact their own laws instead of describing them. The dial renders the tokens; the bearing rolls the actual curve; the text de-redacts as the system delivers. Never explain what you can enact.

**K8 · Craft spends in two places.** The moments the machine is working (AI presence) and the objects it produces (posters, credits, decks, releases). The shell stays quiet so the work is the loudest thing in the room.

**K9 · Dual hour, designed twice.** Night is the same world with the lights off — the instrument at night, the gallery after close, the photostat negative. Never a palette inversion.

**K10 · The wow budget.** Two or three concentrated moments per artifact. Build the zero-effects version first; if the bare structure doesn't hold, no effect saves it.

---

## 2. The method — how an expression is born

Six steps. The output of each is written down, not implied. This method is why three totally different pages all read ALIVE — and it is how the next thirty will.

**Step 1 — World.** Choose a metaphor-world for the artifact, derived from its content: what IS this thing, taken literally? The proofs chose an instrument's dial face, a gallery of material, a classified dossier. Candidate worlds are unlimited — a broadcast control room, an atelier, an observatory, a pressing plant, a flight-ops board, a foundry. The world must pass the anti-mean test: could it belong to any brand, or only to a precision-instrument studio that makes things real?

**Step 2 — Law.** Derive the composition law FROM the world, and write it at the top of the artifact. What is a section in this world (a room, a leaf, a plate)? What is a caption (a didactic, a corner code, an engraving)? What is loading? What is an error? What is the grid, and where does the world break it? Every element on the surface must have a name in the world. If an element has no name, it's imported scaffold — delete it.

**Step 3 — Cast.** Cast the argued faces: a display voice, a working voice, a code voice — each with a written why. (Proofs: Marcellus/B612/B612-Mono because cockpit; Anybody/Archivo/Fragment-Mono because supergraphics and didactics; Redaction/Karrik/Space-Mono because the erasure IS the argument.)

**Step 4 — Carrier.** Decide what red IS in this world (K2). A needle? A room? A seal? A live wire? One answer, then enforce singularity per view.

**Step 5 — Spend.** Place the 2–3 wow moments, derived from the world's own physics — never imported from another expression. De-redaction belongs to the dossier; guilloché belongs to the dial. A new world earns new moments.

**Step 6 — Judge.** Read the built artifact against K1–K10 and the NEVER register (§5), citing specifics — including *adjacent* violations of each ban's why. Fix before delivery. No caveats shipped.

---

## 3. The proof expressions

Three worked examples of the method — live, inheritable, and open for any artifact whose content fits their world. Inheriting means obeying that expression's law, not sampling its surface.

| | A · THE DIAL | B · SHOWROOM | C · TRANSMISSION |
|---|---|---|---|
| **World** | A precision instrument's face | A cold material gallery | A classified technical dossier |
| **Law** | Calm metal field; information bands; micro-captions under everything; rigorous symmetry inside instruments, asymmetric placement on the page | One exhibit per room; color arrives as rooms; supergraphics bleed off walls; captions are humble didactics bottom-left | Center-stacked type, hierarchy by whitespace gap; coordinates at corners; glyph fields with dropouts; one ink accident |
| **Cast** | Marcellus · B612 · B612 Mono (cockpit certification) | Anybody · Archivo · Fragment Mono (supergraphic + archive) | Redaction · Karrik · Space Mono (the erasure is the argument) |
| **Carrier** | The oxblood seconds hand — one thin red element | The room itself — signal-red type room, oxblood NEVER room | The stamp — the mark of a decision |
| **Motion voice** | Crown click | Bearing roll, dolly between rooms | Cut + stamp thunk |
| **AI presence** | Engine-turned guilloché, lume at night | Chrome turning under the spot | De-redaction — text resolving grade 100 → clean |
| **Night** | Onyx dial, lume numerals | Lights down, exhibits take the spot | Photostat negative |
| **Lives at** | `/brand/directions/dial/` | `/brand/directions/showroom/` | `/brand/directions/transmission/` |

---

## 4. Variability — what moves, what never moves

| Axis | May vary per expression | Never varies |
|---|---|---|
| World & composition law | Freely — that's the point | An element with no name in the world |
| Type cast | Freely, with written whys | Unargued/default faces (K5) |
| Palette expression | Which metals, which papers, how dark | Cool field (K3); red-family carrier (K2) |
| Motion voice | The metaphor (click/roll/thunk) | The physics: cut/tick/seat/sweep, hard stops (K4) |
| Wow moments | Derived fresh from each world | The budget: 2–3 (K10); craft placement (K8) |
| Hour | What "lights off" means in the world | Both hours designed (K9) |
| Metadata style | Coordinates, calibres, plate numbers | Their presence (K6) |

---

## 5. NEVER — kernel-level bans

Each carries its why so the ban generalizes; an agent refuses the adjacent violation too. When a ban and a fresh director instruction conflict, the director wins and this file updates.

| # | Never | Why |
|---|---|---|
| N1 | Sparkle glyphs, AI-magic iconography | Claims, not functions |
| N2 | Clicks that answer with nothing; feedback that flashes and vanishes | Trust dies in the gap between click and consequence — in-place, persistent state until resolution |
| N3 | Dev-tool minimalism (Linear/Vercel school) | The tasteful, interchangeable uniform of 2026 software |
| N4 | AI-startup slop — gradient orbs, purple-blue glows, "magic" everywhere | The category's default costume |
| N5 | Apple-clone polish | Premium by imitation, anonymous by definition |
| N6 | Luxury pastiche — serif, gold, marble cosplay | The look of luxury without the engineering underneath |
| N7 | Warm-atmosphere washes; golden-hour grain | The field is cool (K3); warmth is material, not weather |
| N8 | Bounce, blur-fades, drift; linear tweens outside continuous rotation | The physics are machined (K4) |
| N9 | A second saturated element in the same view | The carrier is singular or it means nothing (K2) |
| N10 | Sampling another expression's surface without inheriting its law | Surfaces without laws are costume — the mean in ALIVE's clothes |
| N11 | Hardcoded values where tokens exist | Brand drift with a head start |
| N12 | Marketing-speak, three-adjective stacks, fake questions, excitement | We're confident, not excited |
| N13 | Stock imagery that reads as stock; recycled chrome as stand-in media | If it looks rented, it is |
| N14 | Explaining what can be enacted | The demo is the exhibit (K7) |
| N15 | Cinematic voice on utility surfaces | Utility serves speed |
| N16 | Job errors in toasts or chat; loaders covering existing assets | Errors surface at the trigger point; editing shows a ring, the asset stays visible |

---

## 6. Registers — how loud an expression may run

Registers are artifact classes; they set voice and volume, not the world.

- **R1 · Product UI** — the working instrument. Kernel at its quietest: information seated in bands, craft only at AI-presence moments. *The app's own expression is not yet born — it will be produced by the §2 method as its own project, then the app migrates to it.*
- **R2 · Public editorial** — posters, decks, releases, pitch, 10-K. Full volume; the craft budget spends here. **The world comes from the layer:** ALIVE's own editorial (the seed deck, pitch, releases about ALIVE) runs the house at full volume; produced/client editorial (lookbooks, client decks, generated deliverables) runs an engine expression.
- **R3 · Internal artifacts** — plans, reports, memos. An expression at documentary volume: exact, sourced, plain language, no marketing voice. TRANSMISSION is the natural fit but not the law.

---

## 7. Instancing — other brands, same method

ALIVE's kernel (§1) is instance №1. A customer brand gets its own kernel — its own invariants, carriers, physics — authored by the same six-step method, stored on `productions.brand` / `BrandProfileService`, rendered by the same pipeline. We don't sell a template; we sell the genome authoring.

---

## 8. Files, endpoints, roadmap

| Thing | Where |
|---|---|
| The house (layer 1) | `public/brand/index.html` → `/brand/` |
| This canon (layers 2–3) | `public/brand/standards.md` → `/brand/standards.md` |
| Proof expressions (layer 3) | `public/brand/directions/{dial,showroom,transmission}/` → `/brand/directions/` |
| Self-hosted argued faces | `public/brand/fonts/` (Redaction, Karrik — OFL) |
| App tokens (pre-DNA engineering truth) | `styles/tokens.css` — mirrored at `/brand/tokens.json` via `pnpm tokens:sync` |
| Claude skill | `.claude/skills/alive-brand/` |
| Per-production brand instances | `services/BrandProfileService.ts`, `productions.brand` |

**Roadmap:** kernel tokens (the machined timing family + red carriers + cool fields as data) → birth the register-1 expression and migrate the app → expression library grows per artifact (changelog, decks, 10-K) → brand MCP → customer kernel authoring.

**Versioning:** material changes bump the version. Artifacts citing the genome cite the version. v1 (2026-07-03, same day) documented the incumbent look and was rejected — kept in git history as the cautionary tale: documenting a style is not designing a genome.
