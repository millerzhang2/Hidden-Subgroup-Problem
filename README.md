# Hidden Subgroup Problem

Explanations and executable Jupyter notebooks for hidden subgroup problems, with quantum implementations in Qiskit and classical recovery code.

## Structure

- [Preliminaries](Preliminaries/README.md)
- [Finite Abelian Hidden Subgroups Problems](Finite%20Abelian%20Hidden%20Subgroups%20Problems/README.md)
- [Beyond Finite Abelian Hidden Subgroups](Beyond%20Finite%20Abelian%20Hidden%20Subgroups/README.md)

## Algorithm notebooks

Start with [Simon's algorithm notebook](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Simon%27s%20Algorithm/Simons_Algorithm.ipynb). It explains the problem, derives the quantum sampling procedure, implements the circuit in Qiskit, and recovers the hidden string using binary Gaussian elimination.

Saved outputs include the circuit, measurement results, and recovered string.

The [Generalized Simon's algorithm notebook](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Generalized%20Simon%27s%20Algorithm/Generalized_Simons_Algorithm.ipynb) extends this to a hidden binary subspace. It includes quantum sampling, classical basis recovery, and verification when the hidden dimension is unknown.

The [Finite Cyclic Period Finding notebook](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Finite%20Cyclic%20Period%20Finding/Finite_Cyclic_Period_Finding.ipynb) uses the Fourier transform on a known cyclic group and recovers its hidden period with gcd computations. It includes a non-power-of-two example.

The [Shor's Discrete Logarithm Algorithm notebook](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Shor%27s%20Discrete%20Logarithm%20Algorithm/Shors_Discrete_Logarithm_Algorithm.ipynb) constructs a modular-multiplication oracle from public parameters and combines paired Fourier samples to recover and verify the logarithm, including for composite group orders.

The [Shor's Order-Finding and Factoring Algorithm notebook](Beyond%20Finite%20Abelian%20Hidden%20Subgroups/Shor%27s%20Order-Finding%20and%20Factoring%20Algorithm/Shors_Order_Finding_and_Factoring_Algorithm.ipynb) introduces the infinite abelian setting through quantum phase estimation, continued-fraction order recovery, and verified factor extraction. It includes a nonexact-phase example and an explicit order-recovery success bound.

The [Hallgren's Algorithm for Pell's Equation notebook](Beyond%20Finite%20Abelian%20Hidden%20Subgroups/Hallgren%27s%20Algorithm%20for%20Pell%27s%20Equation/Hallgrens_Algorithm_for_Pells_Equation.ipynb) extends Fourier sampling to real periods using reduced ideals. It includes small Qiskit examples and classical unit recovery, with an explicit distinction between the demonstrations and Hallgren's polynomial-time arithmetic.

The [Kuperberg's Algorithm for the Dihedral HSP notebook](Beyond%20Finite%20Abelian%20Hidden%20Subgroups/Kuperberg%27s%20Algorithm%20for%20the%20Dihedral%20HSP/Kuperbergs_Algorithm_for_the_Dihedral_HSP.ipynb) introduces a nonabelian hidden subgroup problem through retained phase qubits, quantum state combination, and a classical sieve controller that recovers the full reflection parameter.

## Run locally

Use Python 3.12 or newer. From the repository root:

```sh
python -m venv .venv
```

Activate the environment:

```powershell
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
```

```sh
# macOS or Linux
source .venv/bin/activate
```

Install the dependencies and start JupyterLab:

```sh
python -m pip install -r "Finite Abelian Hidden Subgroups Problems/Simon's Algorithm/requirements.txt"
python -m jupyterlab
```

All notebooks use the same dependencies. Open an algorithm notebook and run its cells from top to bottom. The code runs on a local ideal simulator and does not require an IBM Quantum account.
