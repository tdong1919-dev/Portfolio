# Portfolio — Crystal Thuy Dong

Selected work as an AI Systems Architect. One self-contained page, no build step
and no dependencies: `index.html` carries its own CSS and its only image inline
as a data URI, so it renders correctly from any static host.

## Case studies

1. **REIDE — Real Estate Investment Decision Engine.** Institutional acquisitions
   platform: a sixteen-stage workflow from deal intake to investment-committee
   memo, over a deterministic underwriting engine and an evidence registry where
   every material number records its own source.
2. **Fintech AI Brain — Capital Relations Engine.** Built solo for Aurumverse.
   Telegram intake, deterministic scoring and routing, an AI concierge with human
   handoff, and KYC-verified account creation. 2,225 leads captured.
3. **Jidoka Core — Agent Factory.** A six-stage factory over a 200-specification
   library covering eleven business functions.

## Publishing with GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → `main` / `root`. The site
then serves at `https://tdong1919-dev.github.io/Portfolio/`.

For a custom domain, add a `CNAME` file containing the domain and point a DNS
record at GitHub Pages.

## Editing

Open `index.html` and edit it directly. Theme tokens are declared once at the top
of the stylesheet — the bare `:root` block holds the light palette, and the two
dark blocks below it redefine only those tokens, so changing a colour in one
place changes it everywhere in both themes.
