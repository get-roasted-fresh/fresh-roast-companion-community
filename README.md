# Fresh Roast Companion — Community

Public hub for **Coffee Roast Tracker**: bug reports, feature ideas, and **curated** community recipe files.  
The application source code lives in a **separate private repository**; this repo stays limited to what we want public forever.

## Try the app

Replace the link below with your public deploy URL when ready (for example GitHub Pages or another host):

**[Open Coffee Roast Tracker](https://get-roasted-fresh.github.io/fresh-roast-companion/)** *(update this URL if yours differs)*

## Report a bug

Use **Issues → Bug report** so we get browser, steps, and what went wrong:

**[File a bug](https://github.com/get-roasted-fresh/fresh-roast-companion-community/issues/new?template=bug_report.yml)**

## Request a feature

Use **Issues → Feature request** (ideas are welcome; not every request will ship):

**[Request a feature](https://github.com/get-roasted-fresh/fresh-roast-companion-community/issues/new?template=feature_request.yml)**

## Community recipes (beta)

- **Curated files** live in [`recipes/`](./recipes/). Each JSON should export cleanly from the app (or match its recipe schema).
- **`community-recipes-index.json`** is the machine-readable list used for future **in-app browsing** (metadata + download links). See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for how to add an entry.
- Prefer **small pull requests**: one recipe file + one manifest row + short description.

## Discussions

For **show-and-tell**, general questions, or draft recipe ideas before a PR:

**[Open Discussions](https://github.com/get-roasted-fresh/fresh-roast-companion-community/discussions)**

Please avoid pasting huge JSON blobs in threads—link a [Gist](https://gist.github.com/) or open a PR against `recipes/` instead.

## Ground rules

- [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md) — be respectful and on-topic.
- [`SECURITY.md`](./SECURITY.md) — how to report sensitive issues; do not post secrets.
- [`RECIPE_LICENSE.md`](./RECIPE_LICENSE.md) — licensing for recipe files shared here.
- [`CONTRIBUTING.md`](./CONTRIBUTING.md) — how to contribute recipes and manifest entries.

## License

Repository text and templates are under the root [`LICENSE`](./LICENSE) (MIT). **Recipe JSON** may use a different license per file; see **RECIPE_LICENSE.md** and the header comment or sidecar you attach in your PR.
