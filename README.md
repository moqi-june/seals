# Topics

## Crowd Density Visualizer

**Live:** https://moqi-june.github.io/seals/crowd-density/

Model what an event crowd actually looks like on a real lawn or venue. Pick
the spot on a satellite map (or upload a site plan / PDF and calibrate its
scale with two clicks), outline the area, then slide the headcount — 6,000,
8,000, 10,000 people — and watch the dot spacing tighten in real time.
Built for occupancy decisions: show leadership the same lawn at several
densities and let them choose how packed the event should feel.

- Two base layers: satellite imagery with address search, or an uploaded
  site-plan image/PDF with two-click scale calibration
- Realistic blue-noise crowd scatter (up to 25,000 people) that stays stable
  as the slider moves — dots only appear or disappear, never re-shuffle
- Live stats with crowd-safety benchmarks: sq ft per person, people per m²,
  typical spacing, and a color-coded density rating from *Loose* to *Unsafe*
- One-click density presets (15 / 10 / 7 / 5 sq ft per person)
- Presentation-grade exports: a high-res PNG snapshot with a stats banner,
  and a side-by-side comparison board of pinned scenarios over the identical
  view — ready to paste into an executive deck
- Single self-contained HTML file, saves automatically in your browser; the
  only network calls are the map tiles (Esri) and place search (Nominatim)

## Work Motivation Map

**Live:** https://moqi-june.github.io/seals/work-motivation/

A small card-sort game for figuring out what actually motivates you at work,
digitized from a physical card exercise. Pick up to 7 words from a deck of 60
(Autonomy, Trust, Craftsmanship, Recognition, ...) and place each one on the
area of work life it belongs to: Work, Team, Leader, Products, or Company. A
word can also sit on the line between two areas. Not sure about a word? Drag
it to the trash strip and narrow the deck down by elimination.

Useful solo, or as a manager running 1:1s — compare maps to see what drives
each person.

- Results export as a transparent PNG or a Markdown summary, tagged with the
  player's name and date
- Works on desktop and phone, light and dark mode
- Single self-contained HTML file: no dependencies, no server, no tracking.
  Your board never leaves your browser (saved in localStorage); the only
  artifacts are the files you export
