# Affine Observables, Mode Collapse, and Arithmetic Rigidity

**Author:** Tak Heung Sze  
**Official Website:** [recursivesequence.netlify.app](https://recursivesequence.netlify.app/)  
**License:** [CC BY 4.0](http://creativecommons.org/licenses/by/4.0)

## Overview
[cite_start]This research investigates low-dimensional linear discrete dynamical systems under constrained affine observations. [cite_start]It establishes a general mechanism where arithmetic restrictions and affine measurement design force a structural collapse of specific dynamical features[cite: 15, 25].

The study focuses on second-order linear recurrences defined by:
[cite_start]$$x_{n+1} = ax_{n} + bx_{n-1}, \quad a, b \in \mathbb{Z}$$ 

## Key Scientific Contributions
[cite_start]This work identifies three coupled consequences induced by affine observation under arithmetic constraints[cite: 20]:

* [cite_start]**Mode Collapse**: Oscillatory components of the system become unobservable[cite: 21].
* [cite_start]**Dimensional Reduction**: Admissible trajectories are confined to specific invariant lattices[cite: 22].
* [cite_start]**Arithmetic Rigidity**: Observed dynamics are reduced to simple translations on discrete sets, exhibiting modular locking[cite: 23].

[cite_start]The central insight is that spectral cancellation is not a free design choice but a structural necessity compatible with integrality and invariance[cite: 24].

## Mathematical Context
[cite_start]The system considers matrices with a dominant real eigenvalue $\lambda > 1$ [cite: 37] and a secondary real eigenvalue $\mu$ where $\mu < 0$ or $|\mu| [cite_start]\le 1$[cite: 38]. [cite_start]While classical linear filtering can eliminate modes via projection [cite: 43][cite_start], this paper proves that affine observation forces this collapse as an unavoidable consequence of arithmetic consistency[cite: 72].

### Canonical Example
[cite_start]For the system $x_{n+1} = x_{n} + 2x_{n-1}$[cite: 75]:
* [cite_start]**Eigenvalues**: $2$ and $-1$[cite: 76].
* [cite_start]**Affine Observable**: $\mathcal{H}(x,y) = 2x + \frac{y}{5}$ on the section where $y \equiv 0 \pmod 5$[cite: 78].
* [cite_start]**Result**: The state collapses onto the maximal invariant lattice[cite: 79]:
[cite_start]$$\Lambda = \{ (x_n, x_{n-1}) : x_n \equiv -2^n \pmod{15} \}$$ 

## Contents of this Repository
* [cite_start]`main.pdf`: Full research paper.
* For interactive demonstrations, please visit the official website: [recursivesequence.netlify.app](https://recursivesequence.netlify.app/).

## Citation
If you use this work in your research, please cite it as:
> Sze, T. H. (2026). [cite_start]Affine Observables, Mode Collapse, and Arithmetic Rigidity in Low-Dimensional Linear Discrete Dynamical Systems[cite: 2, 3].
