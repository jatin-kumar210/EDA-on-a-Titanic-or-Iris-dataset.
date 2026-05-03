# 📊 Exploratory Data Analysis — Titanic & Iris Dataset

A dual-dataset EDA project analyzing the classic **Titanic** and **Iris** datasets using Python. Built as part of the **Horizon Intern — ML Project A**.

---

## 📁 Project Structure

```
├── EDA_ON_IRIS_AND_TITANIC_DATA.ipynb   # Main notebook
├── titanic_eda.png                       # Titanic visualizations
├── iris_eda.png                          # Iris visualizations
└── README.md
```

---

## 🚢 Part 1 — Titanic EDA

### Dataset
- **Source:** [datasciencedojo/datasets](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Shape:** 891 rows × 11 columns

### Data Cleaning
- Filled missing `Age` values with median
- Filled missing `Embarked` with mode
- Dropped `Cabin` column (too many nulls)

### Visualizations
- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Fare Distribution
- Correlation Heatmap

### 🔍 Key Insights

| Metric | Value |
|--------|-------|
| Overall Survival Rate | ~38.4% |
| Female Survival Rate | ~74.2% |
| Male Survival Rate | ~18.9% |
| Average Age | ~29.7 years |
| Average Fare | ~$32.20 |

- Women had a significantly higher survival rate than men
- 1st class passengers survived more than 2nd and 3rd class
- Fare and Pclass show the strongest correlation with survival

---

## 🌸 Part 2 — Iris EDA

### Dataset
- **Source:** `sklearn.datasets.load_iris`
- **Shape:** 150 rows × 5 columns (4 features + Species)
- **Classes:** Setosa, Versicolor, Virginica (50 each)

### Visualizations
- Species Count
- Sepal Length by Species (Boxplot)
- Petal Length by Species (Boxplot)
- Sepal Length vs Width (Scatter)
- Petal Length vs Width (Scatter)
- Correlation Heatmap

### 🔍 Key Insights
- No missing values in the Iris dataset
- **Setosa** is clearly separable from the other two species
- **Versicolor** and **Virginica** overlap slightly
- Petal features (length & width) are the most useful for distinguishing species
- Strong correlation between petal length and petal width

---

## 🛠️ Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🚀 Run

```bash
jupyter notebook EDA_ON_IRIS_AND_TITANIC_DATA.ipynb
```

---

## 📚 Libraries Used

- `numpy`, `pandas` — data loading & manipulation
- `matplotlib`, `seaborn` — visualizations
- `scikit-learn` — Iris dataset loader

---

## 📝 Project Info

| | |
|---|---|
| **Project Type** | Internship — ML Project A |
| **Organization** | Horizon |
| **Domain** | Exploratory Data Analysis |
| **Language** | Python 3 |
| **Status** | ✅ Completed |

---

## 👤 Author

**Jatin Kumar**
Machine Learning Intern — Horizon

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/jatin-kumar211)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=flat&logo=github)](https://github.com/jatin-kumar210/EDA-on-a-Titanic-or-Iris-dataset./tree/main)

---

> *This project was built for learning purposes as part of an ML internship program.*
