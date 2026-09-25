# Module 2 Numerical Computation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Esha06/module-2-numerical-computation/blob/main/Module_2_Lab.ipynb)

A beginner lab covering numbers and formulas, floating-point precision,
strings and f-strings, collections, the `math` module, basic kinematics
(a tiny physics engine) and automated report generation.

The lab handout and all exercises are in [`Module_2_Lab.ipynb`](Module_2_Lab.ipynb).

## Files

| File | Purpose |
|------|---------|
| `Module_2_Lab.ipynb` | Lab handout + step-by-step Colab notebook |
| `physics.py` | Kinematic equations, projectile motion and a time-step fall simulation |
| `report.py` | Summarises raw measurements and formats a text report with f-strings |
| `test_module2.py` | Unit tests for `physics.py` and `report.py` |

Only the Python standard library is used, so there is nothing to install.

## Run locally

1. `python test_module2.py` (expect `Ran 9 tests ... OK`)
2. `python -c "import physics; print(physics.projectile(20, 45))"`

## Release

`v0.1.0` — first release of the Module 2 lab.
