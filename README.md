# ACCEPT Lab → OTTO Lab

The ACCEPT Lab has been renamed the **OTTO Lab** (Observational Target Trial Operations).

- New site: <https://go-bayes.github.io/ottolab/>
- New repository: <https://github.com/go-bayes/ottolab>
- Canonical domain (pending DNS): <https://ottolab.org>

## What this repository is now

This repository is retained only to keep old links and citations working. The published
output in `docs/` is a static redirect to the new site:

- `docs/index.html` redirects the root (`/accept/`) to the new site.
- `docs/404.html` forwards deep links, mapping `/accept/<page>` → `/ottolab/<page>`.

The previous Quarto source is preserved in this repository (and its history). The project
config has been renamed to `_quarto.yml.disabled` so that an accidental `quarto render`
cannot overwrite the redirect. To work on the live lab site, use the
[`ottolab`](https://github.com/go-bayes/ottolab) repository instead.

GitHub Pages continues to serve from `main` → `/docs`; **no Pages setting needs to change.**
