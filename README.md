# Crop Classification Using Satellite Data

**Author:** Laxmiranjan Sahu  
**Role:** AI/ML Engineer (Tech2 Assignment for SPARC)  

## Overview
This repository contains a cloud-based machine learning pipeline designed to classify land-cover types in the **Mahanadi River Delta**. It leverages Sentinel-2 imagery and a Random Forest classifier to distinguish between sand, sparse vegetation, and dense crops.

## Tech Stack
* **Platform:** Google Earth Engine (GEE)
* **Language:** Python (`geemap`, `pandas`, `matplotlib`)
* **Algorithm:** Random Forest Classifier (50 Trees)
* **Spectral Features:** Sentinel-2 Bands (B2, B3, B4, B8, B11, B12) + NDVI

## Model Performance
* **Overall Accuracy:** 94.15%
* **Kappa Score:** 0.8967

## Repository Contents
* `Spark-AIML Engineer_Task.ipynb`: Complete source code and pipeline.
* `Crop_Classification_Using_Satellite_Data_Report.pdf`: Detailed methodology, confusion matrix, and visual results.
* `Crop_Classification_Output/`: Exported GeoTIFF maps for NDVI and final classification.
