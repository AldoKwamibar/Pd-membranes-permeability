# Palladium alloy Membranes Permeability Prediction with CatBoost & Virtual Screening

This repository contains Python notebooks (`.ipynb`) and datasets related to hydrogen permeability prediction in palladium-based alloy membranes.

All datasets are provided in flat file formats (CSV/XLSX), compatible with Microsoft Excel (tested on Version 2508).

---

## 🚀 Project Structure

PhD. Project organization

## Dataset (Folder)
     ___Lattice parameters.xlsx ----> Vegard's law
    |
    |___Palladium_Alloy_Membranes dataset_QSPR_ML.csv ----> Pd alloy dataset for modelling
    |
    |___oliynyk_extended_std_unit.csv ----> Property dataset for CBFV

## Notebooks (Folder)
     ___Palladium_Membrane_ML_Preprocessing.ipynb
    |
    |___Palladium_Membrane_ML_EDA.ipynb
    |
    |___Palladium_Membrane_ML_Data_Splitting.ipynb
    |
    |___Palladium_Membrane_ML_Featurization.ipynb
    |
    |___Palladium_Membrane_ML_Modelling_Without_Feature_Selection.ipynb
    |
    |___Palladium_Membrane_ML_Modelling_With_Feature_Selection.ipynb
    |
    |___PdCuM_Memebrane_Virtual_Screening.ipynb
    |
    |___Palladium_Membrane_ML_Modelling_Figure_support.ipynb


> **Note:** Some notebooks are larger than 25 MB or contain interactive widgets. For best performance, download them locally or open directly in **Google Colab**.

---

## 📚 Notebook Pipeline (Recommended Reading Order)

1. **Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Train/Validation/Test Splits**
4. **Feature Engineering (Featurization)**
5. **Modeling without Feature Selection**
6. **Modeling with Feature Selection (SHAP/RFE)**
7. **Pd–Cu–M Virtual Screening**
8. **Figures and Statistical Validation**

---

## ✅ Requirements

- Python 3.8+
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- tqdm  
- CatBoost  
- SHAP  
- Matminer  
- Pymatgen  
- Pymatviz  
- wordcloud  
- (and other standard scientific Python packages)

It is recommended to use a virtual environment or Conda environment to ensure package compatibility.

---

## 📩 Contact

For questions or collaboration inquiries, feel free to open an issue or contact the authors.
Email: kolor.k.aa@m.titech.ac.jp

---
