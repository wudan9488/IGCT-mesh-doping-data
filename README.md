# IGCT-mesh-doping-data
Mesh and doping profile data for semiconductor device simulations (VTU format)

## About this dataset
This repository provides the **mesh data and doping profiles** used in the paper:
**Dan Wu Xiyu Peng, Chijie Zhuang\*,, Bo Lin, Qingyuan Shi, Li Li, Ruilang Ji, Xiaoguang Wei, Rong Zeng**,  
*Adaptive Time Step Control for Semiconductor Simulations*, submitted to **IEEE Transactions on Magnetics** (conference-related manuscript for COMPUMAG 2025).


## Files
- `asigct.vtu`  
  Contains node coordinates, unstructured mesh connectivity, and doping distribution field for the **AS-IGCT** device.

- `rbigct.vtu`  
  Contains node coordinates, unstructured mesh connectivity, and doping distribution field for the **RB-IGCT** device.


## Format
- File type: VTU (VTK XML, unstructured grid)
- Content:
  - **Point coordinates** (geometry)
  - **Cell connectivity** (elements)
  - **Doping values** (scalar field defined on points)


## Usage
These files can be opened in [ParaView](https://www.paraview.org/), or read programmatically with Python (`meshio`) or MATLAB (VTK readers).


