
# Titanic Data Analysis

## Project Overview
This project focuses on analyzing the Titanic passenger dataset using Python. The goal is to clean and preprocess the data, perform exploratory data analysis (EDA), engineer new features, and visualize passenger distributions and patterns.

## Objectives
- Understand the structure and characteristics of the Titanic dataset.
- Handle missing values and clean the data.
- Perform feature engineering to extract meaningful information.
- Analyze passenger demographics, ticket details, fares, and family relationships.
- Visualize patterns and distributions using Python libraries.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Exploration
- Display the first and last records.
- Inspect dataset information and data types.
- Identify duplicate records.
- Explore unique values and statistical summaries.

### 2. Data Cleaning
- Handle missing values in Age, Fare, and Embarked.
- Use mean imputation for Age and Fare.
- Use mode imputation for Embarked.
- Remove columns containing missing values where applicable.
- Rename and format columns for better readability.

### 3. Feature Engineering
Created new features to improve the analysis:

- **L_name:** Extracted passenger surname.
- **F_name:** Extracted passenger name information.
- **Title:** Extracted titles such as Mr, Mrs, Miss, and others.
- **fam_cnt:** Combined sibling/spouse and parent/child counts.
- **no_of_psgs:** Calculated the number of passengers sharing a ticket.
- **Companion Type:** Categorized passengers as Solo, Friends, or Family.
- **Age_category:** Categorized passengers into age groups.
- **Social_status:** Grouped passenger titles into social categories.

### 4. Data Analysis
- Analyzed passenger distribution by gender.
- Examined passenger distribution across ticket classes.
- Studied age categories and gender distribution.
- Analyzed passenger fares by gender and age category.
- Examined ticket-based passenger counts.
- Explored embarkation locations and passenger characteristics.

### 5. Data Visualization
Created visualizations using Matplotlib and Seaborn:

- Count plots
- Pie charts
- Bar plots
- Gender-based comparisons
- Age-category distributions
- Fare analysis

## Key Insights
- Male passengers outnumbered female passengers in the dataset.
- Third-class passengers represented the largest passenger group.
- Adult passengers represented a major portion of the passenger population.
- Female passengers had a higher average fare in the analyzed data.
- Total fare distribution differed between male and female passengers.
- Passenger characteristics varied across age categories and ticket groups.

## Project Files
- `Titanic.ipynb` – Jupyter Notebook containing data cleaning, feature engineering, exploratory data analysis, and visualizations.
- `titanic.csv` – Dataset used for analysis.

## How to Run the Project

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook using Jupyter Notebook.
4. Ensure `titanic.csv` is in the same directory as the notebook.
5. Run the notebook cells sequentially.

### Install Dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

## Conclusion
This project helped me gain practical experience in data cleaning, data preprocessing, feature engineering, exploratory data analysis, and data visualization using Python. It strengthened my understanding of how raw data can be transformed into meaningful insights.

---

**Author:** Shaik Yasar Malik
</markdown>

