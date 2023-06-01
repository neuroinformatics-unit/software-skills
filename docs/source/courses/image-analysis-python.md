# Image Analysis in Python

## Overview
This half-day course will introduce the use of Python packages to analyse and visualise image data common to neuroscience.

## Course Summary:

- **Interactive workflows in Python:**
    - IPython for efficient data exploration

- **Basic image analysis techniques:**
    - Utilizing NumPy, and scikit-image libraries
    - Visualization and exploration with napari

- **Processing large datasets effectively:**
    - Introduction to Dask for parallel computing
    - Demonstration using BrainSaw data

- **Tools for processing histology data:**
    - BrainGlobe tools for image registration and segmentation

:::{note}
If time allows, we will also look at using convolutional neural networks for tricky segmentation problems. 
:::
## In advance of the course
### Installing packages

Before attending the course, please 
[install conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) 
if you don't already have it installed, and then run the following to install all relevant packages:

```bash
conda create --name image-analysis-python python=3.10 nb_conda_kernels -y
conda activate image-analysis-python
git clone https://github.com/neuroinformatics-unit/image-analysis-python
cd image-analysis-python
pip install -r requirements.txt
```

### Download data
To speed things up on the day, you may wish to download the data in advance. To do this:
* Start jupyter lab (`jupyter lab`)
* Open up the first notebook (e.g. `notebooks/skimage_napari`)
* Set the conda environment (should be `image-analysis-python` based on the above commands)
* Run the first code cell (the one that says **Run the following cell to download the data in advance** above it!)
* Repeat for the other notebooks

:::{note}
The `dask_cellfinder` notebook has the largest sample data, so this is probably the best one to download in advance. 
Even on a fast (e.g. UCL) network, it may take ~1hr to download.
:::

## Links
### Course materials
* [Notebooks](https://github.com/neuroinformatics-unit/image-analysis-python)
* [Working interactively with Python slides](https://neuroinformatics-unit.github.io/image-analysis-python/)
* [Sample data](https://gin.g-node.org/neuroinformatics/image-analysis-courses)
* [BrainGlobe sample data](https://gin.g-node.org/BrainGlobe/demo-materials)

### Useful links
* [miniconda](https://docs.conda.io/en/latest/miniconda.html)
* [scikit-image](https://scikit-image.org/)
* [napari](https://napari.org)
* [dask](https://www.dask.org/)
* [BrainGlobe](https://brainglobe.info/)
* [keras](https://keras.io/)
* [itk-elastix](https://github.com/InsightSoftwareConsortium/ITKElastix)
* [2018 Data Science Bowl](https://www.kaggle.com/c/data-science-bowl-2018)