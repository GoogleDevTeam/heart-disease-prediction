# Heart Disease Prediction

An educational machine-learning project that compares Logistic Regression and Random Forest models for binary heart-disease classification using clinical features.

> **Important:** This project is for educational purposes only. It is not a medical device and must not be used to diagnose, treat, or make healthcare decisions.

## Project overview

The notebook demonstrates a complete classification workflow:

- Loading and inspecting the dataset
- Checking missing values and class balance
- Exploring feature correlations
- Splitting data with stratification
- Standardizing input features
- Training Logistic Regression and Random Forest models
- Comparing accuracy and ROC AUC
- Reviewing a confusion matrix and classification report
- Plotting an ROC curve
- Examining Random Forest feature importance

## Dataset

The included educational sample contains 50 records, 13 input features, and a binary `target` column. Features include age, sex, chest-pain category, resting blood pressure, cholesterol, maximum heart rate, exercise-related measurements, and other encoded clinical attributes.

### Data notice

The included dataset is synthetic/fictional educational data. It does not represent real patients, does not contain real patient records, and must not be used for medical diagnosis, treatment, or clinical decision-making.

## Results

Using the current notebook configuration and a 20% stratified holdout:

| Model | Accuracy | ROC AUC |
| --- | ---: | ---: |
| Logistic Regression | 0.60 | 0.68 |
| Random Forest | 0.80 | 0.88 |

The test set contains only 10 records, so these results should be treated as illustrative. A larger, independently validated dataset would be required for meaningful evaluation.

## Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- joblib

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/GoogleDevTeam/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. Install the dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook heart_disease_prediction.ipynb
   ```

4. Run the cells from top to bottom.

## Files

- `heart_disease_prediction.ipynb` — the analysis and model workflow
- `heart.csv` — the included educational dataset
- `requirements.txt` — Python dependencies

## Future improvements

- Evaluate on a larger dataset
- Use cross-validation
- Tune model hyperparameters
- Compare additional models
- Analyze class imbalance
- Add reproducible pipelines and stronger validation

## Author

Albaraa Loay Mahroos  
Information Systems Student at Shaqra University