---
title: "Numerical Methods and Tools"
excerpt: "Many problems in astronomy are too complex to be solved exactly. This necessitates efficient and accurate methods of numerical approximation.<br/><img src='/images/numerical_methods.jpeg'>"
collection: portfolio
---

Gravity is a conceptually simple force, but in practice simple does not necessarily mean easy. In fact, the gravitational _N_-body problem has no useful exact analytic solution for _N_ \\(> 3\\). If you have come up with such a solution, please let me know! In the absence of a closed-form analytic solution, we turn to methods of numerical approximation to study the long-term dynamics of planetary systems. The most popular numerical integrator package for orbital dynamics is [REBOUND](https://rebound.readthedocs.io/en/latest/), which I have made several contributions to.

I led the addition of self-consistent tidal, spin and dynamical equations of motion in [REBOUNDx](https://reboundx.readthedocs.io/en/latest/effects.html), a library of add-ons for REBOUND. In [Lu et. al (2023)](https://iopscience.iop.org/article/10.3847/1538-4357/acc06d) we describe the implementation and usage of equilibrium tide theory in REBOUNDx, opening the door for easy and accessible exploration of the physics associated.

Recently, I led the development of a novel hybrid integrator TRACE, which is described in [Lu, Hernandez & Rein (2024)](https://ui.adsabs.harvard.edu/abs/2024arXiv240503800L/abstract). TRACE is specifically designed for fast and accurate integrations of planetary systems with close encounters, and for its use cases it may be up to 13 times faster than its competitors.

Relevant Publications:
1. Lu, Hernandez & Rein (2024), [In Review](https://ui.adsabs.harvard.edu/abs/2024arXiv240503800L/abstract)
2. Lu et. al (2023), [_ApJ_ **948** 41](https://iopscience.iop.org/article/10.3847/1538-4357/acc06d)
