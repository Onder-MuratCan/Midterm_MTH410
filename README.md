# Data Mining for Cybersecurity

This project focuses on utilizing data mining techniques for cybersecurity purposes. The objective is to analyze network traffic data, specifically distinguishing between normal and attack traffic using machine learning models.

## Datasets

The project utilizes two datasets:

- `CTU13_Normal_Traffic.csv`: Dataset containing normal network traffic.
- `CTU13_Attack_Traffic.csv`: Dataset containing attack network traffic.

## Code Overview

The main script (`data_mining_cybersecurity.py`) performs the following tasks:

1. **Data Loading and Preprocessing:**
   - Loads the attack and normal traffic datasets.
   - Handles missing values by dropping rows with missing data.
   - Selects relevant features for analysis.

2. **Model Training and Evaluation:**
   - Splits the data into training and testing sets.
   - Utilizes logistic regression for classification.
   - Evaluates model performance using confusion matrix, classification report, and accuracy score.
   - Generates histograms and box plots to visualize feature distributions and their relationship with labels.
   - Calculates summary statistics and correlation matrix to understand data characteristics.

3. **Model Performance:**
   - Trains a logistic regression model and evaluates its performance on both training and test sets.
   - Displays training and test accuracies.

4. **Data Visualization:**
   - Utilizes pair plots to visualize relationships between features and labels.

## Getting Started

1. **Clone the Repository:**
git clone https://github.com/Onder-MuratCan/data-mining-cybersecurity.git


2. **Install Dependencies:**
pip install -r requirements.txt


3. **Run the Script:**
python data_mining_cybersecurity.py


## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Contribution

Contributions are welcome! Feel free to submit issues or pull requests.
