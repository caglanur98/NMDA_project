# NMDA Project — fMRI & EEG SPM Exercises

This repository contains scripts developed during the Neural Methods and Data Analysis course (MCNB Master’s Program, Freie Universität Berlin).
The project follows the SPM12 manual exercises using example fMRI and EEG datasets to gain hands-on experience with preprocessing and analysis workflows.

Scripts Available
fMRI (SPM12)

Batch script — calls all subscripts; number of participants, runs, sessions, and data paths can be specified here.

Preprocessing

Realignment
1.1. Coregistration
1.2. Segmentation

Normalization (Functional)
2.1. Normalization (Structural) — optional

Smoothing

First-Level Analysis
4.1. First-level GLM — Specification
4.2. First-level GLM — Estimation

Second-Level Analysis
5.1. Second-level GLM — Contrasts
5.2. Second-level GLM — Inference Results
5.3. Second-level GLM — Rendering

EEG (SPM12)

Batch script — contains all preprocessing steps to run them together as part of a pipeline.

Steps before preprocessing

Convert .bdf file to .mat

Channel selection

Prepare montage

Prepare trial definitions for epoching

Preprocessing

Convert

Montage

Prepare

High-pass filter

Downsampling

Low-pass filter

Epoching

Artifact detection/rejection

Averaging

Data

Example datasets from the official SPM manual

fMRI dataset: [link or reference]

EEG dataset: [link or reference]
