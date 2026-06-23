---
title: "Research"
permalink: /research/
author_profile: true
---

# Research

My research develops mechanics-based models and experimental interpretation tools for fracture and transport in geomaterials, with applications to hydraulic fracturing, geological carbon storage, geothermal energy, and subsurface energy systems. A central theme of my work is to understand how fractures initiate, propagate, branch, and remain conductive in quasi-brittle rocks under coupled mechanical, hydraulic, and chemical processes.

---

## Regularized Fracture Modeling of Quasi-Brittle Materials

Quasi-brittle materials such as concrete, rock, and other geomaterials exhibit distributed damage and finite fracture process zones before complete crack formation. When modeled using local damage formulations, this process often suffers from spurious mesh sensitivity, where the predicted failure behavior, crack path, and energy dissipation depend on the size and shape of the finite element mesh. 

The smooth crack band model addresses this issue by introducing a localization limiter characterized by the second gradient of the displacement vector field, including the material rotation gradient. I developed an efficient numerical implementation of this model using a Lagrange multiplier approach and demonstrated its performance through user-defined elements in ABAQUS.


**Related papers:**

* **Smooth Lagrangian crack band model with softening spress-sprain relation and crack width prediction**
  H. Xu, Y. Zhao, **A. T. Nguyen**, and Z. P. Bažant, *International Journal of Non-Linear Mechanics*, 2026.

* **Sprain energy consequences for damage localization and fracture mechanics**
  H. Xu, **A. T. Nguyen**, and Z. P. Bažant, *Proceedings of the National Academy of Sciences*, 2024.

* **Smooth Lagrangian crack band model based on spress-sprain relation and Lagrange multiplier constraint of displacement gradient**
  **A. T. Nguyen**, H. Xu, K. Matouš, and Z. P. Bažant, *Journal of Applied Mechanics*, 2023.

---

## Fast Permeability Testing of Tight Rocks

Low-permeability rocks are important for geological carbon storage, geothermal reservoirs, and subsurface energy systems, but their permeability can be difficult to measure accurately. Conventional pulse-decay permeability tests may require long equilibration times, during which leakage, temperature drift, and storage effects can strongly affect the interpretation.

I developed a fast transient permeability measurement framework that extracts permeability from the early-time response of one-chamber pressure pulse-decay tests. The method accounts for poroelastic storage and system compliance and enables permeability estimation before full pressure equilibration is reached. This approach significantly reduces testing time for tight rocks while maintaining a clear analytical connection between pressure decay and rock permeability.

**Related papers:**

* **A rapid permeability test of low-porosity rock based on analysis of initial pressure pulse decay: experimental validation**
  **A. T. Nguyen** co-first author, P. Asem, Y. Zhao, J. Labuz, and Z. P. Bažant, *Rock Mechanics and Rock Engineering*, 2026.

* **Fast permeability measurement for tight reservoir cores using only initial data of the one-chamber pressure pulse decay test**
  **A. T. Nguyen**, P. Asem, Y. Zhao, and Z. P. Bažant, *Journal of the Mechanics and Physics of Solids*, 2024.

* **Fast permeability measurements of tight rock: theoretical study and experimental validation**
  **A. T. Nguyen**, P. Asem, J. Matter, J. F. Labuz, and Z. P. Bažant, *59th U.S. Rock Mechanics/Geomechanics Symposium*, 2025.

* **Rapid in-situ permeability estimation of reservoir rocks from fall-off tests using a parabolic approximation of axisymmetric diffusion**
  **A. T. Nguyen**, Y. Zhao, Y. Niu, and Z. P. Bažant, *60th U.S. Rock Mechanics/Geomechanics Symposium*, 2026.

---

## Multiphysics Fracture and Hydraulic Fracture Branching

Hydraulic fracture networks in subsurface formations are governed by coupled fluid flow, rock deformation, damage evolution, and pre-existing geological heterogeneity. Understanding when hydraulic fractures remain planar, branch, or coalesce is important for designing stimulation strategies that enhance permeability while limiting uncontrolled fracture growth and induced seismicity.

I developed and implemented poromechanical models for hydraulic fracture propagation and branching in rocks with pre-existing weak layers. The framework couples damage evolution, fluid flow, pressure-dependent permeability, and anisotropic poromechanical response. These models help explain how injection conditions and rock heterogeneity control the transition from localized fracture growth to complex branching patterns.

**Related papers:**

* **A poromechanical model for hydraulic fracture branching in rocks with pre-existing weak layers and crack-parallel stress**
  **A. T. Nguyen**, H. Xu, Y. Zhao, and Z. P. Bažant. Manuscript in preparation.

* **A poromechanical model for the branching of hydraulic fractures in rocks with pre-existing weak layers**
  H. Xu, **A. T. Nguyen**, Y. Zhao, and Z. P. Bažant, *59th U.S. Rock Mechanics/Geomechanics Symposium*, 2025.

* **Hydraulic crack propagation and rock permeability under osmotic pressure gradients with implications for deep CO₂ sequestration and fracking**
  Z. P. Bažant, **A. T. Nguyen**, H. Xu, P. Asem, and J. F. Labuz, *58th U.S. Rock Mechanics/Geomechanics Symposium*, 2024.

---

## Chemo-Hydraulic and Osmotic Effects in Shale

Fluid transport in shale and other chemically active tight rocks can be strongly affected by osmotic pressure gradients, ion diffusion, and fluid-rock interactions. These effects can alter apparent permeability, drive long-term stress redistribution, and contribute to crack formation over geological time scales.

I developed analytical and mechanics-based models to study how osmotic pressure gradients influence water diffusion and permeability interpretation in porous rock. This work shows that neglecting osmotic effects can lead to misleading permeability estimates in shale. I also contributed to a crack-spacing theory in which ion-diffusion-driven stress interactions explain the formation of nearly uniform parallel crack systems over geological time.

**Related papers:**

* **Osmotic control of the spacing of parallel shear cracks in shale growing subcritically in geologic past**
  Y. Zhao, **A. T. Nguyen**, H. T. Nguyen, and Z. P. Bažant, *Journal of the Mechanics and Physics of Solids*, 2026.

* **Osmotic pressure gradient effects on water diffusion in porous rock: Can they pervert permeability tests?**
  Z. P. Bažant and **A. T. Nguyen**, *Journal of Applied Mechanics*, 2023.

* **The prospect of massive sequestration of atmospheric CO₂ in deep formations of basalt or peridotite appraised by fracture, diffusion and osmosis analysis**
  Z. P. Bažant, H. Xu, **A. T. Nguyen**, J. W. Carey, and M. Khan, *57th U.S. Rock Mechanics/Geomechanics Symposium*, 2023.
