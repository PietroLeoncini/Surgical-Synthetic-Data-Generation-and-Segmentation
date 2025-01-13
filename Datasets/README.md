# Synthetic and Real Datasets for Computer Vision in Robotic Suturing

## Overview
This folder contains Real and Synthetic datasets for training computer vision models in robotic suturing tasks. The datasets include bounding boxes and instance-based (objects' contours) annotations, offering a task-specific resource for advancing surgical automation.

## Contents
1. **Synthetic Datasets**: RGB Images + txt annotations
   - **Random**: General-purpose dataset with randomized object placements (1000 images).
   - **Endoscope1**: Typical suturing scenario (1000 images).
   - **Endoscope2**: Realistic lighting and context (1000 images).
2. **Real Dataset**: RGB Images + txt annotations
   - 200 manually annotated real images with Roboflow.

## Annotations
- **Bounding Boxes**: For object detection tasks.
- **Instance Segmentation**: For instance segmentation tasks.

## Generation
- **Synthetic datasets** were generated using Unity environments and 3D models, provided in this GitHub repository, exploiting Unity's Perception Package. It is recommended to look at https://github.com/Unity-Technologies/com.unity.perception which contains a tutorial on how to make the most of the functionality of Unity with the perception package
- **Real images** were manually annotated using **Roboflow** (https://roboflow.com/).

## Applications
These datasets can be used for:
- **Supervised learning**: Training detection and segmentation models.
- **Semi-supervised learning**: Fine-tuning pre-trained models with minimal data.
- **Transfer learning**: Adapting models trained on general surgical contexts to robotic suturing.

## Citation
If you use these datasets, kindly cite our publication:
> *""* [DOI/Link]

