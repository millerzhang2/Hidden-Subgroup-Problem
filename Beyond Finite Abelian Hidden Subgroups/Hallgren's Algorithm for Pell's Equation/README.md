# Hallgren's Algorithm for Pell's Equation

Open [Hallgrens_Algorithm_for_Pells_Equation.ipynb](Hallgrens_Algorithm_for_Pells_Equation.ipynb) for the Pell problem, units and regulators, the real hidden subgroup formulation, Qiskit Fourier sampling, and classical recovery and exact Pell verification.

The quantum oracle is constructed from the input d using explicit continued-fraction ideal reductions. It does not receive a known regulator or Pell solution. The small examples cover both norm +1 and norm -1 fundamental units.

The notebook explains Hallgren's polynomial-time algorithm, while its executable demonstration uses forward ideal walks and compiled lookup circuits. These substitutions are not polynomial-time in the input length and do not demonstrate a quantum speedup. The distinction and output-size limitations are explained in the notebook.

Use Python 3.12 or newer. From this directory:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Run the cells from top to bottom. The examples use a local ideal simulator.

For offline reading, download [the rendered HTML preview](Hallgrens_Algorithm_for_Pells_Equation.html) and open it in a browser. Equations, fonts, and figures are embedded.

Return to [Beyond Finite Abelian Hidden Subgroups](../README.md).
