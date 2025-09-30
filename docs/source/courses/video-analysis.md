(#video-analysis)=
# Video-based analysis of animal behaviour

## Overview
This course introduces free, open-source tools for tracking animal motion from videos and extracting quantitative descriptions of behaviour from motion tracks.

We'll be going through the following chapters of the ['Animals in Motion' handbook](https://animals-in-motion.neuroinformatics.dev/latest/):

- [Chapter 1: Introduction](https://animals-in-motion.neuroinformatics.dev/latest/01-intro.html)
- [Chapter 3: Pose Estimation with SLEAP](https://animals-in-motion.neuroinformatics.dev/latest/03-sleap-tutorial.html). Hands-on practice with [SLEAP](https://sleap.ai/) to train a pose estimation model, evaluate its performance, and use it to predict poses on new video frames.
- [Chanpter 4: Analysing tracks with movement](https://animals-in-motion.neuroinformatics.dev/latest/04-movement-intro.html). Hands on practice with [movement](https://movement.neuroinformatics.dev/) to load predicted pose tracks in Python, clean them, compute kinematic variables, and visualise the results.

:::{note}
Training and prediction with pose estimation models are GPU-intensive tasks.
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

Please carefully read through the [prerequisites page of the 'Animals in Motion' handbook](https://animals-in-motion.neuroinformatics.dev/latest/prerequisites.html), listing  hardware, software, and data requirements.
**Make sure to set aside half an hour ahead of the course to install the necessary software and download the sample data.**

If you encounter any installation issues, please contact **Niko Sirmpilatze**.

:::{note}
If you are an incoming PhD student attending the full [General Software Skills for Systems Neuroscience](general-software-skills) course you will have likely already installed [general development tools](https://animals-in-motion.neuroinformatics.dev/latest/prerequisites.html#sec-install-devtools) so you may skip that section of the prerequisites.
:::


## Materials
- ['Animals in Motion' handbook](https://animals-in-motion.neuroinformatics.dev/latest/)
- [GitHub repository](https://github.com/neuroinformatics-unit/course-animals-in-motion)
