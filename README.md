# Greater Sydney, drawn

Twenty-four Sydney neighbourhoods, drawn by hand. Pick a suburb and watch it drawn.

## View it

Open `index.html` in any browser.

To publish it free with GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`**, then save. It goes live at `https://abutrym2609.github.io/sydney-drawn/`.

## Structure

- `index.html` — the whole site (HTML, CSS and JS in a single file)
- `img/` — 24 illustrations, one per suburb, named `<suburb>.webp`

## The plates

Annandale · Ashfield · Barangaroo · Camperdown · Chippendale · Darlinghurst · Dawes Point · Elizabeth Bay · Forest Lodge · Glebe · Haymarket · Millers Point · Moore Park · Newtown · Paddington · Potts Point · Pyrmont · Redfern · Rushcutters Bay · Sydney · The Rocks · Ultimo · Waterloo · Woolloomooloo

## Editing

- **Add a suburb** — drop `img/<slug>.webp` in, then add `{s:"<slug>", n:"<Name>"}` to the `SUBURBS` list in `index.html`.
- **Opening image** — change `DEFAULT` in `index.html` (currently `"sydney"`).
- **Accent colour, fonts, draw speed** — the `:root` variables at the top of the `<style>` block.
- **Credit line** — the `.rail-foot` block near the end of the HTML.

## Credit

Illustrations — Anastasia Butrym · Sydney · 2026
