# Session 3: Dynamic Programming

**Tuesday 13 October, 9:30-12:00**

- **Lecture:** Why we need dynamic programs at all: scalability and real-time computation for QEC. Introduction to JAX and Just-in-time compilation, and how it embeds into Qrisp with the Jasp module (dynamic control flow, dynamic variables, and compilation pipeline).
- **Tutorial:** Write dynamic programs yourself in Qrisp with dynamic mode leveraging JAX. Evaluation modes: resource estimation, boolean simulation, and other Jasp-related features for quantum programming.

The session has two parts of about 45 minutes each, with a short break in between:

1. Slides, then `JaspTracing.ipynb`
2. `JaspJIT.ipynb`

Click a badge below to open a notebook directly in Google Colab (no local setup required). If you run the notebooks locally, the evaluation-modes section of `JaspJIT.ipynb` also needs Stim (`pip install stim`).

## Main Notebooks

| Notebook | Open in Colab |
|---|---|
| `JaspTracing.ipynb`: Jasp internals and the execution model (jaspr, tracing, primitives), and branching on a measurement result | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PietropaoloFrisoni/iqm-qrisp-school-oct2026/blob/main/Session_3_Dynamic_Programming/JaspTracing.ipynb) |
| `JaspJIT.ipynb`: JIT compilation in JAX and qrisp, dynamic loops, resource estimation, boolean simulation, real-time programs (teleportation, repeat-until-success, dynamic sizes), several evaluation modes on one error correction example, and Catalyst | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PietropaoloFrisoni/iqm-qrisp-school-oct2026/blob/main/Session_3_Dynamic_Programming/JaspJIT.ipynb) |

## Bonus Material (optional)

| Notebook | Open in Colab |
|---|---|
| `BonusMaterial/PrimitivesInJax.ipynb`: building a custom JAX primitive from scratch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PietropaoloFrisoni/iqm-qrisp-school-oct2026/blob/main/Session_3_Dynamic_Programming/BonusMaterial/PrimitivesInJax.ipynb) |
| `BonusMaterial/StableHLOExport.ipynb`: inspecting and exporting compiled StableHLO | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PietropaoloFrisoni/iqm-qrisp-school-oct2026/blob/main/Session_3_Dynamic_Programming/BonusMaterial/StableHLOExport.ipynb) |
| `BonusMaterial/XLABackend.ipynb`: how XLA compiles and optimizes a jitted program | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PietropaoloFrisoni/iqm-qrisp-school-oct2026/blob/main/Session_3_Dynamic_Programming/BonusMaterial/XLABackend.ipynb) |
