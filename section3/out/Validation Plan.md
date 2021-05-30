# What is the intended use of the product?

The intended use is to build an end-to-end AI system which features a machine learning algorithm that integrates into a clinical-grade viewer and automatically measures hippocampal volumes of new patients, as their studies are committed to the clinical imaging archive.

# Validation Plan

## Validation Dataset:

- Imaging modality
  - Cropped rectangular volumes where only the region around the hippocampus has been cut out from MRI scans of the full brain .

## **Ground Truth Acquisition Methodology:**

The silver standard from reading of 3-4 radiologists.

## **Algorithm Performance Standard:**
Jaccard and Dice similarity.
