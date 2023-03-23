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

- Introduction to HPC
- Why use vs. local machine
- Advantages/disadvantages
- Overview of the SWC/GCNU HPC system
- SLURM job scheduler
- How to login
- Understanding the archiecture of thesystem
- Storage mounts
- `sinfo`, `squeue`
- Interactive jobs
- Modules
- Batch jobs
- Array jobs
- How-tos
    - Using modules
    - Using CUDA
    - Installing your own software (conda, etc.)
- Fair use

### Applied HPC Use
- TBC, but may include
  - Pose estimation
  - BrainSaw atlas registration
  - Running custom scripts
