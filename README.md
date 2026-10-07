# EngineeringTrainer's Custom Pangaea Assets

A dedicated static asset repository for **EngineeringTrainer**, providing global CDN delivery for custom stylesheets, scripts, and visual assets used across our Pangaea CMS.

## Getting Started

Use these links directly inside your HTML `<head>` or Pangaea's HTML content block:

```html
<link rel="stylesheet" href="https://engineeringtrainer.github.io/pangaea-assets/...">
```

## Hero styles

Load [`css/hero.css`](css/hero.css) for the Pangaea hero, CTA panel, and social proof sections:

```html
<link rel="stylesheet" href="https://engineeringtrainer.github.io/pangaea-assets/css/hero.css">
```

Apply the matching `et-hero`, `et-hero-cta`, `et-socialproof-facts`, and `et-socialproof-logos` classes to the relevant sections. The stylesheet also provides `section-padding-none` and `section-padding-bottom-none` spacing helpers.

## Card styles

Load [`css/cards.css`](css/cards.css) to give a Pangaea macro list a dark blue border and an orange left accent:

```html
<link rel="stylesheet" href="https://engineeringtrainer.github.io/pangaea-assets/css/cards.css">
```

Add `et-card-primary-border` to an element containing the card's `ul.o-macro`. The style only applies to macro lists inside that element.

## Tag styles

Load [`css/tags.css`](css/tags.css) after the site's base stylesheet, then add a modifier alongside `et-tags` on the tag-list container. Use `et-tags-large` for larger, orange-filled pills or `et-tags-primary` for the original pills with an orange border. See [`css/tags.md`](css/tags.md) for markup examples.

## Documentation

The documentation and examples can be found at [EngineeringTrainer's Custom Styleguide](https://www.engineeringtrainer.com/styleguide-custom)
