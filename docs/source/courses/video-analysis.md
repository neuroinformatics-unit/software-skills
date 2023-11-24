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
GPU-intensive tasks.
Since many students will not have access to a GPU on their own machine, 
we highly recommend that they also attend the follow-up course on 
[Running pose estimation on the SWC HPC system](./hpc-behaviour). 
This will cover how to run pose estimation at scale, using the GPUs of the SWC HPC cluster.

## Prerequisites
Make sure to follow the [steps outlined here](https://github.com/neuroinformatics-unit/course-behavioural-analysis-2023#prerequisites) which will guide you through
setting up your laptop, installing the required software, and downloading the sample data.

If you encounter issues with any of these steps please contact 
<a href="mailto:n.sirmpilatze@ucl.ac.uk?subject=SWC/GCNU Software Skills">Niko Sirmpilatze</a>
in advance of the course.
You may also drop by our office hours at the SWC Library (5th floor) on **Friday Nov 24th, 13:30-16:00**.


## Materials
- [GitHub repository](https://github.com/neuroinformatics-unit/course-behavioural-analysis-2023)
- [Slides](https://neuroinformatics.dev/course-behavioural-analysis-2023/#/title-slide)
- [Sample data](https://www.dropbox.com/scl/fo/ey7b6yrqax2olqyv1th7j/h?rlkey=u4wh2gxtbbn4g5o3s55zbx6pp&dl=0) - link expires on 2023-12-22

Useful links:
- [miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [SLEAP](https://sleap.ai/)
- [DeepLabCut](https://www.mackenziemathislab.org/deeplabcut)
- [LightningPose](https://github.com/danbider/lightning-pose)
- [movement](https://movement.neuroinformatics.dev/)
- [keypoint-moseq](https://keypoint-moseq.readthedocs.io/en/latest/index.html)

Recommended readings:
- [Neuroscience Needs Behavior: Correcting a Reductionist Bias](https://www.sciencedirect.com/science/article/pii/S0896627316310406?via%3Dihub)
- [Quantifying behavior to understand the brain](https://www.nature.com/articles/s41593-020-00734-z)
- [Open-source tools for behavioral video analysis: Setup, methods, and best practices](https://elifesciences.org/articles/79305)
