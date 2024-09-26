(#video-analysis)=
# Video-based analysis of animal behaviour

## Overview
This will be an introductory course on analysing animal behaviour from video data. The course will cover:

- Overview of animal tracking methods and terminology.
- **Pose estimation and tracking with [SLEAP](https://sleap.ai/)**. This includes hands-on practice with training a pose estimation model, evaluating its performance, and using it to predict pose tracks in new videos.
- **Analysing pose tracks with [movement](https://movement.neuroinformatics.dev/)**. This includes loading the predicted pose tracks in Python, filtering and smoothing them, computing kinematic variables, and visualising the results.
- **Extracting behavioural syllables with [keypoint-moseq](https://keypoint-moseq.readthedocs.io/en/latest/index.html)**.

:::{note}
Training and prediction with pose estimation models are
GPU-intensive tasks.
Since many students will not have access to a GPU on their own machine, 
we highly recommend that they also attend the follow-up course on 
[Running pose estimation on the SWC HPC system](./hpc-behaviour). 
This will cover how to run pose estimation at scale, using the GPUs of the SWC HPC cluster.
:::

## Instructors
* [Niko Sirmpilatze ](https://github.com/niksirbi)
* [Chang Huan Lo](https://github.com/lochhh)
* [Sofía Miñano](https://github.com/sfmig)

## Prerequisites

### Hardware Requirements

This is a hands-on course, so **please bring your own laptop and charger**. A mouse is recommended but not essential. A dedicated GPU is not required but will be helpful.

### General Software Requirements

:::{note}
If you are an incoming PhD student attending the full [General Software Skills for Systems Neuroscience](general-software-skills) course and have already installed the general software requirements on Day 1, you may skip this section.
:::

- An IDE for Python programming. We recommend one of the following:
  - [Visual Studio Code](https://code.visualstudio.com/) with the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  - [PyCharm](https://www.jetbrains.com/pycharm/)
  - [JupyterLab](https://jupyter.org/install)

- A working `conda` (or `mamba`) installation. If you don't have it, install via [Miniforge](https://github.com/conda-forge/miniforge).
- A working [Git](https://git-scm.com/) installation.

### Specific Software Requirements

:::{note}
Only proceed with this section after fulfilling the general software requirements above.
:::

You will need to pre-install two different `conda` environments for the practical exercises. Create them as follows:

1. [**SLEAP**](https://sleap.ai/): Use the [conda package method](https://sleap.ai/installation.html#conda-package) from the SLEAP installation guide. You may use either `conda` or `mamba` in the installation command. An NVIDIA GPU is not required for this course as you will only use the SLEAP GUI (launched using `sleap-label`).
2. [**Keypoint-MoSeq**](https://keypoint-moseq.readthedocs.io): Use the recommended [conda installation method](https://keypoint-moseq.readthedocs.io/en/latest/install.html#install-using-conda).

You should now have two new conda environments called `sleap` and `keypoint_moseq`. To view all your conda environments, run `conda env list`.

### Sample Data

Download the sample data for this course from [Dropbox](https://www.dropbox.com/scl/fo/ey7b6yrqax2olqyv1th7j/h?rlkey=u4wh2gxtbbn4g5o3s55zbx6pp&st=56698231&dl=0). Click "Download" to get the `behav-analysis-course.zip` archive, then unzip it.

Alternatively, if you are connected to the SWC network and have access to the SWC's `ceph` filesystem, the dataset is available at `/ceph/scratch/neuroinformatics-dropoff/behav-analysis-course`. 
Ensure you copy the data to a convenient location on your laptop. 
The instructions to mount `ceph` on your laptop can be found on the [SWC wiki](https://wiki.ucl.ac.uk/display/SSC/Storage%3A+Ceph).

:::{note}
If you encounter any issues with these steps, please contact [Niko Sirmpilatze](mailto:n.sirmpilatze@ucl.ac.uk?subject=SWC/GCNU%20Software%20Skills) in advance of the course.
:::

## Materials
- [GitHub repository](https://github.com/neuroinformatics-unit/course-behavioural-analysis)
- [Slides](https://neuroinformatics.dev/course-behavioural-analysis/#/title-slide)
- [Sample data](https://www.dropbox.com/scl/fo/ey7b6yrqax2olqyv1th7j/h?rlkey=u4wh2gxtbbn4g5o3s55zbx6pp&st=56698231&dl=0)

Useful links:
- [SLEAP](https://sleap.ai/)
- [DeepLabCut](https://www.mackenziemathislab.org/deeplabcut)
- [movement](https://movement.neuroinformatics.dev/)
- [keypoint-moseq](https://keypoint-moseq.readthedocs.io/en/latest/index.html)

Recommended readings:
- [Neuroscience Needs Behavior: Correcting a Reductionist Bias](http://dx.doi.org/10.1016/j.neuron.2016.12.041)
- [Quantifying behavior to understand the brain](https://www.nature.com/articles/s41593-020-00734-z)
- [Open-source tools for behavioral video analysis: Setup, methods, and best practices](https://elifesciences.org/articles/79305)
