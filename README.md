# Hidden Subgroup Problem

Explanations and executable Jupyter notebooks for hidden subgroup problems, with quantum implementations in Qiskit and classical recovery code.

## Structure

- [Preliminaries](Preliminaries/README.md)
- [Finite Abelian Hidden Subgroups Problems](Finite%20Abelian%20Hidden%20Subgroups%20Problems/README.md)
- [Beyond Finite Abelian Hidden Subgroups](Beyond%20Finite%20Abelian%20Hidden%20Subgroups/README.md)

## Algorithm notebooks

Start with [Simon's algorithm notebook](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Simon%27s%20Algorithm/Simons_Algorithm.ipynb). It explains the problem, derives the quantum sampling procedure, implements the circuit in Qiskit, and recovers the hidden string using binary Gaussian elimination.

Saved outputs include the circuit, measurement results, and recovered string. For an offline reading copy with rendered equations, download [the HTML preview](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Simon%27s%20Algorithm/Simons_Algorithm.html) and open it in a browser.

The [Generalized Simon's algorithm notebook](Finite%20Abelian%20Hidden%20Subgroups%20Problems/Generalized%20Simon%27s%20Algorithm/Generalized_Simons_Algorithm.ipynb) extends this to a hidden binary subspace. It includes quantum sampling, classical basis recovery, and verification when the hidden dimension is unknown.

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

Both notebooks use the same dependencies. Open either algorithm notebook and run its cells from top to bottom. The code runs on a local ideal simulator and does not require an IBM Quantum account.
