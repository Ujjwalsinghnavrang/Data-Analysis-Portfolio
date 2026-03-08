# 📊 Univariate Analysis using Python

This project demonstrates **Univariate and basic Exploratory Data Analysis (EDA)** using Python libraries such as **Pandas, Seaborn, and Matplotlib**.
The notebook explores datasets and visualizes relationships between variables.

---

## 📁 Project Structure

```
├── Untitled.ipynb
├── Titanic-Dataset.csv
└── README.md
```

---

## 🚀 Features

* Data loading and preprocessing using **Pandas**
* Data visualization using **Seaborn**
* Exploratory analysis of datasets
* Understanding relationships between numerical and categorical variables

---

## 📚 Datasets Used

1. Titanic Dataset
2. Tips Dataset (from Seaborn)
3. Flights Dataset (from Seaborn)
4. Iris Dataset (from Seaborn)

---

## 📊 Visualizations Used

### Scatter Plot

Used to visualize relationships between two numerical variables.

```python
sns.scatterplot(x=bill['total_bill'], y=bill['tip'])
```

### Bar Plot

Used to compare numerical values across categories.

```python
sns.barplot(x='Pclass', y='Age', data=titanic)
```

### Box Plot

Shows distribution and outliers in the data.

```python
sns.boxplot(x=titanic['Sex'], y=titanic['Age'], hue=titanic['Survived'])
```

### Distribution Plot

Used to visualize probability distribution.

```python
sns.distplot(titanic[titanic['Survived']==0]['Age'], hist=False)
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Jupyter Notebook

---

## ⚙️ Installation

Clone the repository

```
[git clone https://github.com/yourusername/repository-name.git](https://github.com/Ujjwalsinghnavrang/Data-Analysis-Portfolio/edit/main/Project-Bivariate_Analysis_ML/README.md)
```

Install required libraries

```
pip install pandas seaborn matplotlib
```

Run the notebook

```
jupyter notebook
```

---

## 🎯 Purpose of the Project

This project helps beginners understand:

* Exploratory Data Analysis (EDA)
* Data visualization techniques
* Handling datasets in Python
* Understanding numerical and categorical relationships

---

## 👨‍💻 Author

**Ujjwal Singh Navrang**
Computer Science Engineering Student
MANIT Bhopal

---

⭐ If you found this useful, please consider starring the repository!

