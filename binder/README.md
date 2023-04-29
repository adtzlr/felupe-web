# MyBinder Configuration
The core scientific stack (numpy, scipy, matplotlib) is installed via conda-forge. All other optional requirements of FElupe are installed via PyPI (pip).

## Vtk
It is necessary to install pyvista via pip. This allows uninstalling its requirement `vtk`, which is replaced in the `postBuild` script with `vtk-osmesa`. 

> **Warning**  
> Never run `!pip install felupe[all]` because this downloads `vtk` via pip and breaks the interactive outputs. 
> Fix this by running the following two lines of code in a Jupyter notebook.
> `!pip uninstall vtk -y`
> `!pip install vtk-osmesa --force-reinstall --extra-index-url https://gitlab.kitware.com/api/v4/projects/13/packages/pypi/simple`
