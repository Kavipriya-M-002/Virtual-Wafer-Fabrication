# Virtual-Wafer-Fabrication

## Overview

This project explores virtual semiconductor fabrication using the **PhotolithoTwin Photolithography Digital Twin**, developed by Zafer Mutlu at the University of Arizona. The simulation focuses on photolithography, photoresist behavior, aerial image formation, exposure dose, resist development, critical dimension (CD) bias, and final patterned wafer formation after lift-off.

Two custom patterns, **"MKP"** and **"KAVI"**, were simulated using negative and positive photoresists, respectively, to explore process parameters, resist profiles, and dimensional accuracy.

## Tools and Process Parameters

- **Platform:** PhotolithoTwin — Photolithography Digital Twin
- **Exposure wavelength:** 248 nm (DUV)
- **Numerical aperture:** 0.63
- **Resist thickness:** 500 nm
- **Exposure dose:** 120 mJ/cm²
- **Development time:** 45 s
- **Soft bake:** 95°C for 60 s
- **Negative resist:** SU-8 / cross-linking, with post-exposure bake at 110°C for 60 s
- **Positive resist:** DNQ-Novolac, with post-exposure bake disabled

## Simulation and Critical Dimension Analysis

The pattern "MKP" was simulated using negative photoresist, while the pattern "KAVI" was simulated using positive photoresist. The experiments included mask design, aerial image and exposure dose visualization, developed-resist analysis, proximity analysis, linewidth-versus-exposure-dose plots, and final patterned wafer observation.

Critical dimension bias was analyzed by comparing the target linewidth with the simulated linewidth at different resist heights.

| Parameter | MKP — Negative Resist | KAVI — Positive Resist |
|---|---:|---:|
| Target CD | 3000 nm | 1000 nm |
| Measured CD at 50% height | 2500 nm | 875 nm |
| Measured CD at 80% height | 2250 nm | 875 nm |
| CD bias | −500 nm | −125 nm |
| Sidewall angle | 40.7° | 47.1° |

Both simulations showed negative CD bias, indicating that the measured linewidth was smaller than the target dimension. The developed-resist profiles and dose-response plots provided additional insight into pattern fidelity, dimensional accuracy, and process sensitivity.

## Key Learning Outcomes

- Understood the fundamentals of photolithography and virtual semiconductor fabrication.
- Explored positive and negative photoresist behavior.
- Studied aerial image formation, exposure dose distribution, and resist development.
- Analyzed critical dimension bias and compared target and measured linewidths.
- Examined resist profiles, sidewall angles, and linewidth variation with exposure dose.
- Gained practical familiarity with semiconductor process parameters and virtual fabrication analysis.

## Simulation Outputs

The repository includes simulation screenshots and reports covering mask designs, aerial images, exposure dose profiles, developed resist, proximity analysis, final patterned wafers, and linewidth-versus-exposure-dose characteristics.

## Platform Reference

[Photolithography Digital Twin — Zafer Mutlu, University of Arizona](https://zafermutlu.arizona.edu/training)
