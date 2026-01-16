# Affine Observables, Mode Collapse, and Arithmetic Rigidity

**Author:** Tak Heung Sze [cite: 3]
**Official Website:** [recursivesequence.netlify.app](https://recursivesequence.netlify.app/)
**License:** [CC BY 4.0](http://creativecommons.org/licenses/by/4.0) 

---

## Overview
This research investigates low-dimensional linear discrete dynamical systems under constrained affine observations. It establishes a general mechanism where arithmetic restrictions and affine measurement design force a structural collapse of specific dynamical features[cite: 20, 25].

The study focuses on second-order linear recurrences defined by:
$$x_{n+1} = ax_{n} + bx_{n-1}, \quad a, b \in \mathbb{Z}$$ 

## Key Scientific Contributions
This work identifies three coupled consequences induced by affine observation under arithmetic constraints[cite: 20]:

* **Mode Collapse**: Oscillatory components of the system become unobservable.
* **Dimensional Reduction**: Admissible trajectories are confined to specific invariant lattices[cite: 22].
* **Arithmetic Rigidity**: Observed dynamics are reduced to simple translations on discrete sets, exhibiting modular locking.

The central insight is that spectral cancellation is not a free design choice but a structural necessity compatible with integrality and invariance.

## Mathematical Context
The system considers matrices with a dominant real eigenvalue $\lambda > 1$ [cite: 37] and a secondary real eigenvalue $\mu$ where $\mu < 0$ or $|\mu| []\le 1$[cite: 38]. []While classical linear filtering can eliminate modes via projection , this paper proves that affine observation forces this collapse as an unavoidable consequence of arithmetic consistency.

### Canonical Example
For the system $x_{n+1} = x_{n} + 2x_{n-1}$:
* **Eigenvalues**: $2$ and $-1$[cite: 76].
* **Affine Observable**: $\mathcal{H}(x,y) = 2x + \frac{y}{5}$ on the section where $y \equiv 0 \pmod 5$.
* **Result**: The state collapses onto the maximal invariant lattice[cite: 79]:
$$\Lambda = \{ (x_n, x_{n-1}) : x_n \equiv -2^n \pmod{15} \}$$ [cite: 80]

## Contents of this Repository
* `main.pdf`: Full research paper[cite: 2].
* For interactive demonstrations, please visit the official website: [recursivesequence.netlify.app](https://recursivesequence.netlify.app/).

## Citation
If you use this work in your research, please cite it as:
> Sze, T. H. (2026). Affine Observables, Mode Collapse, and Arithmetic Rigidity in Low-Dimensional Linear Discrete Dynamical Systems.
