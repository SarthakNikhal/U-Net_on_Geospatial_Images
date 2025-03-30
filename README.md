# Satellite Image Segmentation using Deep Learning

#### Overview
This repository contains the implementation of a U-Net model for geospatial image segmentation. The model is designed to efficiently segment satellite or aerial imagery, making it useful for applications such as land cover classification, change detection, and feature extraction.
![image](https://github.com/user-attachments/assets/07ed9e9f-bead-418c-8c25-305b24edd701)


#### Features
- U-Net architecture for precise segmentation of geospatial images
- Preprocessing and augmentation techniques for remote sensing data
- Training and evaluation on real-world datasets
- Reproducible pipeline for experimentation

#### Steps
The project follows these steps:

1. Data Preparation:
    - Satellite images and corresponding masks (annotations) are loaded in HDF5 format.
    - Data is preprocessed, including resizing and normalization.
2. Model Development:
    - A U-Net model is implemented using TensorFlow/Keras. 
    - The model architecture is designed for image segmentation tasks.
3. Model Training:
    - The model is trained using the prepared dataset.
    - Training parameters, such as learning rate and batch size, are optimized.
4. Model Evaluation:
    - The trained model is evaluated on a separate test dataset.
    - Metrics like accuracy, precision and recall are used to assess performance.
5. Prediction:
    - New satellite images are fed to the trained model to generate segmentation masks.
    - The predicted masks highlight the identified objects/features in the images.

## Requirements

- Python 3.x
- TensorFlow 2.15
- Keras
- Rasterio
- Geopandas
- Contextily
- Segmentation Models
- h5py
- NumPy
- Pandas
- Matplotlib

You can install these using the following command:
`pip install segmentation_models rasterio geopandas contextily tensorflow==2.15`

## Tech Stack
![image](https://github.com/user-attachments/assets/8165d399-6dc9-481a-89bd-39e0842b145c)
![image](https://github.com/user-attachments/assets/d69d5e2d-40df-43e7-afb4-d85855a5098f)
![image](https://github.com/user-attachments/assets/ed828aa2-1659-4c32-bf24-6764a35c3719)
![image](https://github.com/user-attachments/assets/f84c96ff-cfda-468e-bb7c-5be7b49f5be3)
![image](https://github.com/user-attachments/assets/9f329e9a-0b9a-40b5-9c6f-f866644bbbcc)



Reference:
The project is inspired by the paper: Rapid Mapping of Landslides on SAR Data by Attention U-Net (https://www.mdpi.com/2072-4292/14/6/1449)
