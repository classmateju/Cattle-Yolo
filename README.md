## Model Configuration and Training

The `model_config/` directory contains the configuration files used for model development, including network architecture settings, training hyperparameters, input image size, optimization strategies, and other experimental parameters.

The `python_code/` directory provides the complete implementation of the proposed Cattle-YOLO framework, including:

- model training scripts;
- validation and evaluation scripts;
- inference scripts;
- data preprocessing and utility functions.

All experiments can be reproduced using the provided configuration files and source code.

---

## Training Logs and Performance Visualization

The `train_log/` directory contains the training records generated during model optimization.

The provided files include:

- training and validation loss curves;
- precision and recall variation curves;
- mAP performance curves;
- other evaluation results recorded during training.

These logs provide detailed information about model convergence and performance evolution during the training process.

---

## Environment Configuration

The `conda_environment/` directory provides the environment configuration required to reproduce the experiments.

Users can create the experimental environment using:

```bash
conda env create -f conda_environment/environment.yml
conda activate cattle-yolo


## Dataset

The dataset includes four cattle behavior categories:
- walking
- standing
- feeding
- lying

Dataset annotations and split files are provided in `dataset_aux/`.

Due to privacy restrictions, raw farm videos are not publicly released. Some datasets are temporarily unavailable because they are associated with ongoing academic research projects, including unpublished thesis-related work and institutional data management requirements. These restrictions are intended to protect data ownership and privacy.

The authors plan to make the restricted datasets publicly available after the completion of the related academic work and necessary institutional approval. In the meantime, annotation files, dataset split information, metadata, and processing scripts are provided to facilitate reproducibility.

## Data Availability Statement

The code, trained models, annotation files, and dataset processing scripts are available in this repository. Some raw image and video data are restricted due to privacy, ownership, and institutional requirements. Researchers interested in accessing restricted data may contact the corresponding author for further information, subject to applicable permissions.
