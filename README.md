# CUBA exmaple with and without Brian

This repo is a simple example of converting a Brian script into pure Python using numba.

We start from the [CUBA example](https://brian2.readthedocs.io/en/stable/examples/CUBA.html) included in [Brian](https://briansimulator.org).

[Run the code using Brian via Google Colab](https://colab.research.google.com/github/thesamovar/cuba_with_and_without_brian/blob/main/brian_cuba.ipynb).

Next I manually converted this example to do exactly the same thing as Brian does, but in pure Python accelerated using the numba Python JIT compiler.

[Run the code without Brian via Google Colab](https://colab.research.google.com/github/thesamovar/cuba_with_and_without_brian/blob/main/simple_snn.ipynb).

I hope this might be somewhat helpful in understanding how Brian works behind the scenes, and in general what is involved in simulating a spiking neural network.
