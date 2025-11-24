# RecehIn: IDR Coin Classification using Deep Learning

This Notebook is a **Project-Based Learning (PBL)** designed to learn the practical application of **TensorFlow** and **Keras** for an Image Classification task. The specific goal is to build a model capable to accurately classifying different denomintaions of Indonesian Rupiah (IDR) coins.

## Key Components
* Data Acquisition: The dataset, sourced from my own dataset collection [IceKhoffi/idr-coins](https://huggingface.co/datasets/IceKhoffi/idr-coins), includes images and their corresponding COCO annotations.
* Data Pipeline: Data Pipeline created to load images, parse the COCO annotations, and perform necessary preparation (Image Preprocessing, Data Augmentation).
* Classification Task: Handles a multi-class classification problem with 4 classes (different coin denomintaions).

## Model Architectures Explored
1. Baseline CNN Model, custom sequential CNN built from scratch to serve as a foundational benchmark to understand how a simple, deep learning architecture performs on the coin classification problem.
2. Pre-Trained Model (Transfer Learning), Focus on leveraging the power of Transfer Learning. A highly effective strategy for small custom datasets, the use of MobileNetV2 and the base model is frozen.
