# Contributing

## Bugs and features

- **Bugs:** use the **Bug report** issue template (browser, steps, expected vs actual).
- **Features:** use the **Feature request** template. Requests are triaged; timelines are best-effort.

## Community recipes

### What we accept

- JSON that **imports cleanly** into Coffee Roast Tracker (single recipe object), or matches the documented recipe shape.
- Clear **title**, sensible **id** (stable slug), and **machine/batch** hints in the manifest entry.
- Prefer **versioned filenames** (example: `sr540-city-plus-120g-v1.json`) so updates do not silently change behavior for people who already downloaded a file.

### Steps to add a recipe

1. Fork this repository (or branch if you are a maintainer).
2. Add your file under **`recipes/`**.
3. Add one object to **`community-recipes-index.json`** (see fields in that file; keep `indexSchema` at `1` unless the schema version bumps).
4. Open a **pull request** describing:
   - License (default **CC BY 4.0** per **RECIPE_LICENSE.md** if you do not specify otherwise)
   - Attribution name
   - Anything special about the curve (display temps vs bean probe, etc.)

### `recipeUrl` vs `recipePath`

- Prefer **`recipePath`** pointing at `recipes/your-file.json` when the file lives in this repo. The manifest’s **`baseUrl`** is set to the **`main` branch on GitHub raw content** so downloads work **without** turning on GitHub Pages. If you later switch to Pages on the same origin as the app, update `baseUrl` once and re-test all `recipePath` entries.
- Use **`recipeUrl`** only when the JSON is hosted elsewhere over **HTTPS**.

### After merge

Maintainers may occasionally reorder the manifest or tweak summaries for clarity. The recipe file itself should change only via **new versions** (new filename) unless fixing a clear export bug.
