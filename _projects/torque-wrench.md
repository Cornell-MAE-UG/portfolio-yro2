---
layout: project
title: Torque Wrench Design and Analysis
description: Design, optimization, and finite element analysis of a non-ratcheting torque wrench to meet multiple safety and sensitivity requirements.
technologies: [Finite Element Analysis (ANSYS), CAD Modeling (Fusion), Python]
image: /assets/images/disp.png 
---

As part of the MAE 3270 course (Mechanics of Engineering Materials), I undertook a design project focused on creating an instrumented torque wrench rated for 600 in-lbf. The design goal was to select appropriate materials and dimensions to achieve high sensitivity (at least 1.0 mV/V output) while satisfying strict safety factors for static strength, fatigue, and fracture mechanics.

The core challenge was to iterate a design from an initial baseline using a Python script for hand calculations, then validate and refine the final design using Finite Element Analysis (FEM).

Using FEM in ANSYS, I performed a stress analysis on the optimized design to precisely determine the maximum normal stress, load point deflection, and strain at the gauge locations. A key learning objective was to compare and understand the results from the simplified hand calculations versus the more detailed FEM results, particularly regarding stress concentrations and deflection. The final output included the CAD model, material justification, FEM contour plots, and a summary of the wrench's sensitivity.

[Find the full analysis here]({{ "/assets/FINAL.pdf" | relative_url }}) in PDF format.