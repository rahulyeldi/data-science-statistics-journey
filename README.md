# Data Science & Statistics Journey

Welcome to your comprehensive learning resource for data science and statistics! This repository is designed as a hands-on journey through fundamental statistical concepts using real-world datasets.

## Project Overview

This project serves as an interactive learning environment where you'll explore statistical concepts using the famous Titanic dataset. You'll progress from basic statistical understanding to advanced descriptive analysis techniques.

## Project Structure

```
data-science-statistics-journey/
├── dataset/
│   └── Titanic-Dataset.csv          # Titanic passenger data for analysis
├── lab/
│   ├── Introduction.ipynb          # Statistical concepts & data basics
│   └── Descriptive_Statistics.ipynb # Advanced statistical analysis
├── requirements.txt                # Python dependencies
└── README.md                       # This file
```

## Getting Started

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook/Lab
- Virtual environment (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd data-science-statistics-journey
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows: myenv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Lab**
   ```bash
   jupyter lab
   ```

## About the Dataset

**Titanic Dataset**: A comprehensive collection of passenger information from the Titanic disaster, perfect for learning statistical analysis.

### Key Features:
- **891 passengers** with 12 attributes
- **Survival information** (target variable)
- **Demographic data**: Age, sex, passenger class
- **Travel details**: Fare, port of embarkation
- **Family information**: Siblings, spouses, parents, children

### Dataset Columns:
| Column | Description | Type |
|--------|-------------|------|
| `Survived` | Survival (0 = No, 1 = Yes) | Target |
| `Pclass` | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) | Ordinal |
| `Name` | Passenger name | Nominal |
| `Sex` | Gender | Nominal |
| `Age` | Age in years | Continuous |
| `SibSp` | # siblings/spouses aboard | Discrete |
| `Parch` | # parents/children aboard | Discrete |
| `Ticket` | Ticket number | Nominal |
| `Fare` | Passenger fare | Continuous |
| `Cabin` | Cabin number | Nominal |
| `Embarked` | Port of embarkation (C, Q, S) | Nominal |


## Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** | Primary programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computing |
| **Matplotlib** | Basic plotting and visualization |
| **Seaborn** | Statistical data visualization |
| **SciPy** | Scientific computing and statistics |
| **Jupyter** | Interactive development environment |


## Learning Outcomes

After completing this journey, you'll be able to:
- Understand and apply fundamental statistical concepts
- Perform comprehensive exploratory data analysis
- Create insightful data visualizations
- Calculate and interpret key statistical measures
- Identify patterns and anomalies in datasets
- Present findings through clear visualizations and interpretations

## Contributing

This is a learning-focused repository. Feel free to:
- Add new analysis notebooks
- Improve existing visualizations
- Add explanatory comments
- Share insights and findings

## Additional Resources

- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic) - Original dataset source
- [Pandas Documentation](https://pandas.pydata.org/docs/) - For data manipulation
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html) - For visualization
- [Statistics Fundamentals](https://www.khanacademy.org/math/statistics-probability) - Khan Academy

## Notes

- The dataset contains missing values which is intentional for learning data cleaning
- All analysis is performed using the Titanic dataset for consistency
- Code is written with educational clarity in mind

---

Dive into the notebooks and start your data science journey today!
