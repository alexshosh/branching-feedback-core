# Branching feedback at an uncontrollable linearisation with applications to stabilisation, the Brockett integrator, control of frequency and Hopf bifurcation

Alex Shoshitaishvili (also published as A. N. Shoshitaishvili), Independent Researcher

<!-- DOI badge to be added after the first Zenodo release -->

## Abstract

At a working point where the linearisation of a plant is uncontrollable, no smooth feedback solves the qualitative-behaviour control (QBC) problem, that is, makes the closed loop reproduce a prescribed qualitative behaviour if its spectrum does not contain some uncontrollable eigenvalue. We show what can be done instead. The plant is coupled to a reference system by a coupling law depending on the states of both, and one looks for an invariant manifold x = F(z) of the combined system. Uncontrollability forces F to be singular at the working point. Over a state x the reference state z with F(z) = x is then in general not unique, and the coupling law gives one value on each such z: a branching feedback, whose branches are defined on regions of the state space glued together along strata of the caustic, which is the set of critical values of F, and possibly along other submanifolds chosen by design. The same reference and coupling serve a whole family of plants crossing the degeneracy, including the degenerate plant, which has no smooth stabiliser. This is the method of the author's 1990 paper (Adv. Soviet Math. 1), restated in the language of geometric control. From it we recall asymptotic stabilisation and the synthesis of a stable Andronov-Hopf bifurcation at a corank-one degeneracy. New are: stabilisation of the model x' = u^n for every n >= 2 with a rotating reference, and of its deformations; the nonholonomic (Brockett) integrator, with a closed-form synthesis with a rate independent of the initial point and, by rotating the branch, a continuous time-periodic stabiliser; and a cycle of prescribed frequency when the critical pair +-i omega_0 is uncontrollable, where no smooth feedback can change omega_0. This preprint is a short version; the proofs and further results are in the companion preprint.

This is the short version; see also the companion preprint *Qualitative-behaviour control with uncontrollable linearisation: branching feedback and the geometry of its singularity locus* (full version, with proofs).

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
