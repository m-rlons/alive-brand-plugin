# alive-brand

ALIVE's brand system as a Claude Code plugin — install it once, and any Claude
session (any project, any machine) can build on-brand ALIVE work: decks,
one-pagers, pitch material, reports, landing pages.

The full canon (standards, tokens, kernel) ships inside the plugin. No login,
no network, nothing else to set up.

## Install (Claude Code)

Run these two commands inside Claude Code, once per machine:

```
/plugin marketplace add m-rlons/alive-brand-plugin
/plugin install alive-brand@truly-alive-plugins
```

After that, mention a deck, pitch, one-pager, or "make it look like ALIVE" in
any session and the skill loads automatically. To restyle something existing:

> Restyle this deck as ALIVE.

## No Claude Code? (claude.ai, or any other Claude)

Paste this into your chat:

> Fetch https://raw.githubusercontent.com/m-rlons/alive-brand-plugin/main/alive-brand/skills/alive-brand/SKILL.md
> and follow it. The canon it references is at
> https://raw.githubusercontent.com/m-rlons/alive-brand-plugin/main/alive-brand/skills/alive-brand/canon/standards.md
> and .../canon/tokens.json. Then restyle: [your thing]

## What it does

The brand has three layers, and the skill decides the layer first: the house
(artifacts that speak AS ALIVE), the craft laws (kernel + NEVER register),
and the engine (the method that births a fully-opinionated world for
produced/client artifacts). It reads the bundled `canon/standards.md` and
`canon/tokens.json`, builds, then self-judges the result against the NEVER
register before handing it back.

## Updating the canon

The canon here is synced from the `truly-alive` app repo by
`scripts/publish-brand-plugin.sh`. If you installed the plugin a while ago,
re-run `/plugin install alive-brand@truly-alive-plugins` to pick up the
latest.
