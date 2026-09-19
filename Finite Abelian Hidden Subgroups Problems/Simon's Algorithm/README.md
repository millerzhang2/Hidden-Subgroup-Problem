# Simon's Algorithm

Open [Simons_Algorithm.ipynb](Simons_Algorithm.ipynb) for an explanation and executable implementation of Simon's algorithm.

The notebook covers the problem promise, the quantum sampling argument and Qiskit implementation, and classical recovery through Gaussian elimination over the binary field. It includes the one-to-one case and checks for insufficient data.

Use Python 3.12 or newer. From this directory, install the dependencies and launch JupyterLab:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Choose a kernel in the environment where the dependencies are installed, then run the notebook from top to bottom. It runs entirely on a local ideal simulator. Saved outputs include the circuit diagram, measurements, and recovered string.

For reading in a viewer that does not typeset notebook equations, download the [rendered HTML preview](Simons_Algorithm.html) and open it in a browser. Its formulas, fonts, and figures are embedded, so it also works offline. Use the notebook to edit or execute the code.
