# fMRI-Visualisation-Alzheimers

## Project Description
This project visualises fMRI data related to Alzheimer's Disease using Python. By utilising data from Neurosynth, the analysis highlights brain regions associated with specific cognitive and clinical terms. Outputs include functional overlays on anatomical scans and histograms of intensity values, customised for better understanding and interpretation.

---

## Table of Contents
1. **Data**
   - **Functional data**: A uniformity test map indicating statistical associations.
   - **Anatomical data**: A anatomical MRI scan.  
   Data is sourced from [Neurosynth - Alzheimer's Disease](https://neurosynth.org/analyses/terms/alzheimer%20disease/).

2. **Notebook**
   - `Pycourse_Assignment_AD.ipynb`: The main Jupyter Notebook that contains all code, analysis, and visualisations for the project.

3. **Visualisations**
   - **Functional brain map**: Overlay of functional data on anatomical MRI scan.
   - **Histogram**: Intensity value distribution for fMRI data.

---

## Instructions for Use
1. **Download Data**  
   - Visit the [Neurosynth - Alzheimer's Disease](https://neurosynth.org/analyses/terms/alzheimer%20disease/) page.  
   - Under **Layers**, download:
     - The **Functional Data** file (`uniformity-test`).
     - The **Anatomical MRI Data** file (`anatomical`).

2. **Organise Files**  
   - Place the downloaded `.nii.gz` files (functional and anatomical data) and the Jupyter Notebook file (`Pycourse_Assignment_AD.ipynb`) in the same folder. This ensures the code can automatically locate the data files.

3. **Run the Notebook**  
   - Open the notebook a compatible environment (e.g. VS Code).  
   - Run each cell sequentially to reproduce the analysis and visualisations.

---

## Python Packages Used
The following Python packages are required for this project:
- **nilearn**: For neuroimaging data visualisation and processing.
- **nibabel**: To load and handle `.nii.gz` neuroimaging files.
- **matplotlib**: For creating plots and visualisations.
- **numpy**: For numerical operations and data manipulation.
- **os** and **glob**: To manage and automate file detection.

To install the required packages, run:
```bash
pip install nilearn nibabel matplotlib numpy
