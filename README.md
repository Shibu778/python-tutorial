# Python Tutorial

This repository contains source files for the Python Tutorial jupyter book that we are working on.

To push the jupyter book changes to the gh-pages branch
1. Make the changes
2. Do `jupyter-book build docs`
3. Push the changes to main branch
3. Do `ghp-import -n -p -f docs/_build/html`