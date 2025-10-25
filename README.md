# Applied Machine Learning - Titanic Survival Analysis

A machine learning project analyzing survival patterns from the Titanic disaster using Python, Pandas, and Matplotlib.

## Project Overview

This project explores the Titanic dataset to understand factors that influenced passenger survival rates. The analysis includes:

- Data preprocessing and cleaning
- Feature engineering
- Exploratory data analysis (EDA)
- Statistical correlations
- Data visualizations

## Features Analyzed

- **Pclass**: Passenger ticket class (1st, 2nd, 3rd)
- **Sex**: Gender of passenger
- **Age**: Age of passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare price

## Installation

1. Clone this repository:
```bash
git clone https://github.com/[your-username]/Applied-Machine-Learning.git
cd Applied-Machine-Learning
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Download the Titanic dataset and place `titanic.csv` in the project root directory.

## Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook AMLProject.ipynb
```

## Requirements

- Python 3.7+
- pandas
- matplotlib
- jupyter

See `requirements.txt` for specific versions.

## Data Source

The Titanic dataset is commonly available from:
- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- [Seaborn built-in datasets](https://github.com/mwaskom/seaborn-data)

## Project Structure

```
Applied-Machine-Learning/
├── AMLProject.ipynb    # Main analysis notebook
├── titanic.csv         # Dataset (not included in repo)
├── requirements.txt    # Python dependencies
├── .gitignore         # Git ignore file
└── README.md          # This file
```

## Results

The analysis reveals key insights about Titanic passenger survival rates, including correlations between survival and various passenger characteristics.

## License

This project is open source and available for educational purposes.
