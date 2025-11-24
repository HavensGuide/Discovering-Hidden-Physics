# Discovering-Hidden-Physics
This repository contains the full research notebook, code, and supplemental materials accompanying the preprint:  “A Non-Parametric Framework for Physics Discovery via Drift–Diffusion Estimation, Statistical Geometry, and Optimal Transport” (ArXiv preprint link will be added once posted.)

The project develops a two-step statistical–geometric method for reconstructing the underlying physical laws of a system directly from observational data, without assuming any specific model class.

---

## Overview

The framework recovers:

* Drift fields ( u(x) )
* Diffusion fields ( D(x) )
* Probability flux and divergence
* Koopman operator spectral evolution
* Fisher and Wasserstein geometric structure
* Thermodynamic decomposition (excess vs. housekeeping drift)
* Onsager–Machlup action minimizers

The method is entirely non-parametric and validated using noisy diffusion data. It accurately reconstructs drift, diffusion, and derived quantities such as the Reynolds number using multiple independent prediction pipelines.

---

## Method Summary

1. **Statistical Reconstruction**
   A kernel density estimator is used to recover the empirical log-density and its spatial derivatives from observational data.

2. **Physics-Constrained Optimization**
   The drift and diffusion fields are optimized to satisfy the Fokker–Planck equation, flux constraints, and regularity conditions while matching the observed density evolution.

This two-step approach separates the statistical problem from the physical one, preventing oversmoothing and overfitting.


