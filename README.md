# 3D-MRI-Reconstruction

## Project Description

The 3D-MRI-Reconstruction project aims to reconstruct and analyze 3D MRI images of brain tumors using deep learning techniques. This repository includes code for loading, preprocessing, and visualizing MRI data, as well as building and training a U-Net model for tumor segmentation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Installation

To set up the environment for this project, you need to install the required packages. You can use `pip` to install them. Here’s a sample command to install the necessary dependencies:

```sh
pip install numpy pandas matplotlib seaborn scikit-image nibabel nilearn tensorflow
```

### Usage

1. **Clone the repository:**
```sh
git clone https://github.com/yourusername/3D-MRI-Reconstruction.git
cd 3D-MRI-Reconstruction
```
2. **Prepare your MRI dataset in the following structure:**
```sh
MICCAI_BraTS2020_TrainingData/
├── BraTS20_Training_001/
│   ├── BraTS20_Training_001_flair.nii
│   ├── BraTS20_Training_001_t1.nii
│   ├── BraTS20_Training_001_t1ce.nii
│   ├── BraTS20_Training_001_t2.nii
│   └── BraTS20_Training_001_seg.nii
```
3. **Run the script to visualize MRI slices and train the model:**
```sh
python your_script_name.py
```

## Technologies Used

- **Python**: The main programming language for this project.
- **TensorFlow**: For building and training the U-Net model.
- **Numpy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-Image**: For image processing tasks.
- **Nilearn & Nibabel**: For handling neuroimaging data.
