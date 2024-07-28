# Comparison-of-EfficientNet-with-traditional-CNN-architectures

This study is a comprehensive analysis of the EfficientNet architecture and its comparison with other famous Convolutional Neural Networks architectiectures. The comparison is evaluated over three different datasets: CIDAR-100, Oxford Flowers-102 and Oxford III-T Pets dataset.

- The **CIFAR-100** dataset consists of of 60,000 color images, each of size 32×32 pixels, divided into 100 classes with 600 images per class.
- The **Flowers-102** dataset consists of of 8,189 color images, each of size 224x224 pixels, divided into 102 classes with 40 - 258 images per class.
- The **Oxford-IIIT Pet** dataset consists of of 7,349 color images, each of size 224x224 pixels, divided into 38 classes with around 200 images per class.

The architectures taken into account are: AlexNet, ResNet-50, VGG-16, Inception-V3, EfficientNet-B1, EfficientNet-B3, EfficientNet-B5.

The set of codes present in this project shows the performance and computational efficiency of these architectures over the dataset previosuly mentioned. More specifically, each code does the following:

- **CIFAR100 Dataset.ipynb:** shows the Top-1 accuracy and F1-Score of the mentioned architectures over the CIFAR-100 dataset.
- **Flowers102 Dataset.ipynb:** shows the Top-1 accuracy and F1-Score of the mentioned architectures over the Oxford Flowers-102 dataset.
- **Oxford III pets Dataset.ipynb:** shows the Top-1 accuracy and F1-Score of the mentioned architectures over the Oxford Flowers-102 dataset.
- **Parameters.ipynb:** shows the paremeters and FLOPs calculation of each one of the architectures over an input RGB 224x224 image.
- **Graphs.ipynb:** shows important graphs, which data was taken from the other codes.
