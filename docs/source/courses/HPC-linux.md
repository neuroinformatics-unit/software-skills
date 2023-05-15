# Introduction to high-performance computing with Linux

## Overview
The aim of this one-day course is to introduce Linux and bash to novice users, providing the fundamental knowledge to 
effectively use the SWC/GNU High Performance Computing (HPC) system.

## Content
### Introduction to Linux & Bash

- Basic introduction to Linux/Unix
  - Why is Linux used so often in scientific computing?
- Directory structure
- Introduction to Bash
- Navigating file structure
    - `ls`, `pwd`, `cd`
- Getting help
  - `man`, `--help`
- Debugging errors
- Creating files
    - `touch`, `nano`/`vim`, redirect output (`>`, `>>`)
- Displaying/printing file contents
    - `echo`, `cat`
- Moving/renaming/deleting files
    - `mv`, `rm`, `cp`, `mkdir`
- Wildcards
- Pipes
- Bash scripts
- Concept of `$PATH`
- Customization
  - links, aliases, and `.bashrc` files
- Permissions
    - `chmod`, `rwx`, `sudo`
- Cautions
    - Deleting files is forever
    - Spaces in filenames
    - ...

### Introduction to HPC 

Introduction to the SWC HPC system:
* Overview of the SWC/GCNU HPC system
* SLURM job scheduler
* Data storage
* Interactive jobs
* Batch jobs
* Array jobs

#### Materials
- [Slides](../materials/Introduction_to_HPC.pdf)


### Applied HPC Use
Running pose estimation with [SLEAP](https://sleap.ai)

#### Materials
- [GitHub repository](https://github.com/neuroinformatics-unit/swc-hpc-pose-estimation) with example scripts
- [Presentation slides](https://neuroinformatics-unit.github.io/swc-hpc-pose-estimation)