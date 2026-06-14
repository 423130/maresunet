# MarusNet Reproduction and Cross-Dataset Evaluation

## Overview

This project reproduces and evaluates the MarusNet semantic segmentation framework on two benchmark remote sensing datasets: ISPRS Vaihingen and ISPRS Potsdam.

The objective was to study the model's ability to generalize across different aerial imagery datasets and evaluate its performance on land-cover classification tasks. The project involved dataset preparation, training, validation, performance analysis, and comparison of results using standard semantic segmentation metrics.

## My Contributions

* Adapted MarusNet for multiple remote sensing datasets
* Prepared and processed Vaihingen and Potsdam datasets
* Configured training and validation pipelines
* Evaluated model performance using segmentation metrics
* Compared obtained results with reported benchmark results
* Analyzed cross-dataset generalization behavior

## Datasets

### ISPRS Vaihingen

A benchmark dataset containing high-resolution aerial imagery with pixel-level annotations for semantic segmentation.

### ISPRS Potsdam

A large-scale remote sensing dataset used for land-cover classification and urban scene understanding.

## Evaluation Metrics

* Mean Intersection over Union (mIoU)
* F1 Score
* Overall Accuracy (OA)

### Vaihingen Results

| Metric           | Obtained Result |
| ---------------- | --------------- |
| mIoU             | 79.49%          |
| Mean F1          | 88.26%          |
| Overall Accuracy | 91.06%          |

### Potsdam Results

| Metric        | Obtained Result |
| ------------- | --------------- |
| Training mIoU | 85.6%           |
| Training F1   | 92.1%           |
| Training OA   | 91.5%           |

## Technologies Used

* Python
* PyTorch
* NumPy
* OpenCV
* Matplotlib
* Jupyter Notebook

## Learning Outcomes

This project provided hands-on experience with semantic segmentation, remote sensing datasets, model evaluation, and deep learning workflows in PyTorch. It also helped in understanding the challenges of transferring segmentation models across different datasets and environments.

## Acknowledgements

This work is based on the original MarusNet implementation. Credit for the model architecture belongs to the original authors.
