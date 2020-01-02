# Sabrina

A theme for [Hugo](https://gohugo.io/) based on the simple, organic feel of a mother's cook book.

## Quick Start

0. Install Hugo with your favorite package manager, or follow their [Installation Guide](https://gohugo.io/getting-started/installing/)
1. Add the repository into your Hugo Project repository as a submodule, `git submodule add https://github.com/joshjcarrier/hugo-sabrina.git themes/sabrina`.
1. Configure your `config.toml` or `config.yaml` with theme named `"sabrina"`.
1. Build your site with `hugo serve` and see the result at `http://localhost:1313/`.

## Recipe

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
