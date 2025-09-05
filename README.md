
# Centralized and Federated Learning with Sparse Fine-Tuning & Communication and Client Drift Analysis


The repository contains independent Jupyter notebooks, each of which can be run separately. Some notebooks require input files in JSON format or previously saved pre-trained weights.<br>
The code explores centralized and federated training approaches for image classification on the CIFAR-100 dataset using the pre-trained DINO ViT-S/16 model. Communication and client drift in the federated approaches are also analyzed.


## Codebase Structure
The code is logically organized into three main sections: Data Exploration, Centralized Approach and Federated Approach.
<br>

### 1. Data Exploration 
This initial phase is dedicated to analyzing and understanding the dataset.

- **Data Exploration Notebook:** Examines class distribution, variability, and key features of the dataset.
<br>

### 2. Centralized Approach 
This section contains experiments conducted in a centralized environment.

- **Head-Only Training:** Training only the classifier (head) of the model.
- **Sparse Fine-Tuning:** Sparse fine-tuning the of the backbone, keeping the classifier frozen.
- **Additional Tests:** Extra tests and in-depth analysis on the centralized approach.
<br>

### 3. Federated Learning Approach 
The federated learning approach is implemented and evaluated through various tests and analyses.

- **Head-Only Training:** Federated training limited to the classifier only.
- **Sparse Fine-Tuning:** Federated training with sparse fine-tuning of the backbone.
- **Additional Tests:** Extra tests and in-depth analysis on the FL approach.
- **Communication Analysis:** Evaluation of communication costs + implementation of a reduced communication.
- **Client Drift Analysis:** Study of client drift (local model divergence) in i.i.d. and non-i.i.d. scenarios.

