# SymptomSolver

A machine learning-based disease prediction system that analyzes user symptoms and predicts the most likely medical condition. The project leverages healthcare datasets and predictive modeling techniques to provide quick preliminary insights based on reported symptoms.

> Disclaimer: This project is intended for educational and research purposes only and should not be considered a substitute for professional medical advice.

## Features

- Symptom-based disease prediction
- Data preprocessing and cleaning
- Machine Learning classification model
- Disease prediction from user input symptoms
- Interactive prediction workflow
- Dataset-driven analysis
- Easy-to-understand output results

## Project Objectives

The primary goals of this project are:

- Analyze symptom-disease relationships
- Build a predictive healthcare model
- Improve understanding of medical datasets
- Demonstrate machine learning applications in healthcare
- Provide quick disease prediction based on symptoms

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook
- Matplotlib
- Seaborn

## Dataset

The project uses symptom and disease datasets containing:

- Symptoms
- Disease labels
- Medical condition mappings
- Training and testing data

Example symptoms:

- Fever
- Headache
- Nausea
- Fatigue
- Cough
- Chest Pain
- Dizziness

## Project Structure

```text
symptomSolver/
│
├── Datasets/
│   ├── Training.csv
│   └── description.csv
│   └── diets.csv
│   └── medications.csv 
│   └── precautions_df.csv
│   └── symptoms_df.csv
│   └── workout_df.csv
│
├── projectSymptom.ipynb
├── projectsymptom.py
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/1MdAnas1/symptomSolver.git
cd symptomSolver
```

Install required packages:

```bash
pip install -r requirements.txt
```

## Running the Project

### Using Python Script

```bash
python projectsymptom.py
```

### Using Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
projectSymptom.ipynb
```

and execute all cells.

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Symptom-Based Prediction
7. Result Interpretation


## Results

The model predicts possible diseases based on user-selected symptoms and demonstrates how machine learning can assist in preliminary healthcare analysis.

## Author

**Mohd Anas Siddique**

## License

This project is intended for educational and learning purposes.
