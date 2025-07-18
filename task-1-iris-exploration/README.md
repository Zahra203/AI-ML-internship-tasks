# Task 1: Iris Dataset Exploration and Visualization

## Objective
Explore and visualize the Iris dataset using Python libraries to understand feature relationships, patterns, and data distribution.

---

## Dataset
- **Name**: Iris dataset
- **Source**: Built-in dataset from Seaborn
- **Samples**: 150 iris flowers
- **Features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target**: Species (Setosa, Versicolor, Virginica)

---

## Techniques Used
- Data loading and inspection using **Pandas**
- Summary statistics using `.describe()` and `.info()`
- Visualizations: Scatter plots, histograms, box plots, pair plots
- Outlier and distribution analysis

---
### Final Insights

- The dataset contains 150 samples with no missing values.
- Petal measurements (especially length and width) show clear separation among species.
- Setosa is well-separated from other classes.
- Some outliers can be seen in Sepal Width for certain samples.
- This dataset is suitable for beginner-level classification models.

---

## Libraries Used (with Short Explanation)

| Library           | Purpose                                                 |
|-------------------|----------------------------------------------------------|
| **pandas**        | Handle and explore structured tabular data               |
| **matplotlib**    | Create static, basic plots (scatter, box, histograms)    |
| **seaborn**       | Generate enhanced and stylish statistical plots          |
| **numpy**         | Handle numerical data and support plotting/analysis      |

---

## Files Included
- `iris_exploration.ipynb`: Jupyter notebook with full code and visualizations
- `README.md`: Summary and description of the task
