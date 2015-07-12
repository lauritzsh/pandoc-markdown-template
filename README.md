# Markdown template for reports
A simple template for writing reports in [Markdown](http://commonmark.org/)
using [Pandoc](http://pandoc.org/) for school/college/university/whatever.

## Requirements
Be sure to have LaTeX ([Windows](http://miktex.org/), [OS
X](https://tug.org/mactex/), [Linux](http://latex-project.org/)) and Pandoc
installed.

Pandoc can be installed with Homebrew: `brew install pandoc`.

## Typeset
For now there is a simple Bash script to typeset the document. To typeset it,
make sure `typeset` is executable (should be) and type `./typeset`. It will be
exported as `report.pdf` in the root folder.

## Replacing sample data
Edit the `cover.tex` file with the name of students and supervisor(s).

The `template.tex` file work as a template for LaTeX and preamble for LaTeX.
Edit this file for using other packages, settings etc.

Lastly you want to remove the directories filled with Markdown files and write
your own. Add the new files to `typeset` in the `FILES` array.

**Pro tip:** use [brace
expansion](http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_04.html) to
write the directories only once like the sample input already defined.
