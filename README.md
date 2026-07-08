# ObjResizer for 3ds Max

A professional, high-precision script designed to resize objects in 3ds Max without the usual headaches of coordinate system errors, scaling artifacts, or geometry deformation.

## Features
- **Smart Coordinate System:** Supports both World and Local coordinate spaces.
- **FFD Preservation:** An option to keep the FFD modifier stack intact for parametric control.
- **Smart Vertex Move:** A custom method for non-destructive resizing.
- **Precision:** Uses high-precision matrix transformations for accurate dimensions.
- **Undo Support:** Fully compatible with 3ds Max Undo/Redo stack.

## Installation
1. Download the [MRT_ObjResizer_v1.0.zip](https://github.com/mrtvisual/3Ds-max-Object-Resizer/raw/main/MRT_ObjResizer_v1.0.zip) file.
2. Simply extract the file and **drag and drop** the `.mcr` file into your 3ds Max viewport.
3. The script will be available in the `mrtTools` category in your Customize User Interface menu.

## Usage
- Open the script from your toolbar or menu.
- Use the **"Get Real Dimensions"** button to read your current object's bounding box.
- Set your target dimensions.
- Choose your Resize Strategy (Standard Scale, FFD, or Smart Vertex Move).
- Click **"Apply"**.

## Support
If you have any questions or feature requests, feel free to open an issue in this repository.

---
*Created by Mohammad Reza Taheri*
