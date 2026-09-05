# Greater Sydney, drawn

106 Sydney neighbourhoods, drawn by hand. Pick a suburb and watch it drawn.

## View it

Open `index.html` in any browser.

To publish it free with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `/ (root)`**, then save. It goes live at `https://abutrym2609.github.io/sydney-drawn/`.

## Structure

- `index.html` — the whole site (HTML, CSS and JS in a single file), with a live search box
- `img/` — 106 illustrations, one per suburb, named `<suburb>.webp`

## The plates (106)

Abbotsford · Airds · Annandale · Artarmon · Ashfield · Auburn · Avalon Beach · Badgerys Creek · Balmain · Balmain East · Bankstown · Barangaroo · Bellevue Hill · Berowra Waters · Birchgrove · Blacktown · Bondi · Bondi Beach · Bondi Junction · Breakfast Point · Bronte · Burwood · Cabarita · Cammeray · Camperdown · Canada Bay · Castle Cove · Castlecrag · Chatswood · Chippendale · Chiswick · Clovelly · Concord · Concord West · Coogee · Cremorne · Cremorne Point · Crows Nest · Croydon · Croydon Park · Darling Point · Darlinghurst · Dawes Point · Double Bay · Dover Heights · Drummoyne · Dulwich Hill · Edgecliff · Elizabeth Bay · Enmore · Five Dock · Forest Lodge · Glebe · Greenwich · Haberfield · Haymarket · Kensington · Kirribilli · Kurraba Point · Lane Cove · Lavender Bay · Leichhardt · Linley Point · Longueville · Manly · Maroubra · Marrickville · McMahons Point · Middle Cove · Millers Point · Milsons Point · Moore Park · Mosman · Naremburn · Neutral Bay · Newtown · North Sydney · North Willoughby · Northbridge · Paddington · Parramatta · Petersham · Point Piper · Potts Point · Pyrmont · Queens Park · Randwick · Redfern · Riverview · Rose Bay · Rushcutters Bay · St Leonards · Stanmore · Surry Hills · Sydney · Tamarama · The Rocks · Ultimo · Vaucluse · Waterloo · Waverton · Willoughby · Willoughby East · Wollstonecraft · Woolloomooloo · Woolwich

## Editing

- **Add a suburb** — drop `img/<slug>.webp` in, then add `{s:"<slug>", n:"<Name>"}` to the `SUBURBS` list in `index.html`.
- **Opening image** — change `DEFAULT` in `index.html` (currently `"sydney"`).
- **Accent colour, fonts, draw speed** — the `:root` variables at the top of the `<style>` block.

## Credit

Illustrations — Anastasia Butrym · Sydney · 2026
