# Making TOC and contents from loop

## Things to install

jupyterlab 3
conda install "nbconvert=5.6.1"
conda install -c conda-forge jupyter_contrib_nbextensions

## Create html with TOC

jupyter nbconvert --to html_toc jupyterloop.ipynb --no-input

## Good links with Sphinx issues

https://github.com/spatialaudio/nbsphinx/issues/152
