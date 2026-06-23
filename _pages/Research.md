---
title: "Research"
permalink: /research/
author_profile: true
---

My research develops mechanics-based models and experimental interpretation tools for fracture and transport in geomaterials, with applications to hydraulic fracturing, geological carbon storage, geothermal energy, and subsurface energy systems. A central theme of my work is to understand how fractures initiate, propagate, branch, and remain conductive in quasi-brittle rocks under coupled mechanical, hydraulic, and chemical processes.

---

## Regularized Fracture Modeling of Quasi-Brittle Materials

Quasi-brittle materials such as concrete, rock, and other geomaterials exhibit distributed damage and finite fracture process zones before complete crack formation. When modeled using local damage formulations, this process often suffers from spurious mesh sensitivity, where the predicted failure behavior, crack path, and energy dissipation depend on the size and shape of the finite element mesh. 

The smooth crack band model addresses this issue by introducing a localization limiter characterized by the second gradient of the displacement vector field, including the material rotation gradient. I developed an efficient numerical implementation of this model using a Lagrange multiplier approach and demonstrated its performance through user-defined elements in ABAQUS.


**Related papers:**

* [**Smooth Lagrangian crack band model based on spress-sprain relation and Lagrange multiplier constraint of displacement gradient**](https://asmedigitalcollection.asme.org/appliedmechanics/article/91/3/031007/1169714/Smooth-Lagrangian-Crack-Band-Model-Based-on-Spress)<br>
   **A. T. Nguyen**, H. Xu, K. Matouš, and Z. P. Bažant, *Journal of Applied Mechanics*, 91(3).

* [**Sprain energy consequences for damage localization and fracture mechanics**](https://doi.org/10.1073/pnas.2410668121)<br>
   H. Xu, **A. T. Nguyen**, and Z. P. Bažant, *Proceedings of the National Academy of Sciences*, 121(40), e2410668121.

* [**Smooth Lagrangian crack band model with softening spress-sprain relation and crack width prediction**](https://doi.org/10.1016/j.ijnonlinmec.2026.105340)<br>
   H. Xu, Y. Zhao, **A. T. Nguyen**, and Z. P. Bažant, *International Journal of Non-Linear Mechanics*, 186, 105340.

---

## Fast Permeability Testing of Tight Rocks

Low-permeability rocks are important for geological carbon storage, geothermal reservoirs, and subsurface energy systems, but their permeability can be difficult to measure accurately. Conventional pulse-decay permeability tests may require long equilibration times, during which leakage, temperature drift, and storage effects can strongly affect the interpretation.

I developed a fast transient permeability measurement framework that extracts permeability from the early-time response of one-chamber pressure pulse-decay tests. The method accounts for poroelastic storage and system compliance and enables permeability estimation before full pressure equilibration is reached. This approach significantly reduces testing time for tight rocks while maintaining a clear analytical connection between pressure decay and rock permeability.

**Related papers:**

* [**A rapid permeability test of low-porosity rock based on analysis of initial pressure pulse decay: experimental validation**](https://link.springer.com/article/10.1007/s00603-026-05517-9)<br>
   **A. T. Nguyen** (co-first author), P. Asem, Y. Zhao, J. Labuz, and Z. P. Bažant, *Rock Mechanics and Rock Engineering*. Published online.

* [**Fast permeability measurement for tight reservoir cores using only initial data of the one-chamber pressure pulse decay test**](https://doi.org/10.1016/j.jmps.2024.105805)<br>
   **A. T. Nguyen**, P. Asem, Y. Zhao, and Z. P. Bažant, *Journal of the Mechanics and Physics of Solids*, 192, 105805.

---

## Multiphysics Fracture and Hydraulic Fracture Branching

Hydraulic fracture networks in subsurface formations are governed by coupled fluid flow, rock deformation, damage evolution, and pre-existing geological heterogeneity. Understanding when hydraulic fractures remain planar, branch, or coalesce is important for designing stimulation strategies that enhance permeability while limiting uncontrolled fracture growth and induced seismicity.

I developed and implemented poromechanical models for hydraulic fracture propagation and branching in rocks with pre-existing weak layers. The framework couples damage evolution, fluid flow, pressure-dependent permeability, and anisotropic poromechanical response. These models help explain how injection conditions and rock heterogeneity control the transition from localized fracture growth to complex branching patterns.

**Related papers:**

* [**A poromechanical model for the branching of hydraulic fractures in rocks with pre-existing weak layers**](https://onepetro.org/ARMAUSRMS/proceedings-abstract/ARMA25/ARMA25/786316)<br>
   H. Xu, **A. T. Nguyen**, Y. Zhao, and Z. P. Bažant, *59th U.S. Rock Mechanics/Geomechanics Symposium*, Santa Fe, New Mexico, USA. American Rock Mechanics Association.

---

## Chemo-Hydraulic and Osmotic Effects in Shale

Fluid transport in shale and other chemically active tight rocks can be strongly affected by osmotic pressure gradients, ion diffusion, and fluid-rock interactions. These effects can alter apparent permeability, drive long-term stress redistribution, and contribute to crack formation over geological time scales.

I developed analytical and mechanics-based models to study how osmotic pressure gradients influence water diffusion and permeability interpretation in porous rock. This work shows that neglecting osmotic effects can lead to misleading permeability estimates in shale. I also contributed to a crack-spacing theory in which ion-diffusion-driven stress interactions explain the formation of nearly uniform parallel crack systems over geological time.

**Related papers:**

* [**Osmotic control of the spacing of parallel shear cracks in shale growing subcritically in geologic past**](https://www.sciencedirect.com/science/article/pii/S0022509625004028)<br>
   Y. Zhao, **A. T. Nguyen**, H. T. Nguyen, and Z. P. Bažant, *Journal of the Mechanics and Physics of Solids*, 207, 106428.
* [**Osmotic pressure gradient effects on water diffusion in porous rock: Can they pervert permeability tests?**](https://doi.org/10.1115/1.4063030)<br>
   Z. P. Bažant and **A. T. Nguyen**, *Journal of Applied Mechanics*, 90(12).

