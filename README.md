# Plant Seedlings Image Classification — Computer Vision Case Study

A computer vision notebook project exploring plant seedling image classification.

## Repository contents

- `Plant Seedlings Image Classification.ipynb`: exploratory notebook containing the modeling workflow.
- `Labels.csv`: label metadata used by the notebook.

## Purpose

This repository is included as an earlier computer vision learning and applied modeling case study. It should not be interpreted as a production inference service or an independently verified deployment.

## How to review

1. Open the Jupyter notebook in GitHub or a compatible notebook environment.
2. Review image preparation, modeling steps, and any evaluation outputs recorded in the notebook.
3. Check the notebook's data paths and package imports before attempting to execute it.
4. Obtain any image data required by the notebook through appropriately licensed sources. The presence of `Labels.csv` does not establish that the complete image dataset is included.

## Evaluation and reproducibility

Model accuracy, class-wise precision/recall, data-split methodology, and inference latency have **not been independently revalidated for this portfolio update**. Refer to the notebook for original exploratory results. Avoid comparing any notebook metric with production performance without a controlled test dataset.

For reproducible evaluation, future work should document:
- Image dataset provenance and licensing
- Train/validation/test split and leakage prevention
- Class distribution and confusion matrix
- Model architecture, preprocessing, and augmentation
- Dependency versions, random seeds, and a repeatable inference command

## Scope

This is a historical computer vision project. My more recent work on evidence-grounded AI systems is documented in the [CIVIX engineering portfolio](https://github.com/hupomene/civix-portfolio), whose proprietary implementation is maintained privately.
