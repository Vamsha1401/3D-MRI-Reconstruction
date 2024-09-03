# 3D-MRI-Reconstruction

## Project Description

The 3D-MRI-Reconstruction project aims to reconstruct and analyze 3D MRI images of brain tumors using deep learning techniques. This repository includes code for loading, preprocessing, and visualizing MRI data, as well as building and training a U-Net model for tumor segmentation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Results](#results)

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


## Results
![image](https://github.com/user-attachments/assets/86bb0fde-d3a1-47c3-afb3-563ecf134419)
![image](https://github.com/user-attachments/assets/5efe2a41-dc01-4a23-bc73-a48eaaeecc85)
![image](https://github.com/user-attachments/assets/f4ff09a7-e03c-469b-8da3-be74b93f1e2a)
![image](https://github.com/user-attachments/assets/575745b4-cc6f-49a5-bef8-cd2eb5ae039c)
![image](https://github.com/user-attachments/assets/b533220a-1020-4ae8-bd9c-a758e39282ff)
![image](https://github.com/user-attachments/assets/a4bfed67-b3e1-42d0-9e32-ad32d1a05b33)
![image](https://github.com/user-attachments/assets/7674ef8b-7c47-4a6a-adaa-7647887e7166)

**Predicted outputs of different regions of tumor**

![image](https://github.com/user-attachments/assets/d73ef654-45aa-4580-898e-d8a4bf345014)

**Comparison between Training and Validation Accuracy**

![image](https://github.com/user-attachments/assets/3763e0f2-c341-4430-ab70-5314b35bd5c9)

**Ground Truth and Predicted Class of Tumor**

![image](https://github.com/user-attachments/assets/a2156edd-d65c-433c-aeb7-51f23f49acc5)

**3D Reconstructed Tumor of Predicted**

![image](https://github.com/user-attachments/assets/87fe47de-dd0c-45d0-9b65-dc170d35502e)

**Visualization of 3D Reconstructed Tumor in MeshLab**








