# Animal Trading Card — Snow Leopard

Final project for Udacity's *Intro to Web Development* (nd000) HTML & CSS unit.

A static, single-page HTML card built with semantic markup and an external
stylesheet — no inline `style` attributes anywhere.

Open `card.html` in a browser to see the card. Files:

```
card.html         Card markup
styles.css        External stylesheet (linked from card.html)
snow-leopard.svg  Card image
```

## Rubric mapping

| Criterion | Where |
|---|---|
| Page resembles card prototype | `card.html` + `styles.css` |
| Italicised fact | `.card-fact { font-style: italic }` |
| Bolded list-item labels | `.card-label { font-weight: bold }` |
| No bullet dots on list | `.card-list { list-style: none }` |
| Border around name / image / info | `.card-name`, `.card-image`, `.card-info` all have `border: 1px solid …` |
| Spacing between blocks | `margin: 0 0 12px 0` on each block |
| Card width 300px, image 300px | `.card { width: 300px }` and `.card-image { width: 300px }` |
| Custom (relevant) image and information | snow-leopard image + facts |
| `alt` is relevant | `"A snow leopard photographed against snowy mountain rocks"` |
| CSS classes with meaningful names | `.card`, `.card-name`, `.card-image`, `.card-info`, `.card-fact`, `.card-list`, `.card-label`, `.card-description` |
| Separation of concerns | linked stylesheet, no `<style>` or inline `style=` |
| Code quality | indentation, comments, leading rule blocks |

## License

Educational submission for Udacity nd000. Snow leopard image is a generic
placeholder (SVG); you may swap it with any photo you have.
