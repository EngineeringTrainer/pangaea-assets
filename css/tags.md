# Tag variants

The site's base stylesheet defines `.et-tags`: small white pills with a light border and dark blue text. [`tags.css`](tags.css) provides two optional modifiers for that base style:

- `et-tags-large` makes the pills larger and orange-filled, with dark blue text.
- `et-tags-primary` keeps the base size and white background, changing only the border to brand orange.

```html
<link rel="stylesheet" href="https://engineeringtrainer.github.io/pangaea-assets/css/tags.css">
```

Load `tags.css` after the site's base stylesheet. Add `et-tags` and one modifier to the element containing the list. The modifiers rely on the base class for the pill shape, layout, and other shared styles.

```html
<div class="et-tags et-tags-large">
  <ul>
    <li>Codes &amp; standards</li>
    <li>Engineering software</li>
  </ul>
</div>

<div class="et-tags et-tags-primary">
  <ul>
    <li>Codes &amp; standards</li>
    <li>Engineering software</li>
  </ul>
</div>
```
