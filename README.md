<p align="center">
  <img src="https://raw.githubusercontent.com/adtzlr/felupe/main/docs/_static/logo_without_text.svg" height="120px"/>
  <p align="center">Notebooks for running <a href="https://github.com/adtzlr/felupe">FElupe</a> in the Browser. </p>
</p>

[![FElupe](https://img.shields.io/badge/%F0%9F%94%8D-FElupe-white)](https://github.com/adtzlr/felupe) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/adtzlr/felupe-web/main?labpath=notebooks/binder/01_Getting-Started.ipynb) [![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://adtzlr.github.io/felupe-web/lab?path=01_Getting-Started.ipynb) <a target="_blank" href="https://colab.research.google.com/github/adtzlr/felupe-web/blob/main/notebooks/colab/01_Getting-Started.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## JupyterLite
Due to limitations using JupyterLite / Pyodide, the `parallel`-evaluation mode of a `Job` is not available. The computation is performed on the client side. Hence, the computation performance depends on the client. Python is running in 32bit mode. Visualizing the simulation model is not possible, i.e. `felupe.View` is not available in JupyterLite.

> **Note**  
> Select and delete all files in JupyterLite to delete all local files and to restore the files provided by the repository.

## MyBinder and Google Colab
The most complete package is available via MyBinder. The computations are performed in virtual machines with limited memory. 

> **Warning**  
> Never run `!pip install felupe[all]` in a MyBinder environment because this downloads `vtk` via pip and breaks the interactive outputs.

## Google Colab
Computations are performed in virtual machines with limited memory. Colab offers Pro plans providing more memory and computation power. Visualizations of the simulation model are limited in Colab, i.e. `felupe.View` is only available with a static backend in Colab.
