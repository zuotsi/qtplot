![alt tag](screenshot.png)

## Installing

This modified Qtplot is compatible with python 3 due to updated pyQT5. Using the Anaconda Python distribution (https://www.continuum.io/downloads) is recommended to make installing packages like `numpy` and `scipy` easier.

There might be some issues with numpy, it should works with 1.23*

Create a new environment:

`conda create --name qtplot python=3.8`

Install qtplot:

`pip install qtplot`

Install other dependencies with:

`conda install numpy scipy pandas matplotlib pyqt`

Executables will be generated in the `/Scripts` folder of your Python environment with the names `qtplot.<exe>` and `qtplot-console.<exe>`. Associate one of these with `*.dat` files for them to be automatically opened in qtplot.
