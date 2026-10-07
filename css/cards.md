# Card styles

[`cards.css`](cards.css) gives Pangaea macro lists a dark blue border, rounded corners, and an orange left accent.

```html
<link rel="stylesheet" href="https://engineeringtrainer.github.io/pangaea-assets/css/cards.css">
```

Add `et-card-primary-border` to an element containing `ul.o-macro`. Only lists inside that element receive the style.

## Three-step workflow

Add `et-card-flow` to the section containing three `et-card` columns. The cards share a single border at each join, with orange arrows between steps. Below 960px they stack with downward arrows. An `et-card-primary-border` card inside `et-card-flow` gets its orange accent on the top edge at 960px and wider; below that it keeps the left accent. Other cards keep the original left accent.
