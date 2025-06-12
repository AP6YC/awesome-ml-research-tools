# awesome-ml-research-tools
An (awesome) list of my favorite machine learning research tools.

## Python 

### Libraries

#### Neural Networks

- [PyTorch](https://docs.pytorch.org/docs/stable/index.html) - neural nets à la Facebook
- [Tensorflow](https://www.tensorflow.org/api_docs/python/tf/all_symbols) - neural nets à la Google

#### Data Science/Handling

- [`pandas`](https://pandas.pydata.org/docs/) - the main way to handle DataFrames in Python.
- [`scikit-learn`](https://scikit-learn.org/stable/) - the main traditional machine learning library in Python.

#### Plotting

- [`matplotlib`](https://matplotlib.org/stable/) - the central plotting library for the Python ecosystem.
- [`seaborn`](https://seaborn.pydata.org) - wrapper for `matplotlib` with common recipes for statistical visualization.
- [`bokeh`](https://docs.bokeh.org/en/latest/index.html) - a separate Python plotting library with built-in support for interactive plots.

#### QPU Simulators

- [qsim](https://quantumai.google/qsim) - Google's quantum computing simulator.
- [qiskit](https://github.com/Qiskit/qiskit) - IBM's quantum simulator.

#### Etc.

- [jupyter](https://docs.jupyter.org/en/latest/) - ecosystem that contains the `IPython` kernel, jupyter notebook, and jupter lab environments. You can install most of what you need with `pip install jupyterlab`.

### Virtual Environment Management

- [Mamba](https://github.com/mamba-org/mamba) - a C++ rewrite of `conda`.
- [Python’s stdlib venv](https://docs.python.org/3/library/venv.html) - Python's native virtual environment manager; always available as a fallback.

## Education

- [Stanford graph neural nets class](https://web.stanford.edu/class/cs224w/index.html#content) - a great course on graph neural nets

## Dev

A collection of references and resources for actually running experiments.

### HPCs

- [mill documentation](https://docs.itrss.umsystem.edu/pub/hpc/mill) - the MST Mill documentation.
- [mill OnDemand](https://mill-ondemand-p1.itrss.mst.edu/) - the Open OnDemand GUI interface to the MST Mill

### Resources

- [Sasha’s GitHub](https://github.com/AP6YC) - Sasha Petrenko's collection of research projects, packages, and mistakes.

## Julia

[Julia](https://julialang.org) packages and resources.

- [Revise.jl](https://timholy.github.io/Revise.jl/stable/) - online recompiler for Julia, significantly reducing restarts.
- [DrWatson.jl](https://juliadynamics.github.io/DrWatson.jl/stable/)- scientific project management package
- [Flux.jl](https://fluxml.ai/Flux.jl/stable/) - the main Julia neural nets library.
- [Lux.jl](https://lux.csail.mit.edu/dev/) - a Julia neural nets library to use when doing physics-informed work.

## CLI

Various command line interface tools.

- [chezmoi](https://www.chezmoi.io) - a cross-platform dotfiles manager.
- [nushell](https://www.nushell.sh) - a decent shell.
- [wezterm](https://wezterm.org) - a decent terminal emulator and multiplexer all-in-one.
- [starship](https://starship.rs) - a decent shell prompt.
