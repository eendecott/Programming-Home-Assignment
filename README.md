# Programming for Psychologists - Home Assignment on Mental Imagery fMRI Data

### Liz Endecott

Date completed: December 5, 2025

Neurosynth link: https://neurosynth.org/analyses/terms/mental%20imagery/
---

This home assignment involved writing Python code in a Jupyter Notebook to visualize fMRI data. In this case, fMRI data related to mental imagery. Data is visualized first by using Nilearn to create 3 cuts of related brain regions, then by using Nibabel to create a histogram of the uniformity data distribution. 
---

### Table of Contents
**Jupyter notebook**: MRI_home_project.ipynb
**Anatomical data zip file**: anatomical.nii.gz 
**Uniformity data zip file**: mental imagery_uniformity-test_z_FDR_0.01.nii.gz

Both zip files need to be unzipped to access data. 
Ensure both files are in the same folder in your current working directory. 
---

**Python version:** 3.12.4

### Python packages used:
- `nilearn`
- `nibabel`
- `matplotlib`
- `glob`
- `pathlib`