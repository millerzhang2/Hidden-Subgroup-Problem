# Shor's Order-Finding and Factoring Algorithm

Open [Shors_Order_Finding_and_Factoring_Algorithm.ipynb](Shors_Order_Finding_and_Factoring_Algorithm.ipynb) for the problem statement, infinite abelian hidden subgroup formulation, quantum phase-estimation derivation and Qiskit code, and classical continued-fraction recovery and factoring code.

The notebook distinguishes a verified period from the exact order and gives an explicit success bound for recovering the order from independent pairs of samples. Its nonexact-phase example uses base 2 modulo 21. The factoring routine assumes a semiprime input and verifies its returned factors.

Use Python 3.12 or newer. From this directory:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Run the cells from top to bottom. The local ideal simulation uses dense modular-multiplier gates and supports at most 6 work qubits, or 18 total qubits. The notebook explains how these small demonstrations differ in cost from scalable reversible arithmetic.

For offline reading, download [the rendered HTML preview](Shors_Order_Finding_and_Factoring_Algorithm.html) and open it in a browser. Its equations, fonts, and figures are embedded.

Return to [Beyond Finite Abelian Hidden Subgroups](../README.md).
