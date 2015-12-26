Simple recipes
==============

Write your recipes in YAML, make them into a GitHub page.

See the [`gh-pages`](https://github.com/dill/recipes/tree/gh-pages) branch for examples!

This set of pages is rendered at [converged.yt/recipes/](http://converged.yt/recipes/).

## Format


The general idea is that you write the ingredients and other "meta" data in the YAML block, then the instructions as a numbered list as the content.

Ingredients are key:value pairs, the key being the amount of ingredient and the value being the description. This might not make the most sense but means that the YAML is human-readable.

Note that the ingredients section must be nested (at the moment), so you have subsets of ingredients (cake plus icing for example).

### A simple example

```
---
layout: recipe
title: "A recipe for delicious YAML"
source: some URL or book
serves: 6 ravenous monsters
ingredients:
  ingredient set 1:
    850g : an ingredient
    a pinch : another ingredient
  another set of ingredients:
    1.5l : another ingredient
    1tbsp : something else

---

1. Put everything in a big bowl.
2. Make dinner.
```


