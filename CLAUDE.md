# tb-pages

> **`tb-pages` — one domain in Thomas's `~/repos` workspace.**
> **Owns:** Thomas's personal published pages & projects (public GitHub Pages). Personal, not brand-related.
> Master cross-repo rules & area map: `~/repos/CLAUDE.md` (source: `systems/repos-CLAUDE.md`). Keep out-of-scope work in its home repo.
> **Sync:** `syncpull` at session start · `syncpush` after edits (`dbpush`/`ilypush` brand-scoped, `dbs` status) — see `~/repos/SYNC-GUIDE.md`.
> **Cowork:** Claude edits files (they sync to disk) but does **NOT** run git — not even read-only; any git command in the Cowork mount strands `.git/index.lock` (fix: `rm -f .git/index.lock`). Thomas runs the sync commands.

## What this is

Thomas's personal published pages and projects, served via GitHub Pages at https://thomasbrown-personal.github.io/tb-pages. Personal, not tied to Dutton Brown or iloveyouth — keep brand work in its own repo.

## Structure

- `swiftbladefelix/` — SwiftBladeFelix website
- `health-dashboard/` — personal health dashboard
- `relationships/` — personal project
- `index.html` — landing page
- `README.md`

## Show Your Work

**Show Thomas whatever you make, in the same turn, without being asked.** A file path is not a deliverable — if he has to ask "how do I look at this?", it wasn't delivered.

- Image / screenshot / chart / render → read it back so it renders inline
- Video / audio / several files → build a small local `review.html` that plays them all, then `Start-Process` it
- HTML page / dashboard / prototype → open it in the browser; publish an Artifact if it should be shareable
- Report / analysis → lead with the findings in the response, don't just link the file
- Data / query result → show the actual numbers, formatted

Then open it yourself and confirm it renders. Full rule: `~/repos/CLAUDE.md` → Show Your Work Rule.
