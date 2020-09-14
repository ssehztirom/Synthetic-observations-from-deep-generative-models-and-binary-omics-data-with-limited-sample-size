# About

Here you can find the accompanying information about the methods proposed in the manuscript: "Synthetic observations from deep generative models and binary omics data with limited sample size". 
Specifically a [Jupyter Notebook](notebook.ipynb) which allows to evaluate the investigated approaches with simulated data.

During evaluation, all required packages are automatically installed.

## Prerequisites

To run the Notebook, you need a Jupyter Server with a running Julia installation. One approach is to install [Julia](https://www.julialang.org/downloads/) then install [IJulia](https://github.com/JuliaLang/IJulia.jl) and run
```julia 
using IJulia
notebook()
```
This will install the Jupyter server components via Conda. For plotting functionalities via PyPlot, you may need to install [Matplotlib](https://matplotlib.org) via the Python installation, installed by Conda. Given you are in your `HOME` directory, you can achieve this by executing

```.julia/conda/3/bin/pip3 install matplotlib --user```.
