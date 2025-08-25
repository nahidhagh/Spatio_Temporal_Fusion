/STDFM_CNN.ipynb         # Main notebook for training and running STDFM-CNN
/MACHINE LEARNING CODE/     # All machine learning models; first part of each script for training, second part for testing
    /Region_A/          section 1 # Scripts for training models using Region A data
    /Region_B/        section 1    # Scripts for applying models on Region B data
/DATA/                   # Preprocessed MODIS and Landsat LST datasets
README.md



How to Use ML Models
Train the model with Region A data (ML_Models/Region_A).

Apply the trained model to Region B data (ML_Models/Region_B) to evaluate generalization.

STDFM-CNN
Python implementation for fusion of MODIS and Landsat LST and predicting Landsat LST.

Training and execution scripts are in STDFM_CNN.ipynb.

Requirements
Python 3.8+

Libraries: numpy, pandas, tensorflow, keras, rasterio, matplotlib, scikit-learn

Data
MODIS and Landsat LST datasets are divided into Region A and Region B.

Preprocessed datasets are in /DATA.

All data follow FAIR principles for reproducibility.
