# CUBA example with and without Brian

This repo is a simple example of converting a Brian script into pure Python using numba.

We start from the [CUBA example](https://brian2.readthedocs.io/en/stable/examples/CUBA.html) included in [Brian](https://briansimulator.org).

[Run the code using Brian via Google Colab](https://colab.research.google.com/github/thesamovar/cuba_with_and_without_brian/blob/main/brian_cuba.ipynb).

Next I manually converted this example to do exactly the same thing as Brian does, but in pure Python accelerated using the numba Python JIT compiler.

[Run the code without Brian via Google Colab](https://colab.research.google.com/github/thesamovar/cuba_with_and_without_brian/blob/main/simple_snn.ipynb).

Or here's a version that uses vectorisation and NumPy instead of numba.

[Run the code without Brian via Google Colab](https://colab.research.google.com/github/thesamovar/cuba_with_and_without_brian/blob/main/simple_snn_numpy.ipynb).

For this last one, you can copy/paste the content of the cell from [the notebook](https://github.com/thesamovar/cuba_with_and_without_brian/blob/main/simple_snn_numpy.ipynb) into a new notebook using [JupyterLite](https://jupyterlite.github.io/demo/) to run it locally in the browser rather than on Colab. This lets you run this example without a Google account.

I hope this might be somewhat helpful in understanding how Brian works behind the scenes, and in general what is involved in simulating a spiking neural network.
