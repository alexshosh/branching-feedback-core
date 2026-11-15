# Branching feedback at an uncontrollable linearisation with applications to stabilisation, the Brockett integrator, control of frequency and Hopf bifurcation

Alex Shoshitaishvili (also published as A. N. Shoshitaishvili), Independent Researcher

<!-- DOI badge to be added after the first Zenodo release -->

## Abstract

The qualitative-behaviour control (QBC) problem is to make the closed loop reproduce a behaviour smoothly equivalent to a given one. At a working point where the linearisation of the plant is uncontrollable, this problem has no smooth solution if the spectrum of the given behaviour does not contain some uncontrollable eigenvalue. We show what can be done instead. The plant (state x) is coupled to a reference system (state z) by a coupling law u(x,z), and one looks for a surface x = F(z) that the joint motion keeps invariant. If the reference does not share an uncontrollable eigenvalue of the plant, F is singular at the working point, F^(-1)(x) has several points z for some x, and u(x,F^(-1)(x)) is a branching feedback. Its branches correspond to regions of the surface x = F(z) (most often adjacent), and a switching law defines the change of branch. We consider branching QBC after the author's papers of 1988-1992 and introduce two new notions: ultrastability, the uniform stabilisation of every plant of a family that may include plants with no smooth stabiliser, as when an actuator fails; and robust ultrastability, the same with one feedback for the whole family. The new results are: stabilisation of x' = u^n, n >= 2; ultrastability and robust ultrastability for x' = u^n + xA(x,conj(x),u,conj(u)) + conj(x)B(x,conj(x),u,conj(u)) (as in damping of a family of resonators); an ultrastable and robust ultrastable Andronov-Hopf bifurcation as the target behaviour, for a part of this family (as for resonators with damping, detuning and a Duffing term); two stabilisers of the nonholonomic (Brockett) integrator, a branching one and a continuous time-periodic one; and an attracting cycle of prescribed frequency at an uncontrollable critical pair +-i omega_0, where no smooth feedback can change omega_0. The proofs and further results are in the companion preprint.

This is the short version; see also the companion preprint *Qualitative-behaviour control with uncontrollable linearisation: branching feedback and the geometry of its singularity locus*, [doi:10.5281/zenodo.23847156](https://doi.org/10.5281/zenodo.23847156) (full version, with proofs).

## Files

- `Shoshitaishvili_BranchingFeedback_Core.tex` - LaTeX source (amsart; figures are inline TikZ, no external files).
- `Shoshitaishvili_BranchingFeedback_Core.pdf` - compiled preprint (pdflatex, 10 pages).

## Building

```
pdflatex Shoshitaishvili_BranchingFeedback_Core.tex
pdflatex Shoshitaishvili_BranchingFeedback_Core.tex
pdflatex Shoshitaishvili_BranchingFeedback_Core.tex
```

## Citing this work

See [`CITATION.cff`](CITATION.cff).

## License

Creative Commons Attribution 4.0 International (CC BY 4.0)

Copyright (c) 2026 Alex Shoshitaishvili
