# FElupe Web
This Repository provides notebooks for running **FElupe** - *Finite Element Analysis* in the Browser. 

## JupyterLite
Due to limitations using JupyterLite / Pyodide, the `parallel`-execution mode is not available. The computation is performed on the client side. Hence, the computation performance depends on the client. Python is running in 32bit mode. Visualizations of the simulation model are not possible (`felupe.Result` is not available).

## MyBinder and Google Colab
The computations are performed in virtual machines with limited memory. Google Colab offers Pro plans providing more memory and computation power. Howver, visualizations of the simulation model are restricted to static screenshots.

https://adtzlr.github.io/felupe-web/lab?path=01_Getting+Started.ipynb
