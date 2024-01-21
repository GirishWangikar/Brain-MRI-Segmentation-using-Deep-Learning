# Brain-MRI-Segmentation-using-Deep-Learning

This repository contains code and documentation for a project exploring the association between shape features extracted from brain MRI scans and genomic subtypes of lower-grade gliomas. The goal is to develop imaging-based biomarkers that can serve as non-invasive surrogates for characterizing tumor molecular profiles.

Repository Contents
feature_extraction.ipynb: Jupyter notebook containing the code for MRI preprocessing, tumor segmentation using a U-Net model, and extraction of shape features like bounding ellipsoid volume ratio, margin fluctuation, and angular standard deviation.

Methodology
The key steps involved in this project are:

Dataset: 110 patients with preoperative brain MRI (FLAIR sequence) and genomic data from TCGA-LGG.
Preprocessing: Standardizing MRI sizes, skull stripping, contrast normalization.
Segmentation: U-Net model trained on manual segmentations to output automated tumor masks.
Feature Extraction: Computation of shape descriptors like BEVR, margin fluctuation, ASD from predicted masks.
Analysis: Statistical tests relating imaging features to genomic subtypes.

Key Results
Imaging features like BEVR showed significant associations with RNASeq subtypes.
Margin fluctuation differed substantially across DNA methylation clusters.
Findings demonstrate feasibility of non-invasive imaging surrogates for glioma genomics.
