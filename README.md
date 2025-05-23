# Eye Disease Classification from Slit-Lamp Images
This project uses deep learning to classify eye diseases from slit-lamp photography. Inspired by recent research in medical imaging, it aims to build an end-to-end pipeline for automated ocular diagnosis support.

The current implementation includes a multi-class image classification model using convolutional neural networks (CNNs) to differentiate between healthy and diseased eyes. Segmentation and GAN-based enhancements are in progress and will be added in future updates.

Note: Only a portion of the codebase is publicly available due to ongoing development and dataset licensing restrictions. The segmentation and GAN modules are not yet fully implemented.

Features
Classification of eye images into multiple diagnostic categories

CNN-based architecture trained on real-world slit-lamp data

Visualization tools such as confusion matrices and Grad-CAM

Inference-ready demo using Streamlit

Planned Features
Semantic segmentation of ocular structures

GAN-based synthetic data generation for improved model generalization

Datasets
This project uses slit-lamp images from the following sources:

SLID-E Dataset : "SLID-E: Slit Lamp Image Dataset for Epiphora - A Benchmark Resource for Automated Tear Overflow Analysis"

"Open-source automatic segmentation of ocular structures and biomarkers of microbial keratitis on slit-lamp photography images using deep learning"

TIFF images are labeled as diseased, while PNG images are labeled as healthy.

Live Demo
An interactive Streamlit app is included to demonstrate inference on new images. Model training was conducted locally with an RTX 4090 GPU.

Disclaimer
This project is for research and educational purposes only. It is not intended for clinical use.


