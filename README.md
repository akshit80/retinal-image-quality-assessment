# Robust Retinal Image Quality Assessment

## Problem
Poor-quality retinal images can negatively affect automated disease detection systems.
Before applying diagnostic models, it is important to assess whether a retinal image
is of sufficient quality for reliable analysis.

## Objective
This project studies retinal image quality assessment as a system-level problem rather
than proposing new architectures. The focus is on:
- Robustness across datasets
- Effect of preprocessing on quality prediction
- Treating quality labels as ordered categories
- Evaluating the impact of quality filtering on disease detection

## Datasets
- EyeQ dataset (Good / Usable / Reject)
- DRIMDB dataset (cross-dataset evaluation)
- EyePACS dataset (downstream diabetic retinopathy detection)

## Methodology (Planned)
- Use standard pretrained CNN models (e.g., ResNet, MobileNet)
- Perform controlled preprocessing ablation experiments
- Model quality labels as ordered categories
- Evaluate cross-dataset generalization
- Compare disease detection performance with and without quality filtering

## Evaluation Metrics
- Accuracy, Recall, AUC for quality assessment
- Disease detection metrics before and after quality filtering


