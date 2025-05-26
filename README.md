# ElevateLabs-AI-ML-Task1

This project performs data analysis and preprocessing on the Titanic dataset to understand the factors that influenced passenger survival during the Titanic disaster.

## Dataset Description

The dataset contains information about passengers aboard the Titanic, including:
- Passenger demographics (age, gender, class)
- Ticket information
- Cabin details
- Survival status

## Project Structure

- `EL_Task1.ipynb` - Jupyter notebook containing the analysis
- `Titanic-Dataset.csv` - Original dataset
- `Titanic-Cleaned.csv` - Preprocessed dataset
- `requirements.txt` - Python package dependencies

## Setup Instructions

1. Clone this repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open `EL_Task1.ipynb` to view and run the analysis.

## Analysis Steps

The notebook performs the following steps:
1. Data loading and initial exploration
2. Handling missing values
3. Feature engineering and encoding
4. Data normalization
5. Outlier detection and treatment
6. Data visualization

## Dependencies

- pandas >= 1.5.0
- numpy >= 1.21.0
- seaborn >= 0.12.0
- matplotlib >= 3.5.0
- scikit-learn >= 1.0.0
- jupyter >= 1.0.0
