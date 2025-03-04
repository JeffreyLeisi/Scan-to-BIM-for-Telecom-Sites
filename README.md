# Scan-to-BIM: Optimizing the Planning Process for Telecom Sites with Advanced 3D Modeling

## Overview
This repository contains the code, methodology, and findings of my **Bachelor's Thesis** at **ETH Zürich**, conducted in collaboration with **Axians Schweiz AG**. The project focuses on developing an efficient **Scan-to-BIM** workflow to enhance the **planning process for telecom sites**. By leveraging **3D point cloud processing, mesh conversion, and BIM modeling**, the aim is to replace traditional, labor-intensive methods with a streamlined, automated approach.

## Project Scope
Telecom site planning requires precise **geometric information** about both the **surroundings** and the **building structure** to:
- Ensure accurate **Non-Ionizing Radiation (NIR) assessments** within a several-hundred-meter radius.
- Generate **building permit plans** and detailed pole and radio equipment placement data.

Currently, the process relies on **GNSS and total station measurements**, combined with outdated or unavailable architectural plans. This project proposes a modernized workflow that:
1. Converts **point clouds** to **meshes** and ensures **georeferencing** for site surroundings.
2. Converts **meshes** to **BIM models** for building structures.
3. Automates the generation of **top and front view plans** for regulatory compliance.

## Key Deliverables
- **Employer’s Information Requirements (EIR)**: Defines client-specific BIM expectations and deliverables.
- **BIM Execution Plan (BEP)**: Establishes standardized modeling workflows and data processing methodologies.
- **Implementation & Code**: Python scripts and tools for **point cloud processing, mesh generation, and BIM modeling**.

## Technologies Used
- **Point Cloud Processing**: Open3D, CloudCompare, Agisoft Metashape
- **Mesh Reconstruction**: PolyFit, RANSAC, Points2Poly
- **BIM Modeling**: Autodesk Revit, Scan-to-BIM plugins
- **Automation & Scripting**: Python

## Contributors
- **Jeffrey Leisi** – BSc. Geospatial Engineering, ETH Zürich
- **Supervisors**:  
  - **Océane Durand Maniclas** (ETH)  
  - **Forth Kasimir** (ETH)  
  - **Jean-Charles Schaegis** (Axians Schweiz AG)

## License
This project is intended for academic research and development. Licensing details will be specified based on final project scope.
