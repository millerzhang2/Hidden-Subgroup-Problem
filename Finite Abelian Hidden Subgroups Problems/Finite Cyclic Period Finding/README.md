# Finite Cyclic Period Finding

Open [Finite_Cyclic_Period_Finding.ipynb](Finite_Cyclic_Period_Finding.ipynb) for the exact period-finding problem on a known cyclic group, its quantum Fourier-sampling derivation and Qiskit implementation, and classical recovery using gcd computations and oracle verification.

The period is promised to divide the group size. Small non-power-of-two groups use an embedded Fourier matrix, while power-of-two groups use Qiskit's QFTGate. The notebook explains the scaling limits of the dense demonstration.

Use Python 3.12 or newer. From this directory:

~~~sh
python -m pip install -r requirements.txt
python -m jupyterlab
~~~

Select the kernel containing these dependencies and run the cells from top to bottom. The notebook runs on a local ideal simulator.

For reading offline, download [the rendered HTML preview](Finite_Cyclic_Period_Finding.html) and open it in a browser. Equations, fonts, and figures are embedded.

Return to [Finite Abelian Hidden Subgroups Problems](../README.md).
