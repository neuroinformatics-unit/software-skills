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
Make sure to follow the [steps outlined here](https://github.com/neuroinformatics-unit/course-behavioural-analysis#prerequisites) which will guide you through
setting up your laptop, installing the required software, and downloading the sample data.

If you encounter issues with any of these steps please contact 
<a href="mailto:n.sirmpilatze@ucl.ac.uk?subject=SWC/GCNU Software Skills">Niko Sirmpilatze</a>
in advance of the course.

## Materials
- [GitHub repository](https://github.com/neuroinformatics-unit/course-behavioural-analysis)
- [Slides](https://neuroinformatics.dev/course-behavioural-analysis/#/title-slide)
- [Sample data](https://www.dropbox.com/scl/fo/ey7b6yrqax2olqyv1th7j/h?rlkey=u4wh2gxtbbn4g5o3s55zbx6pp&st=zolupk4i&dl=0)

Useful links:
- [SLEAP](https://sleap.ai/)
- [DeepLabCut](https://www.mackenziemathislab.org/deeplabcut)
- [movement](https://movement.neuroinformatics.dev/)
- [keypoint-moseq](https://keypoint-moseq.readthedocs.io/en/latest/index.html)

Recommended readings:
- [Neuroscience Needs Behavior: Correcting a Reductionist Bias](https://www.sciencedirect.com/science/article/pii/S0896627316310406?via%3Dihub)
- [Quantifying behavior to understand the brain](https://www.nature.com/articles/s41593-020-00734-z)
- [Open-source tools for behavioral video analysis: Setup, methods, and best practices](https://elifesciences.org/articles/79305)
