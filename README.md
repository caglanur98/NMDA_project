# NMDA Project — fMRI & EEG SPM Exercises

This repository contains scripts developed during the Neural Methods and Data Analysis course (MCNB Master’s Program, Freie Universität Berlin).
The project follows the SPM12 manual exercises using example fMRI and EEG datasets to gain hands-on experience with preprocessing and analysis workflows.

Scripts Available

# fMRI (SPM12)

Batch script — calls all subscripts; number of participants, runs, sessions, and data paths can be specified here.

Preprocessing

1. Realignment

  1.1. Coregistration

  1.2. Segmentation

2. Normalization (Functional)

  2.1. Normalization (Structural) — optional

3. Smoothing

First-Level Analysis

4.1. First-level GLM — Specification
4.2. First-level GLM — Estimation

Second-Level Analysis

5.1. Second-level GLM — Contrasts
5.2. Second-level GLM — Inference Results
5.3. Second-level GLM — Rendering

# EEG (SPM12)

Batch script — contains all preprocessing steps to run them together as part of a pipeline.

Steps before preprocessing:

1. Convert .bdf file to .mat
2. Channel selection
3. Prepare montage
4. Prepare trial definitions for epoching

Preprocessing:

1. Convert
2. Montage
3. Prepare
4. High-pass filter
5. Downsampling
6. Low-pass filter
7. Epoching
8. Artifact detection/rejection
9. Averaging


Data:
Penny, W., Friston, K., Ashburner, J., Kiebel, S., & Nichols, T. (2011). Statistical Parametric Mapping: The Analysis of Functional Brain Images. Elsevier/Academic Press. Retrieved from https://www.fil.ion.ucl.ac.uk/spm/doc/manual.pdf
