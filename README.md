Segmentation Transformer - Medical Image Segmentation with Neural Networks
This is an early-stage research project focusing on segmentation of tissue in medical images using lightweight transformers. This project aims to provide accurate and reliable segmentation, aiding in the diagnosis and monitoring of breast cancer.

## Data
Segmentation masks for the DUKE dataset are saved at : data/Duke

## Installation
Create a virtual environment and install the required packages:
Segmentation Transformer - Medical Image Segmentation with Neural Networks
This is an early-stage research project focusing on segmentation of tissue in medical images using lightweight transformers. This project aims to provide accurate and reliable segmentation, aiding in the diagnosis and monitoring of breast cancer.

## Data
Segmentation masks for the DUKE dataset are saved at : data/Duke

## Installation
Create a virtual environment and install the required packages:

## Get Started
### Prepare Data
- Navigate to mammoview/data/dataset_breast.py and create a new Dataset class based on BaseDataset.
- Go to mammoview/data/datamodule_breast.py and create a new DataModule class based on BaseDataModule.

### Training
- Optional: Pretrain the model using scripts/main_pretrain.py
- Train the model using scripts/main_train.py

```bash
python -m venv venv
source venv/bin/activate
pip install -e .
```

### Prediction
- For cross-fold prediction, use scripts/main_predict_kfold.py
- For ensemble prediction on an external dataset, use scripts/main_predict.py

Please note that this project is in its early research stage and is intended for use by for-profit companies. The project is separate from any previous projects and does not bear any relation to them.
