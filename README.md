# Bank Marketing ML Project

## Project Goal
Build a binary classification model to predict whether a bank client
will subscribe to a term deposit based on marketing campaign data.

## Dataset
The dataset contains client demographic and campaign-related features.
The target variable is `subscribed` (1 — subscribed, 0 — not subscribed).
The data is highly imbalanced.

## Tools
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Model
- Logistic Regression
- Class imbalance handled using `class_weight='balanced'`

## Results
- ROC-AUC: **0.70**
- Recall (target class): **0.67**

The model demonstrates a good ability to identify potential subscribers,
which is important in marketing scenarios where missing a positive client
is more costly than a false positive.

## Future Improvements
- Threshold tuning based on business cost
- Tree-based models (Random Forest, Gradient Boosting)
- Feature selection and model interpretability analysis

## How to Run

1. Clone or download this project.
2. Open a terminal and navigate to the project directory:
   ```bash
   cd path/to/Bank-Marketing-ML-Project
   ```
3. Create a virtual environment (recommended):
   ```bash
   python3 -m venv venv
   ```
4. Activate the virtual environment:
   - On macOS/Linux: `source venv/bin/activate`
   - On Windows: `venv\Scripts\activate`
5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
7. Open `bank_marketing_ml.ipynb` in your browser and run all cells sequentially.
