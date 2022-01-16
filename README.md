# ENet-ImageSemanticSegmentation-on-CamVid-dataset
This repository implements ENet (A Deep Neural Network Architecture for Real-Time Semantic) on CAMVID dataset. The paper of ENet could be found [here](https://arxiv.org/abs/1606.02147)<br>
Training notebook is supported at [training_notebook.ipynb](https://github.com/Uchiha-Hieu/ENet-ImageSemanticSegmentation-on-CamVid-dataset/blob/main/training_notebook.ipynb)

### 1. Training parameters
- learning rate : 0.0005
- batchsize : 10
- epochs : 30
- learning rate scheduler steps : 100
- learning rate scheduler ratio : 0.1
- weight decay: 2e-4

### 2. Training results
- val loss : 0.63
- val iou : 0.56
