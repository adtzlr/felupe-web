# MyBinder Configuration
The core scientific stack (numpy, scipy, matplotlib) is installed via conda-forge. Everything related to FElupe is installed via PyPI (pip).

## Vtk
It is necessary to install pyvista via pip. This allows uninstalling its requirement vtk, which is replaced in the `postBuild` script with `vtk-osmesa`.
