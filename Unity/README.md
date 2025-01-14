# Unity Environments for Synthetic Dataset Generation

## Overview
This folder contains Unity Environments, with other useful files, and Randomizers specifically designed for generating synthetic datasets with increasing levels of realism. These environments were developed to replicate endoscopic surgical views and facilitate automated annotation using the [Unity Perception Package](https://docs.unity3d.com/Packages/com.unity.perception@1.0/manual/index.html).

## Contents:
1. **3D-Models**: 
   - 3D Models of objects as Unity file, also available as `.obj` files in [3D-Models](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/3D-Models) to allow for any changes
2. **Environments**
   1. **Random**: 
      - Objects placed randomly to ensure diverse orientations and positions.
      - Randomized backgrounds for variability.
   2. **Endoscope1**: 
      - Surgical tools (Cadiere Forceps, Needle Driver and Potts Scissors) positioned realistically on either side.
      - Needle and tissue located centrally to simulate typical suturing scenarios.
   3. **Endoscope2**: 
      - Similar to Endoscope1 but with enhanced lighting and rendering for higher realism.
   4. **Materials**: materials used in unity to give realism to objects
   5. **Configuration Files**: assets that define a taxonomy of labels for ground truth generation:
      1. **LabelConfiguration**
      2. **SegmentationLabelConfiguration** 
3. **Randomizers**:
   1. **MaterialSwapperRandomizer**: `C#` code to change objects' materials/colour during dataset generation
   2. **ToolSwapperRandomizer**: `C#` code to make objects appear and disappear during dataset generation in order to create diverse scenes


## Usage
To use these environments:
1. Install the [Unity Perception Package](https://docs.unity3d.com/Packages/com.unity.perception@1.0/manual/index.html).
2. Import the Unity files in your Unity project.
3. Follow Unity's Perception package [tutorial](https://github.com/Unity-Technologies/com.unity.perception) to make the best use of their resources and those available in this repository.
4. Run the provided scenes to generate annotated images.

## Citation
If you utilize these Unity environments in your research, please reference our work:
> *""* [DOI/Link]



[def]: 3D-Models