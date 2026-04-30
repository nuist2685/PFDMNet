# PFDMNet

<div align="center">

**PFDMNet: Prior-Guided Frequency-Decoupled Mamba Network for Infrared Small Target Detection**

</div>

---

## Overview

PFDMNet is proposed for infrared small target detection in complex scenes. It uses frequency decomposition to separately describe background structures and target details, and further combines them with learnable feature modeling for more reliable small target segmentation.

The source code and related materials will be made publicly available after the manuscript is accepted.

---

## Difference-Driven Convolution Block

DDCB is designed to enhance local differences around small targets, making weak targets easier to distinguish from surrounding clutter.

<div align="center">
  <img src="./assets/DDCB.png" width="850">
  <br>
  <em>Fig. 1. Structure of the difference-driven convolution block.</em>
</div>

---

## Frequency Modeling Module

FMM decomposes input features into different frequency components, allowing background structures and local details to be processed separately.

<div align="center">
  <img src="./assets/FMM.jpg" width="850">
  <br>
  <em>Fig. 2. Structure of the frequency modeling module.</em>
</div>

---

## Role-Aware Fusion Module

RAFM models shallow and deep features according to their different roles before fusion, making cross-level feature fusion more suitable for small target segmentation.

<div align="center">
  <img src="./assets/RAFM.jpg" width="850">
  <br>
  <em>Fig. 3. Structure of the role-aware fusion module.</em>
</div>

---

## Visual Comparison

The visual comparison shows the segmentation results of different infrared small target detection methods. PFDMNet produces more complete target regions and fewer background responses in challenging scenes.

<div align="center">
  <img src="./assets/Comparison.png" width="900">
  <br>
  <em>Fig. 4. Visual comparison results of different IRSTD methods.</em>
</div>

---

## 3D Visualization

The 3D visualization shows the response maps of different methods. PFDMNet gives a sharper and more concentrated response around the target region.

<div align="center">
  <img src="./assets/3d_visual.png" width="900">
  <br>
  <em>Fig. 5. 3D visualization results of different IRSTD methods.</em>
</div>

---

## Code Release

The source code and detailed usage instructions will be released after the manuscript is accepted.
