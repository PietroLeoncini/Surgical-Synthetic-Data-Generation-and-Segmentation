# Surgical-Synthetic-Data-Generation-and-Segmentation

This repository contains resources developed to contribute research toward suture automation:

- [**3D-Models**](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/3D-Models): Task-specific `.obj` models for robotic tools, surgical needle and tissue-cuts.
- [**Datasets**](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/Datasets)**: 
    1. Annotated `rgb` images generated in Unity, including bounding boxes and instance segmentation annotations as `txt` files in YOLO format. 
    2. Annotated `rgb` images generated in Unity with enhanced realism using [Cycle-GAN-TURBO](https://github.com/GaParmar/img2img-turbo) and enhanced resolution using [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN), including instance segmentation annotations as 'txt' files in YOLO format.

- [**Unity files**](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/Unity):
    1. [3D-Models](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/Unity/3D-Models): 3d models as unity file ready to use in Unity
    2. [Environments](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/Unity/Environments): 
        - three Simulated surgical scenarios with varying levels of realism used to generate three different synthetic datasets.
        - materials used to change visual features of objects
        - configuration files to create ground-truth annotations
        - New version of the simulated surgical scenario
    3. [Randomizers](https://github.com/PietroLeoncini/Surgical-Synthetic-Data-Generation-and-Segmentation/tree/main/Unity/Randomizers): `C#` scripts to introduce variability in the simulation and so in the datasets
- **Instance Segmentation Models**: 
    1. A YOLOv8m-based model trained for surgical tool instance segmentation.
    2. A YOLO11m-based model trained for surgical tool instance segmentation.

## Usage Instructions

1. Install the [Unity Perception Package](https://docs.unity3d.com/Packages/com.unity.perception@1.0/manual/index.html).
2. Download and import the Unity files, provided in this repository, in your Unity project.
3. Follow Unity's Perception package [tutorial](https://github.com/Unity-Technologies/com.unity.perception) to make the best use of their resources and those available in this repository.
4. Modify these environments or run the simulation to generate new annotated images.
5. Use the datasets for training or fine-tuning your own models or testing pre-trained models.

## Citation

If you use this repository, please cite:

```bibtex
@article{Leoncini2025,
  title={A reproducible framework for synthetic data generastion and instance segmentation in robotic suturing},
  author={Leoncini Pietro, Marzola Francesco, Pescio Matteo, Casadio Maura, Arezzo Alberto, Dagnino Giulio},
  journal={International Journal of Computer Assisted Radiology and Surgery},
  year={2025},
  volume={20},
  pages={1567 - 1576},
  doi={10.1007/s11548-025-03460-8}
}
```
