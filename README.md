# README

## Steps to Use This Repository

### Step 1: Create Environment
- Create a Python environment using the `requirements.txt` file.
  ```bash
  pip install -r requirements.txt
  ```

### Step 2: Extract 322 Features
- Use the `SW_2gr_Feature_extraction.ipynb` notebook to extract features.
- Alternatively, load features directly from the provided `.mat` files.

### Step 3: Model Training with 60/40 Split
- Train the model using the `SW_2gr_Main_4_6.ipynb` notebook for the 60/40 data split.

### Step 4: Model Training with 5-Fold Cross-Validation
- Train the model using the `SW_2gr_Main_5f.ipynb` notebook for 5-fold cross-validation.
