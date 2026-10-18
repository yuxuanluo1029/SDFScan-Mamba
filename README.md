# SDFScan-Mamba

This repository is the official implementation of *SDFScan-Mamba: Lightweight Single-Encoder Dual-Frequency Scan-Aware Mamba Network for V-D-T Salient Object Detection*.

**The source code will be released upon acceptance of the paper.**

## Architecture

<p align="center">
  <img src="assets/overall.png" width="100%" alt="Overall architecture of SDFScan-Mamba">
</p>

<p align="center">
  <em>Overall architecture of SDFScan-Mamba.</em>
</p>

## Results

| Dataset | S<sub>m</sub> &uarr; | MAE &darr; | E<sub>&xi;</sub><sup>mean</sup> &uarr; | F<sub>&beta;</sub><sup>mean</sup> &uarr; |
|:--|:--:|:--:|:--:|:--:|
| VDT-2048 | **0.9302** | **0.0026** | **0.9844** | **0.8908** |
| LiTR-2654 | **0.8833** | **0.0430** | **0.9169** | **0.8615** |

SDFScan-Mamba contains only **1.2M parameters** and requires **2.98G FLOPs**.

## Code

The source code, pretrained models, and prediction maps are not publicly available at this stage. They will be released after the paper is accepted.

## Citation

Citation information will be updated after publication.
