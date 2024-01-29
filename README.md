# BraTs2020 MRI Scan Segmentation Project

## Overview

Welcome to the BraTs2020 MRI Scan Segmentation project! This project focuses on segmenting brain tumors in 3D MRI scans using the 3D U-Net architecture. Additionally, the project includes a feature to generate a GIF showcasing the segmentation process, followed by calculating the volume of the tumor in cubic centimeters.

## Table of Contents

- [Introduction](#brats2020-mri-scan-segmentation-project)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Prerequisites

Before running the project, make sure you have the following dependencies installed:

- Python 3.7
- Required Python packages (you can install them using `pip install -r requirements.txt`)
- TensorFlow (or any other backend supported by Keras)

## Installation

1. Clone the repository:

   ```bash
   [git clone https://github.com/your-username/brats2020-mri-segmentation.git](https://github.com/AlbanXhepi21/MRI-Scan-Segmentation-.git)
   cd brats2020-mri-segmentation] ```

2. Install the required dependencies:
   ``bash
      pip install -r requirements.txt ```
## Usage
1. Download the BraTs2020 dataset from Kaggle.
2. Prepare your BraTs2020 dataset and organize it appropriately by running this script:
    ```bash
      python brats2020_get_ready.py ```
3. Train the model and make the segmentation by running this script:
   ```bash
      python train_brats2020_V5.0.py ```
   
4.Once the segmentation is complete, you can run this script to generate the GIF of the 3d segmentation:
   ```bash
      python generateGif.py ```
5. After generating the GIF, calculate the tumor volume:
   ```bash
      python find_volume.py ```

   
