---
title: Home
permalink: /
---

# A Bread Baker’s Notebook

Like probably most home bakers, I have a notebook filled with the bread formulas I’ve developed, tested, forgotten about, and preserved. As much as I love handwritten recipes, I became frustrated trying to track down an old formula, or adequately tracking how a formula evolved over time. I know others use spreadsheets for these reasons. I hate spreadsheets.

I began thinking about the potential of Git version control and a simple data format like YAML to create a durable, flexible, living repository for my formulas.

My formulas don't develop linearly. While there may be a “master” version, ingredients, quantities, and methods change from bake to bake without necessarily replacing the previous version of the recipe. Some turn into new recipes, others dead ends, while still others become alternatives, riffs on a theme.

I am using a Github [repository]({{ site.recipe-repository }}) to document the riverine development of these formulas. It’s an unfolding corpus, full of sprouting, interconnected nodes of experimentation.

All recipes are at some stage of development; some are close but need minor tweaking, others may be disasters. Those that I consider *good enough* — an amorphous, perfectionistic, and excessively subjective classification — are published on this site.

The code for this website is also housed on [Github]({{ site.repository }}).

## Formulas
{% include recipe-nav.html %}

## Road map
* Create a simple timeline module for improved readability of recipe method.
* Build out tag functionality.
* Include ingredients in search index.
* Formulas: log overall formula (or generate on website).

## License
Copyright (c) 2017–{{ "now" | date: "%Y" }} Dana Johnson.

This website and the recipes published here are licensed under the MIT license. Feel free to steal, adapt, or remix anything you find. Happy baking!
