# Test-Time Adaptation For Image Classification

Authors: Leonardo Giammarella, Enrico Zanetti

This project focuses on implementing a test-time adaptation technique for image classification based on the MEMO (marginal entropy minimization with one test point) approach. The primary goal is to improve the robustness and accuracy of pre-trained convolutional neural networks (CNNs) when deployed in environments with data distributions that differ from the training set. This is achieved by leveraging test-time augmentations and entropy minimization to adapt the model to new data distributions on-the-fly.

Experiments to evaluate the performance of the proposed solution are carried out on *Imagenet-A* and *Imagenet-v2* (matched frequency one) datasets.

The file *TTA_image_classification.ipynb* is a self-contained Jupyter notebook with explanations, code and experiments run with results.

The methodology used in this project is illustrated in the diagram below:

![](architecture_diagram.png)
