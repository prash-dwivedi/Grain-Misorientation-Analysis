# Misorientation Angle Calculation Script for OVITO

## Overview
This repository contains a Python script for calculating the misorientation angle between two grains using their quaternion orientations. The script is designed for use with OVITO (Open Visualization Tool) and integrates seamlessly with the Grain Segmentation modifier to retrieve grain orientation data.

## Purpose
The misorientation angle is a crucial parameter for understanding grain boundary behavior in polycrystalline materials. This script simplifies the calculation process by working directly within OVITO, eliminating the need for external tools or software. Researchers can use this script to analyze the crystal orientation relationships between grains efficiently.

## Features
- Calculates the misorientation angle between two grains using quaternions.
- Compatible with OVITO's Grain List Data Table.
- Includes detailed error handling for missing or invalid grain IDs.
- Easy integration into OVITO's Python scripting environment.

## How to Use
1. Load your data into OVITO.
2. Apply the Grain Segmentation modifier to generate the Grain List.
3. Attach this script to the pipeline and specify the grain IDs for the two grains of interest.
4. The misorientation angle will be printed in the console.

## Requirements
- OVITO Pro (with Grain Segmentation analysis capabilities)
- Python (compatible with OVITO’s scripting environment)
- NumPy library

## Developed by
Prashant Dwivedi  
Ph.D. Researcher in Material Science  
Contact: [Your Email]

## License
This project is released under the MIT License. Feel free to modify and use it for your research.
