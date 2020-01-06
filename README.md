# Sabrina

A theme for [Hugo](https://gohugo.io/) based on the simple, organic feel of a mother's cook book.

## Quick Start

0. Install Hugo with your favorite package manager, or follow their [Installation Guide](https://gohugo.io/getting-started/installing/)
1. Add the repository into your Hugo Project repository as a submodule, `git submodule add https://github.com/joshjcarrier/hugo-sabrina.git themes/sabrina`.
1. Configure your `config.toml` or `config.yaml` with theme named `"sabrina"`.
1. Build your site with `hugo serve` and see the result at `http://localhost:1313/`.

## Recipe

Create `.md` files in `content/`. Images go in `static/`.

```yml
---
layout: recipe
title: My recipe
subtitle: Sour, spicy and sweet pickled vegetable appetizer
image:
date:

authorName:
authorURL:
sourceName: My cookbook
sourceLocation: 43
sourceIMG: /images/cookbook/my-recipe.jpg
category: Appetizers
cuisine: American
tags:
  - Sour
  - Spicy
  - Sweet
  - Pickled
yield:
prepTime:
cookTime:
subcomponents:
  - title: Optional
    ingredients:
      - One
      - Two
    directions:
      - One
      - Two
  - title: More
    ingredients:
      - One
      - Two (optional)

ingredients:
  - One
  - Two
  - Three

directions:
  - Firstly,
  - Secondly,
---

```

## Glossary

Edit `data/glossary.yml`

```yml
- title: Something foreign
  translation: Something understandable
- title: Something else foreign
  translation: Something else understandable
```

## Enabling search

- Add a file in `content/search.html`

```html
---
title: "Search"
sitemap:
  priority: 0.1
layout: "search"
---
```

## License

- [Liberation Mono font](https://fontlibrary.org/en/font/liberation-mono)
- [Dancing script font](https://fontlibrary.org/en/font/dancing)
