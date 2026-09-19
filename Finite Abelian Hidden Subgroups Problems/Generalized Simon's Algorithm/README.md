# Generalized Simon's Algorithm

Open [Generalized_Simons_Algorithm.ipynb](Generalized_Simons_Algorithm.ipynb) for the binary hidden-subspace problem, its quantum sampling argument and Qiskit implementation, and classical recovery of a basis by Gaussian elimination.

The implementation certifies the recovered subgroup without requiring its dimension in advance. It includes checks for insufficient samples, the trivial subgroup, one hidden period, and the full input space.

Use Python 3.12 or newer. From this directory:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Choose a kernel in the environment containing these dependencies, then run the notebook from top to bottom. All circuits run on a local ideal simulator.

For reading offline, download [the rendered HTML preview](Generalized_Simons_Algorithm.html) and open it in a browser. Its equations, fonts, and figures are embedded.

Return to [Finite Abelian Hidden Subgroups Problems](../README.md).
