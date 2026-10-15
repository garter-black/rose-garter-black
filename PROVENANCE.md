# Provenance of this tree

| File | Copied from | Byte-identical to |
|---|---|---|
| `index.html` | `C:/Hecate-Umbra/WEBSITES/rose.garter.black/` — confirmed as this project's local source by `.wrangler/cache/pages.json`, which names `project_name: "rose-garter-black"` | the bytes `https://rose-garter-black.pages.dev/` serves — sha256 `c345f4dfcabb0031b1a2648802545ce2299c90e9fb1714a049b48f9898cb95fd`, verified 2026-10-16 |

## What was NOT copied, and why

- `assets/` and `samples/` from that same directory — 1.5 MB of images, one mp4 and
  five PDFs. Media is not git (SOURCE-OF-TRUTH-PLAN.md §1). All of it was verified
  live and returning correct content-types on 2026-10-16; see
  decisions/rose-garter-black.md for the status of each URL.
- `C:/Hecate-Umbra/sites/_backup_garter_20261001/source-rose/index.html`
  (78,059 B, sha256 `7a2809530a2a4405...`) — an older, thinner copy. 17 `<h2>`
  against this file's 21, and it is missing the three pay-data SVG charts. Lost on
  content-superset.
- `C:/Hecate-Umbra/sites/garter-black-v2/rose/index.html` (111,921 B) — same page
  but written for the `/rose/` path on the parent host: its canonical, og:url, all
  five PDF links and all four asset paths are `/rose/...`. Publishing that file at
  `rose.garter.black/` produces working-but-dual-canonical content. Lost on
  operator-intent and routability; the differences are itemised in the decision
  record.
- `C:/Hecate-Umbra/sites/garter-black-v3/dist/rose/index.html` (114,467 B) — a
  LATER edit of this same page, and the only candidate that is free of the
  forbidden link, but it was never built from `src/`, it has no git provenance at
  all, and it serves from `garter.black/rose/` rather than from this project. Its
  unique content is preserved instead inside the garter-black repo at
  `recovered-dist/rose/`, which is where a rebuild would find it.

## Hand edits

One sanitised line, recorded in decisions/rose-garter-black.md.
