# Retinal Vessel Segmentation

## Overview
Implementation of a deep learning pipeline for automatic retinal vessel segmentation from fundus images using a UNet-based architecture.

The project focuses on preserving vascular topology and extracting clinically relevant biomarkers.

Developed for the course:  
Medical Image Processing  
Prof. Filippo Molinari  
Prof.ssa Kristen Mariko Meiburger  
Academic Year 2025/2026  


---

## Data

Main file `Script` include:

- `training_script.ipynb`  # model training pipeline  
- `training_params.json`  # training configuration  
- `testing_script.ipynb`  # evaluation and inference   
- `best_model.pt`  # trained model weights

---

## Method

- Fundus image preprocessing (patching, normalization)  
- UNet-based CNN for segmentation  
- Hybrid loss function (BCE + Dice + SRL)  
- Threshold optimization for class imbalance  
- Morphological post-processing for topology refinement  

---

## Key Features

- Automatic retinal vessel segmentation  
- Topology-aware optimization (clDice, SRL)  
- Preservation of thin vessel structures  
- Extraction of vascular biomarkers  

---

## Results

- Robust segmentation of retinal vasculature  
- Improved connectivity and reduced fragmentation  
- Good balance between accuracy and topology preservation  
- Performance validated on test data  

---

## Notes

Project focused on deep learning for medical image segmentation with emphasis on topology preservation and clinical relevance.
