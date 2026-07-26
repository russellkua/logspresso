---
tags: [home]
---
# ☕ Logspresso

Set this note as your **Obsidian homepage** (Settings → Core plugins → make sure "Files" starts here, or use the community "Homepage" plugin pointing at `README`).

## 🗺️ Vault map

- **[[Flavour Catalogue]]** — the master catalogue of every pod flavour known (140 flavours across 7 brands), shown as glanceable cards — a colored dot for roast, a green badge once you've tasted it. This is where you add a new flavour or collaboration the moment you spot it, before you've even tasted it.
- **`Tasting Log/`** (folder) — one page per flavour you've actually tasted (18 so far). Each page carries its category info up top and a running table of tasting sessions below, so you can log the *same* flavour again each time you prepare it differently (black, with milk, iced, etc.).
- **`Templates/`** (folder) — copy-paste starting points: [[New Flavour Row]] for adding a line to the [[Flavour Catalogue]], and [[New Tasting Log Entry]] for duplicating into `Tasting Log/` the first time you taste something.

## 🔁 Your workflow

1. **Spot a new flavour or collab** (in a store, online, a gift) → add a line for it in [[Flavour Catalogue]] under the right Brand/Line section. No page needed yet.
2. **Taste something for the first time** → duplicate [[New Tasting Log Entry]] into `Tasting Log/`, rename it to the flavour, fill in the category info, log the session, then go back to [[Flavour Catalogue]], turn its name into a `[[link]]`, and add `tried` to its badge span so it fills in green.
3. **Taste it again, prepared differently** → open its existing page in `Tasting Log/` and add another row to the Tasting Sessions table. Nothing to duplicate — one page per flavour, many sessions.

## 🎨 Card styling

[[Flavour Catalogue]] uses a small CSS snippet (`.obsidian/snippets/flavour-catalogue.css`) to render each flavour as a card with a roast-colored dot and a tried/untried badge, instead of a plain bullet list. It's already enabled by default in this vault's settings — if it ever looks like plain text, go to *Settings → Appearance → CSS snippets* and toggle **flavour-catalogue** on.
