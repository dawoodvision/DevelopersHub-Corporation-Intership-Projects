# 🌸 Iris Dataset Exploration and Visualization

## 📌 Task Objective
The objective of this task is to learn how to load, explore, summarize, and visualize a dataset using Python. The goal is to understand the dataset structure and identify patterns using basic data analysis techniques.

## 📊 Dataset
This project uses the **Iris Dataset**, which contains **150 samples of iris flowers** from three species:

- Setosa
- Versicolor
- Virginica

Each sample includes four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset is clean and contains no missing values, making it suitable for learning data exploration and visualization.

## ⚙️ Approach

### 1. Data Loading
The dataset was loaded using the **pandas** library.

### 2. Dataset Understanding
The dataset structure was explored using:
- `.shape`
- `.columns`
- `.head()`

### 3. Data Visualization
Visualizations were created using **matplotlib** and **seaborn**.

- **Scatter Plot** to analyze the relationship between sepal length and sepal width.
- **Histogram** to observe the distribution of sepal length.
- **Box Plot** to examine data spread and detect outliers.

### 4. Correlation Analysis
A **correlation heatmap** was created to understand relationships between numerical features.

## 📈 Results and Insights

- **Setosa** generally has shorter but wider sepals.
- **Versicolor and Virginica** tend to have longer sepals.
- Sepal and petal lengths show greater variation compared to widths.
- A strong positive correlation exists between **sepal length and petal length**.

## ✅ Conclusion
Basic data exploration and visualization helped reveal patterns in the Iris dataset.  
Sepal and petal measurements provide useful information for distinguishing between iris species.