# SimpleNet Model Implementation on MVTec AD Dataset

This repository contains the implementation of the SimpleNet model for anomaly detection and localization on the MVTec Anomaly Detection (MVTec AD) dataset. The main code runs as a Kaggle notebook, leveraging helper modules and the dataset provided here.

---

## Repository Structure

- `simplenet-module/`  
  Contains helper Python files such as `backbones.py`, `resnet.py`, `common.py`, `utils.py`, etc. These modules support the SimpleNet model training and evaluation.

- `mvtec-ad/`  
  The MVTec Anomaly Detection dataset folder. This dataset is used for training and testing the SimpleNet model.

- `SimpleNet_Training_Notebook.ipynb`  
  Kaggle notebook for training the SimpleNet model and evaluating results.

---

## How to Run

1. **Download or clone this repository** to your local machine or directly upload files to Kaggle.

2. **Upload the following to your Kaggle notebook environment as inputs:**

   - The entire `simplenet-module` folder (containing all helper modules).
   - The full `mvtec-ad` dataset folder.

3. **Open the notebook `simplenet_final.ipynb`** in Kaggle.

4. **Set the input paths in the notebook if needed:**  
   The notebook assumes the paths to `simplenet-module` and `mvtec-ad` folders in the Kaggle input directory.

5. **Run all notebook cells sequentially** to:  
   - Load the dataset  
   - Initialize and train the SimpleNet model  
   - Evaluate model performance  
---

## Notes

- The notebook uses PyTorch and other common Python libraries; Kaggle environment supports these by default.
- Make sure the dataset and module folder paths are correctly set in the notebook before running.
- GPU acceleration on Kaggle is recommended for faster training.

---
