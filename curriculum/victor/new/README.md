Smart Fancy LaTeX CV
====================

Prerequisites
-------------

The following LaTeX packages must be installed:

* `texlive`
* `texlive-xetex`
* `texlive-luatex`
* `texlive-math-extra`
* `texlive-bibtex-extra`

Optional for Font Awesome icons:

* `texlive-fonts-extra`

Ubuntu install snippet:

```bash
sudo apt-get install texlive texlive-xetex texlive-luatex texlive-math-extra texlive-fonts-extra texlive-bibtex-extra
```

Compiling
---------

```bash
# Generate the english CV
make english
# Clean auxiliary files
make clean
# Generate the spanish CV
make spanish
# Clean auxiliary files
make clean
# Or run all of the above
make all
```

Please note that `lualatex` will be slow the first time.