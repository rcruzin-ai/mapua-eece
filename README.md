# EECE Excellence Awards 2026 — Keynote

A self-contained HTML slide deck for a ~15-minute guest keynote at the **Mapúa University School of Electrical, Electronics & Computer Engineering (EECE) Excellence Awards 2026**.

**Speaker:** Engr. Raymond Bueta Cruzin · Senior AI & Machine Learning Engineer, Sprout AI Labs

> *Skill Issue? — Plot twist: not yours.* Everyone can code now, so what's your moat? A talk on reframing AI from threat to leverage, and on becoming significant rather than average.

## View it

Open [`deck.html`](deck.html) in any modern browser. No build step, no dependencies — everything is embedded in the single file.

### Controls

| Key | Action |
| --- | --- |
| `←` / `→` (or click sides) | Previous / next slide |
| `s` | Toggle speaker notes |
| `f` | Fullscreen |
| `o` | Toggle the **overview** (all slides on one page, with notes — also good for printing to PDF) |

Deep-link to a slide with `deck.html#4`, or open the overview directly with `deck.html#overview`.

## Editing

`deck.html` is the **single source of truth**. Slide content lives in the `String.raw` markdown block inside it — edit the slides there. A lightweight in-page parser turns that markdown into both the presenting view and the overview.

- Slides are separated by `---`.
- Per-slide directives: `<!-- class: x -->` sets the layout variant; `<!-- notes: ... -->` holds speaker notes.

[`deck.md`](deck.md) is a readable export of the same content, regenerated from `deck.html` on request.

## Layout

```
deck.html      # the deck — present from here, edit here
deck.md        # readable markdown export (derived)
images/        # logos, journey/deck artwork, QR codes
```

## License

Personal keynote material. Brand logos in `images/logos/` belong to their respective owners and are used here for illustrative reference only.
