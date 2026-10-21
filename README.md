```
## Model Configuration and Training
https://github.com/classmateju/Cattle-Yolo#model-configuration-and-training
The `model_config/` directory contains the configuration files used for model development, including network architecture settings, training hyperparameters, input image size, optimization strategies, and other experimental parameters.
The `python_code/` directory provides the complete implementation of the proposed Cattle-YOLO framework, including:
- model training scripts;
- validation and evaluation scripts;
- inference scripts;
- data preprocessing and utility functions.
All experiments can be reproduced using the provided configuration files and source code.

## Training Logs and Performance Visualization
https://github.com/classmateju/Cattle-Yolo#training-logs-and-performance-visualization
The `train_log/` directory contains the training records generated during model optimization.
The provided files include:
- training and validation loss curves;
- precision and recall variation curves;
- mAP performance curves;
- other evaluation results recorded during training.
These logs provide detailed information about model convergence and performance evolution during the training process.

## Environment Configuration
https://github.com/classmateju/Cattle-Yolo#environment-configuration
The `conda_environment/` directory provides the environment configuration required to reproduce the experiments.
Users can create the experimental environment using:
```bash
conda env create -f conda_environment/environment.yml
conda activate cattle-yolo
```

## Dataset

The dataset includes four cattle behavior categories:

- walking
- standing
- feeding
- lying

Dataset annotations and split files are provided in `dataset_aux/`.

The self-collected farm raw images and videos contain sensitive operational information of the farm and cannot be publicly released, as access is restricted by institutional privacy regulations and binding farm site access agreements. All minimal data required to reproduce the findings, including annotation files, animal ID indices, dataset split information, metadata, and preprocessing scripts, are publicly provided here.

The public Kaggle cattle behavior dataset adopted in this study is available at [https://www.kaggle.com/datasets/lucyfirst/beef-cattle-behavior-data-set](https://www.kaggle.com/datasets/lucyfirst/beef-cattle-behavior-data-set) and is released under the CC0 public domain license, permitting unrestricted access and secondary analysis.

## Data Availability Statement

The code, trained models, annotation files, and dataset processing scripts are available in this repository. The self-collected farm raw images and videos contain sensitive operational information of the farm and cannot be publicly released, as access is restricted by institutional privacy regulations and binding farm site access agreements. All minimal data required to reproduce the findings, including annotation files, animal ID indices, dataset split information, metadata, and preprocessing scripts, are publicly provided here. The public Kaggle cattle behavior dataset adopted in this study is available at [https://www.kaggle.com/datasets/lucyfirst/beef-cattle-behavior-data-set](https://www.kaggle.com/datasets/lucyfirst/beef-cattle-behavior-data-set) and is released under the CC0 public domain license, permitting unrestricted access and secondary analysis. Additional experimental resources are archived in Zenodo: [https://doi.org/10.5281/zenodo.21776172](https://doi.org/10.5281/zenodo.21776172)
