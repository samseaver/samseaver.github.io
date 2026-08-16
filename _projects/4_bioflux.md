---
layout: page
title: Neural-Mechanistic Hybrid Modeling for Metabolism (BioFlux)
description: Making genome-scale metabolic models predictive from data
img: assets/img/4.jpg
importance: 4
category: research
related_publications: elalaoui2025pinn, mishra2025sorghum
---

**BioFlux** is my line of work on **physics-informed machine learning** for metabolism:
neural-network *solvers* (no trained weights) that make genome-scale metabolic models *predictive*
from multi-omics data while respecting hard mechanistic constraints (mass balance), so predictions
stay biochemically valid.

- **First result:** a flexible **neural-mechanistic hybrid** that simulates the iron-deficiency
  response in plant plastidial metabolism (senior author, *bioRxiv*, 2025).
- **Method:** biochemistry-informed mechanistic gradient optimization with mass-balance constraints,
  run as a PINN in solver mode (no trained weights); convergence analysis across data-fit vs.
  mass-balance loss formulations.
- **Why it matters:** predict how a cell, strain, or plant will behave under perturbation — before
  it's measured.
