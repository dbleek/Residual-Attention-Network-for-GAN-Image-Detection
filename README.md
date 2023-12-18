# Residual-Attention-Network-for-GAN-Image-Detection

This is a repo for our project team's Deep Learning final project. It contains two Google Colab notebooks:

* In IrisSegentation.ipynb, we finetune a Mask-RCNN to detect irises given an image of a face and perform additional pre-processing to create our input dataset.

* GANDetection.ipynb, we implement a Residual Attention Network (RAN) for detecting if an image is real or GAN-generated, given an iris pair from the input image.

The model is a recreation of the one described in the 2022 paper "Robust Attentive Deep Neural Network for Exposing GAN-generated Faces," available [here](https://arxiv.org/abs/2109.02167). Our PyTorch RAN implementation is adapted from [this publicly available repo](https://github.com/tengshaofeng/ResidualAttentionNetwork-pytorch). 
