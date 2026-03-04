# AI-Based App Popularity Prediction (Random Forest)

## Overview
This repository contains the code and resources for an **AI-Based App Popularity Prediction** project developed during an AI/ML workshop at **Nanyang Technological University (NTU), Singapore**. The project uses a **Random Forest model** trained on a ~**9,000-row dataset** of app metadata to predict app popularity and identify which factors influence adoption the most.

---

## Project Highlights
- Predicts whether an application is **Popular** based on app attributes  
- Uses **Random Forest** with feature preprocessing and encoding  
- Takes user inputs (rating, reviews, installs, price, size, category, etc.) and outputs a predicted popularity class

---

## Repository Contents
- **AI_Based_App_Popularity_Prediction.ipynb**  
  End-to-end notebook for data preprocessing, model training, evaluation, and prediction.

---

## Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **Environment:** Google Colab / Jupyter Notebook  

---

## Getting Started (Google Colab)

1. Open the notebook in **Google Colab** (upload it or open from GitHub).
2. If your dataset is stored in Google Drive, mount Drive:
```python
from google.colab import drive
drive.mount('/content/drive')

3. Update the dataset path in the notebook if required.

4. Run the notebook cells in order:
   - Data loading + preprocessing
   - Model training + evaluation
   - Prediction on user inputs


## Output Example

Predicted Popularity: Popular

Meaning: Based on the given input attributes, the model predicts the app falls under the Popular category.

