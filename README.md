# A Bread Baker’s Notebook

Like probably most home bakers, I have a notebook filled with the bread formulas I’ve developed, tested, forgotten about, and preserved. As much as I love handwritten recipes, I became frustrated trying to track down an old formula, or adequately tracking how a formula evolved over time. I know others use spreadsheets for these reasons. I hate spreadsheets.

I began thinking about the potential of Git version control and a simple data format like YAML to create a durable, readable, living repository for my formulas. This repository also houses the development simple, web-based interface to browse the formulas. But my hope is that the plain-text files for individual formulas can stand on their own as clear guidelines for baking bread.

## Road map
* Web interface: create a simple timeline module for improved readability of recipe method.
* Web interface: build out tag functionality.
* Web interface: include ingredients in search index.
* Repo: create license for project files.
* Formulas: what would baking be without experimentation? Unlike a version-controlled file, my formulas don't develop linearly. While there may be a “master” version, ingredients, quantities, and methods change from bake to bake without necessarily replacing the previous version of the recipe. Some turn into new recipes, others dead ends, but most become alternatives, riffs on a theme. I’d like to be able to track this entire riverine history, an unfolding corpus of experiments, with all its sprouting, interconnected nodes of discovery. I’m not sure how to do this yet. Could I just use `git branch`? 🤔
