# Brain Stroke X-Ray Segmentation

Automated segmentation of brain stroke regions from X-Ray/CT images using **Convolutional Neural Networks (CNNs)**. This project aims to assist clinicians in early stroke detection and accurate diagnosis by highlighting affected brain regions.

## Features

- **Segmentation Metrics**: Dice Coefficient, IoU Score, Precision, Recall, AUC
- **Training Management**: ModelCheckpoint, EarlyStopping, and custom logging callbacks
- **Resume Training**: Continue from last checkpoint or train from scratch
- **Visualizations**: Training curves for Loss, Dice, and IoU
- **Flexible Configuration**: Adjustable epochs, batch size, and data paths

## Installation

```bash
git clone https://github.com/yourusername/brain-stroke-xray-segmentation.git
cd brain-stroke-xray-segmentation
pip install -r requirements.txt
