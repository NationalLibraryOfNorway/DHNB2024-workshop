# DH-lab workshop notes and slides for DHNB 2024 in Reykjavik

This workshop will take place on Wednesday, 29th May 2024 at the [Digital Humanities in the Nordic and Baltic Countries 2024](https://dhnb.eu/conferences/dhnb2024/) 8th conference in Reykjavik, Iceland.

This repo contains the github pages, slides and notebooks to be used during the workshop.

## Building the book

If you'd like to develop and/or build the dhlab-workshop book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `dhlab_workshop/` directory
4. Run `jupyter-book clean dhlab_workshop/` to remove any existing builds
5. Run `jupyter-book build dhlab_workshop/`

A fully-rendered HTML version of the book will be built in `dhlab_workshop/_build/html/`.

## Slides

The presentation slides are written in myst markdown, converted to a Jupyter notebook, and exported as a slide show with [`nbconvert`](https://nbconvert.readthedocs.io/en/latest/index.html).

Convert the myst markdown file to a notebook, then to a slide show html file, and copy to the `_build/html/` directory:

```{code-cell} shell
cd dhlab_workshop
jupytext slideshow.md --to ipynb
jupyter nbconvert slideshow.ipynb --to html --template reveal
cp slideshow.html _build/html/
```

Run this to host the slide show on a local server and view in a browser:

```{code-cell} shell
jupyter nbconvert dhlab_workshop/slideshow.ipynb --to slides --post serve
```
