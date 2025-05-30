# Prediction of Temporal Anomalies in ECG for Atrial Fibrillation Identification (AFI)

This repository contains a Jupyter Notebook and related datasets used to analyze patient metadata and extracted features from ECG (electrocardiogram) signals.

## Repository Contents

- **`main.ipynb`**  
  The main Jupyter notebook that includes:
  - Data loading and preprocessing
  - Exploratory data analysis (EDA)
  - Visualization of ECG features
  - (Optional) Machine learning or statistical modeling

- **`metadata_patients.xlsx`**  
  Excel file containing patient information such as age, gender, diagnosis, etc.

- **`ecg_features.csv`**  
  CSV file containing numerical features extracted from ECG signals (e.g., heart rate, intervals, amplitudes).

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **(Optional) Set up a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   If you have a `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```
   Otherwise, make sure you have the following libraries:
   - `pandas`
   - `numpy`
   - `matplotlib` or `seaborn`
   - `openpyxl` (to read `.xlsx`)
   - `scikit-learn` (if using ML)

4. **Launch the notebook**:
   ```bash
   jupyter notebook main.ipynb
   ```

## Project Purpose

This project aims to develop an arrhythmia prediction model based on ECG data to enable early identification of atrial fibrillation.
