# AI-Native Lattice Diagram Generator

This repository is the public showcase for my resume project:
**AI-Native Lattice Diagram Generation MVP**.

The project explores an automated workflow for producing physics-inspired
lattice diagrams by connecting lattice geometry logic, constraint-aware
parameter generation, and SDXL-based image generation.

## Problem

Traditional many-body physics lattice diagrams often require manual coding,
repeated parameter tuning, and slow visual iteration. The workflow can be
time-consuming, visually rigid, and difficult to reuse across lattice types.

## MVP Architecture

- **Interactive Web UI:** Configures lattice type, visual style, and generation parameters.
- **Python backend:** Generates lattice geometry parameters and physics-constrained inputs.
- **SDXL generation layer:** Calls an SDXL image-generation API for diagram rendering.
- **Physics-Based Validation:** Checks generated lattice nodes, connection relations, and geometric symmetry against predefined physical constraints.

## Resume-Aligned Highlights

- Built the MVP independently from 0 to 1.
- Connected the underlying physics logic, image-condition control, and multimodal generation model into one workflow.
- Tested the workflow on 4 representative lattice categories.
- Reduced the production time of a single diagram from about 3 hours to about 3 minutes.
- Reduced manual parameter-tuning iterations from about 30 rounds to about 3 rounds.

## Demo

The image below shows the public demo material for the workflow.

<img width="2658" height="776" alt="AI_Agent_Lattice_60x_Demo" src="https://github.com/user-attachments/assets/112f05b2-c23f-43f9-957b-80a73b10d09d" />
