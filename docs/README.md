Please see https://deeplabcut.github.io/DeepLabCut for documentation on how to use this software. 

# Contributing to the Docs
The documentation is built using [JupyterBook](https://jupyterbook.org/en/stable/intro.html). All of our documentation is contained within this repository, except the two files `_config.yml` and `_toc.yml` that live in the root folder (`DeepLabCut`).

Contributing to the docs is easy, as just a few steps are needed:
- Fork DeepLabCut
- `git clone` your fork to get a local version
- Install the developer edition of DeepLabCut. 
- Install additional dependencies (`conda install jupyter-book sphinxcontrib-mermaid`).
- Start editing!

Once you have made the improvements, you can build a local version of the documentation to see what they look like. To do so, make sure you ate in the root folder (`DeepLabCut`), then run `jupyter-book build .`.