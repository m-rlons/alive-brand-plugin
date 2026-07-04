# alive-brand

ALIVE's brand genome as a Claude Code skill — install it once, and any Claude
session (any project, any machine) can build on-brand ALIVE work: decks,
one-pagers, pitch material, reports, landing pages.

It fetches the live canon from `truly-alive.vercel.app` every time it runs, so
it's never stale and needs no local files.

## Install

```
/plugin marketplace add m-rlons/alive-brand-plugin
/plugin install alive-brand@truly-alive-plugins
```

Run once per machine. After that, mention a deck, pitch, one-pager, or
"make it look like ALIVE" in any session and the skill loads automatically.

## What it does

Reads `/brand/standards.md` (the kernel + the six-step method that births
visual expressions) and `/brand/tokens.json` (exact values), then either
inherits one of the three proof expressions or births a new one for your
content — and self-judges the result against the NEVER register before
handing it back.

See `https://truly-alive.vercel.app/brand/` for the living reference.
