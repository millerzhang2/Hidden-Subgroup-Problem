# Kuperberg's Algorithm for the Dihedral HSP

Open [Kuperbergs_Algorithm_for_the_Dihedral_HSP.ipynb](Kuperbergs_Algorithm_for_the_Dihedral_HSP.ipynb) for the dihedral hidden reflection problem, phase-qubit preparation, the quantum combination operation, and classical control of the sieve and subgroup restrictions.

The notebook implements the basic power-of-two case and recovers the complete reflection parameter. It uses Qiskit to retain and combine actual simulated qubits, with bounded retries and a final oracle verification.

The small-instance hiding oracle is compiled from a truth table. Its classical compilation and simulation costs are stated separately from Kuperberg's subexponential quantum algorithm. The demonstration supports powers of two from 2 through 64.

Use Python 3.12 or newer. From this directory:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Run the cells from top to bottom. No IBM Quantum account is required.

For offline reading, download [the rendered HTML preview](Kuperbergs_Algorithm_for_the_Dihedral_HSP.html) and open it in a browser. Equations, fonts, and figures are embedded.

Return to [Beyond Finite Abelian Hidden Subgroups](../README.md).
