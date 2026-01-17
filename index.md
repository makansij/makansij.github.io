# Jordan Makansi

Quantum optimization and software engineer.
[About](#about-me) · [Experience](#experience) · [Publications](#publications) · [Projects](#projects) · [Education](#education) · [Contact](#contact)

---


I work on NISQ-era algorithms (QAOA, LR-QAOA), noise-aware benchmarking, and
practical applications like LABS, routing, and portfolio-type problems.

## Selected Projects

### A Greedy Quantum Route-Generation Algorithm for Vehicle Routing

Greedy, noise-robust QAOA variant for constrained vehicle routing problems that
exploits correlations between sampled bitstrings to guide route construction.

- Designed a noise-robust QAOA for constrained optimization problems which
  exploits correlation between samples, and provably converges to a feasible
  solution without post-processing.
- Showed the proposed algorithm obtains an ~80% lower optimality gap, in
  comparable time to state-of-the-art classical and quantum-inspired methods.
- Obtained computational results for graph instances up to 50 nodes using
  Qiskit and C++ on a high-performance computing cluster to deliver software
  artifacts for PWICE stakeholders (see Publications).

**Paper:** [arXiv:2405.03054](https://arxiv.org/abs/2405.03054)  
**Code:** [GitHub repo](https://github.com/makansij/A_Greedy_Quantum_Route-Generation_Algorithm)

