# tacosnorkel.com

Static site for tacosnorkel, served by GitHub Pages from `main` (root).
Plain HTML and CSS, no build step, no trackers.

- `/` home, features FRDG
- `/frdg/privacy/` FRDG privacy policy (linked from Google Play; keep this URL stable).
  Source of truth is `docs/privacy.md` in the FRDG repo; update both together.
- `/frdg/` FRDG page (the share link in the game points here): banner, screenshots (`img/frdg/`, from the store listing at 2x), store link, privacy, terms, accessibility (the game's "?" page points here)
- `/frdg/terms/` FRDG terms of use. Source of truth is this page.
- `/accessibility/` accessibility statement for the site and FRDG. Keep it in step with the
  game's settings (FRDG `scripts/sim/prefs_rules.gd`) and its known gaps.
- `CNAME` custom domain

Every page has the same footer links (FRDG, Privacy, Terms, Accessibility, Contact).
Public contact is info@cloudsnorkel.com.
