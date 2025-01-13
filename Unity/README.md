# Unity Environments for Synthetic Dataset Generation

## Overview
This folder contains Unity Environments and Randomizers specifically designed for generating synthetic datasets with increasing levels of realism. These environments were developed to replicate endoscopic surgical views and facilitate automated annotation using the **Unity Perception Package** ().

## Contents
1. **Random Scene**: 
   - Objects placed randomly to ensure diverse orientations and positions.
   - Randomized backgrounds for variability.
2. **Endoscope1 Scene**: 
   - Surgical tools (Cadiere Forceps, Needle Driver and Potts Scissors) positioned realistically on either side.
   - Needle and tissue located centrally to simulate typical suturing scenarios.
3. **Endoscope2 Scene**: 
   - Similar to Endoscope1 Enhanced lighting and rendering for higher realism.

## Features
- **Randomizers**:
  - Variability in object positions, textures, and lighting for diverse data generation.
  - Scripts written in C# for efficient parameter control.
- **Annotations**:
  - Automatic generation of bounding boxes and segmentation masks.

## Usage
To use these environments:
1. Import the Unity project.
2. Install the Unity Perception Package.
3. Run the provided scenes to generate annotated images.

## Citation
If you utilize these Unity environments in your research, please reference our work:
> *"Bridging the Sim-to-Real Gap for Robotic-Assisted Suturing through Hybrid Training Approaches"* [DOI/Link]

