# Video-based analysis of animal behaviour

## Overview
This will be an introductory course on analysing animal behaviour from video data. The course will cover:

- Motivation
- Overview of animal tracking methods and terminology
- Pose estimation and tracking
  - Overview of existing tools
  - Labeling animal body parts
  - Training a model
  - Predicting poses
  - Evaluating performance
- Analysing pose tracks with Python
  - Loading and saving data
  - Filtering/smoothing
  - Visualising tracks
  - Time spent in regions of interest

Training and prediction with pose estimation models are
GPU-intensive tasks. Since many students will not have access to a GPU on their own machine, 
we highly recommend that they also attend the follow-up course on 
[Running pose estimation on the SWC HPC system](./hpc-behaviour). 
This will cover how to run pose estimation at scale, using the GPUs of the SWC HPC cluster.

## Prerequisites
Students should bring their own laptop with Python installed. If you require any assistance, please contact
<a href="mailto:adam.tyson@ucl.ac.uk?subject=SWC/GCNU Software Skills">Adam Tyson</a> in advance of the course.

To get the most out of the course, students should install [SLEAP](https://sleap.ai/) on their laptops. 
This will allow them to follow along
such tasks as labelling animal body parts on a video and preparing the training data. 
We recommend following the [official installation instructions](https://sleap.ai/installation.html),
which may defer depending on your operating system.
If your machine doesn't include a GPU, you may ignore the [GPU support](https://sleap.ai/installation.html#gpu-support) section of the installation instructions.
If you encounter problems with installing SLEAP, contact
<a href="mailto:n.sirmpilatze@ucl.ac.uk?subject=SWC/GCNU Software Skills">Niko Sirmpilatze</a> in advance of the course.

Optionally, the students are welcome to bring along any animal videos they would like to analyse.
This could simply be a video of your pet, or of the London fox you spotted in your garden last night.

## Materials
- [Recommended paper to read](https://www.nature.com/articles/s41593-020-00734-z)
- Slides (TBC)
- GitHub repository (TBC)