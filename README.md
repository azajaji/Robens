# ROBENS: A Robust Ensemble System for Password Strength Classification

This repository contains the implementation of **ROBENS (ROBust ENSemble system for password strength)**, a machine learning framework for password strength classification. ROBENS combines Random Forest (RF) and Support Vector Machine (SVM) classifiers with ensemble strategies such as **bagging, boosting, and voting** to improve accuracy and robustness, especially under **small** and **imbalanced datasets**.

## Features
- Password strength classification into **weak, medium, strong**
- Integration of **ensemble learning** methods
- Data preprocessing and resampling (oversampling, undersampling)
- Performance evaluation using accuracy, precision, recall, F1-score, and error rate
- Jupyter Notebook implementation for reproducibility

## Repository Structure
- `Final_New_Data.ipynb` – Main Jupyter Notebook with full ROBENS implementation  
- `figures/` – Plots and visualizations (if applicable)  
- `README.md` – Project documentation (this file)  

## Dataset
The system is trained using the **Password Strength Classifier Dataset**:
- Derived from the **000webhost leak**  
- Labeled using the **Password Assessment and Recognition System (PARS)** from Georgia Tech  
- Available online: [Kaggle – Password Strength Classifier Dataset](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset)

**Dataset citation:**
```
B. Bansal, "Password Strength Classifier Dataset," 
Available online: https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset 
(accessed on 25 May 2022).
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/azajaji/Robens.git
   cd Robens
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook and run all cells:
   ```bash
   jupyter notebook Final_New_Data.ipynb
   ```

4. Modify dataset paths or parameters in the notebook as needed.

## Results
ROBENS achieves superior accuracy, precision, recall, and F1-scores compared to baseline models, demonstrating **robustness under both small and imbalanced dataset conditions**.

## Citation
If you use ROBENS in your research, please cite:

```
A. Alajaji, et al., 
"ROBENS: A Robust Ensemble System for Password Strength Classification Under Data Challenges," 
IEEE Access, 2025 (under review).
```


