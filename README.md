# Volume Gradient Visualization in Java

This Java project processes raw 3D volumetric data and visualizes it as 2D image slices in grayscale and RGB. It demonstrates how to extract and visualize both raw and gradient-based features of medical or scientific volumetric datasets.

---
![image](https://github.com/user-attachments/assets/78841051-d385-4db5-b5f8-7ee7dbaf81b4)
![image](https://github.com/user-attachments/assets/e886ba6f-351f-4b3d-81de-8ce060380e6a)
![image](https://github.com/user-attachments/assets/345e9429-92c5-41cc-9f18-1d8a1d1a25a9)

## Overview

This project performs the following steps:

1. **Read a raw volume dataset** from a `.raw` binary file.
2. **Extract a 2D slice** at a specified depth (`z-index`).
3. **Compute gradients** in 3D and extract:
   - Gradient **magnitude** (grayscale)
   - Gradient **vectors** (RGB)
4. **Save all results** as `.tiff` images.

---

## Files

- `Lab1.java` – Main class that reads data, processes it, and saves outputs.
- `Volume.java` – Handles volume data reading and gradient calculations.
- `im.tiff` – 2D grayscale slice of the volume.
- `imGradientMagnitude.tiff` – Grayscale visualization of gradient magnitudes.
- `imGradient.tiff` – RGB visualization of gradient vectors.

---

## Requirements

- Java 8 or later
- A TIFF image viewer (like ImageJ, IrfanView, Photoshop, or GIMP)

---

## Compilation & Execution

### Compile

```bash
javac Lab1.java
