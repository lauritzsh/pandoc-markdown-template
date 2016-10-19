# Pandoc Markdown template
This repository is a small collection of personal Markdown templates for Pandoc.

Each directory contains a working template and example PDF output.

## Requirements
Be sure to have LaTeX ([Windows](http://miktex.org/), [OS X](https://tug.org/mactex/),
[Linux](http://latex-project.org/)) and Pandoc installed.

On macOS, Pandoc can be installed with Homebrew: `brew install pandoc`.

For typesetting you can either use the `Makefile`s with `make` or just use `pandoc`.

For the `report-bib` you will need `pandoc-citeproc` too. On macOS that is easily installed with
`brew install pandoc-citeproc`.

## Customization
If you want to see what Pandoc allows for customization you can use `pandoc -D latex` to get the
default LaTeX template. You can set variables with `-V/--variable` when using `pandoc` or preferably
put them into a [YAML front matter](http://assemble.io/docs/YAML-front-matter.html).
