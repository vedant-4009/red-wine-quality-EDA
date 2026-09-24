# 🍷 Red Wine Quality — Exploratory Data Analysis

An Exploratory Data Analysis (EDA) project that analyzes the chemical properties of red wine and investigates their relationships with wine quality using Python.

## 📌 Project Overview

This project performs Exploratory Data Analysis on a Red Wine Quality dataset containing physicochemical properties of red wines along with their quality ratings.

The main goal is to explore the dataset, identify patterns and relationships, understand feature distributions, detect potential outliers, and determine which chemical characteristics have stronger statistical associations with wine quality.

## 🎯 Objectives

* Understand the structure and characteristics of the dataset
* Perform data quality checks
* Generate descriptive statistical summaries
* Analyze distributions of numerical features
* Detect potential outliers
* Study relationships between chemical properties
* Analyze the relationship between wine characteristics and quality
* Identify features that have stronger correlations with wine quality
* Present findings through clear visualizations

## 📊 Dataset

The dataset contains **1,143 wine observations** and **13 columns**, including an identifier column.

After removing the `Id` column, 12 analytical features are used for the EDA.

### Features

| Feature                | Description                     |
| ---------------------- | ------------------------------- |
| `fixed acidity`        | Fixed acids present in the wine |
| `volatile acidity`     | Volatile acidity of the wine    |
| `citric acid`          | Citric acid content             |
| `residual sugar`       | Amount of residual sugar        |
| `chlorides`            | Chloride concentration          |
| `free sulfur dioxide`  | Free sulfur dioxide level       |
| `total sulfur dioxide` | Total sulfur dioxide level      |
| `density`              | Density of the wine             |
| `pH`                   | Acidity/basicity level          |
| `sulphates`            | Sulphate concentration          |
| `alcohol`              | Alcohol percentage              |
| `quality`              | Wine quality score              |

`Id` is treated as an identifier and is excluded from the analysis.

## 🔍 Exploratory Analysis

The project includes:

### 1. Dataset Overview

* Number of rows and columns
* Data types
* Column information
* Descriptive statistics

### 2. Data Quality

* Missing value analysis
* Duplicate record detection
* Dataset validation

### 3. Univariate Analysis

* Distribution of wine quality
* Distribution of alcohol
* Distribution of acidity-related variables
* Distribution of chemical properties

### 4. Bivariate Analysis

Relationships between wine quality and variables such as:

* Alcohol
* Volatile acidity
* Sulphates
* pH
* Citric acid

### 5. Correlation Analysis

A correlation matrix and heatmap are used to identify statistical relationships between numerical variables and wine quality.

### 6. Outlier Analysis

Boxplots are used to identify potential outliers in the chemical characteristics of wine.

## 📈 Visualizations

The notebook contains visualizations such as:

* Wine quality distribution
* Feature distributions
* Alcohol distribution
* Alcohol vs. quality
* Volatile acidity vs. quality
* Sulphates vs. quality
* pH vs. quality
* Correlation heatmap
* Feature-quality correlation chart
* Boxplots for outlier detection
* Pairplot of selected features
* Average feature values by wine quality

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📁 Project Structure

```text
red-wine-quality-eda/
│
├── Red_Wine_Quality_EDA.ipynb
├── README.md
│
└── dataset/
    └── red_wine_quality.csv
```

## ▶️ How to Run

### Option 1 — Google Colab

Open the notebook in Google Colab and run the cells sequentially.

Upload the dataset when prompted.

### Option 2 — Local Jupyter Notebook

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/red-wine-quality-eda.git
```

Move into the project directory:

```bash
cd red-wine-quality-eda
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Red_Wine_Quality_EDA.ipynb
```

## 💡 Key Insights

The EDA investigates how physicochemical properties of red wine are associated with wine quality.

The analysis focuses particularly on:

* Alcohol content
* Volatile acidity
* Sulphates
* Citric acid
* pH
* Other chemical properties

Correlation analysis is used to identify statistical relationships, while visualizations help reveal distributions, differences between quality groups, and potential outliers.

> Correlation indicates statistical association and does not by itself establish causation.

## 🚀 Future Improvements

This EDA can be extended into a machine learning project by:

* Preparing features for machine learning
* Creating training and testing datasets
* Building classification models
* Comparing multiple machine learning algorithms
* Evaluating model performance
* Performing feature importance analysis
* Building a wine quality prediction application

## 👨‍💻 Author

**Vedant Shinde**

AIML Engineering Student
Sanjivani University

### Connect with me

* GitHub: https://github.com/vedant-4009
* LinkedIn: https://www.linkedin.com/in/vedant-shinde-4oo9/

---

⭐ If you find this project useful, consider giving the repository a star.
