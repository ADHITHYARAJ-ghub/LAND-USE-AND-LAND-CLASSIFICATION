A benchmark comparision of Simple CNN, ResNet50 and EfficientNet for image classification
Land Cover Classification using CNN Architectures
This project compares three deep learning models — Simple CNN, ResNet-50, and EfficientNet — for classifying land use and land cover types from satellite images in the EuroSAT dataset (Sentinel-2 imagery).

Objective
To identify the most effective CNN architecture for accurate terrain type classification across 10 land cover classes including forest, river, residential, and farmland.
Models Used
Simple CNN: Lightweight baseline model for fast training

ResNet-50: Deep residual network with skip connections

EfficientNet-B0: Scalable, high-performance model with compound scaling
Dataset
EuroSAT: 27,000+ geo-referenced images

Input size: 64×64 resized to 224×224 for training

Classes: Agricultural, Forest, Residential, River, etc.
Preprocessing
Band selection (RGB + NIR)

Normalization

Image resizing

Data augmentation (flipping, rotation, scaling)
Results
Model	Accuracy
EfficientNet	97.5%
Simple CNN	94.0%
ResNet-50	89.0%
Applications
Urban development planning

Environmental monitoring

Agricultural analysis

Disaster response mapping
