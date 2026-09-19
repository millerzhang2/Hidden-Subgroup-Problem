# Shor's Discrete Logarithm Algorithm

Open [Shors_Discrete_Logarithm_Algorithm.ipynb](Shors_Discrete_Logarithm_Algorithm.ipynb) for the problem statement, hidden subgroup formulation, quantum Fourier-sampling derivation and Qiskit code, and classical recovery through the extended Euclidean algorithm.

The notebook assumes a known cyclic group order and supports composite orders. Its modular-multiplication oracle uses only the public group parameters. Small non-power-of-two orders use embedded Fourier matrices. The notebook explains the scaling limits of these dense demonstrations.

Use Python 3.12 or newer. From this directory:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Select the environment containing these dependencies and run the notebook from top to bottom. The circuits use a local ideal simulator.

For reading offline, download [the rendered HTML preview](Shors_Discrete_Logarithm_Algorithm.html) and open it in a browser. Its equations, fonts, and figures are embedded.

Return to [Finite Abelian Hidden Subgroups Problems](../README.md).
