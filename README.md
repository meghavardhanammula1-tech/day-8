 day-8
seaborn visualizaion

Introduction

Seaborn is a Python visualization library built on top of Matplotlib.
It is mainly used for creating statistical graphs and visualizations.
Seaborn works with both Pandas and NumPy datasets and helps in understanding data easily.

---

Topics Covered

1. Line Plot

Line plot is used to show trends or changes in data.

Example

sns.lineplot(data=data, x="x", y="y")

---

2. Scatter Plot

Scatter plot is used to show the relationship between two variables.

Example

sns.scatterplot(data=data, x="x", y="y")

---

3. Box Plot

Box plot is used to display data distribution and identify outliers.

Example

sns.boxplot(data=data, x="category", y="y")

---

4. Violin Plot

Violin plot shows the distribution and density of data.

Example

sns.violinplot(data=data, x="category", y="y")

---

5. Swarm Plot

Swarm plot displays individual data points without overlapping.

Example

sns.swarmplot(data=data, x="category", y="y")

---

6. Bar Plot

Bar plot is used for comparing different categories.

Example

sns.barplot(data=data, x="category", y="y")

---

7. Point Plot

Point plot shows mean values of categories.

Example

sns.pointplot(data=data, x="category", y="y")

---

8. KDE Plot

Kernel Density Estimate (KDE) is used to estimate the probability density function of a dataset.

Example

sns.kdeplot(data["y"], fill=True)

---

Customizing Seaborn

1. Adding Titles and Axis Labels

Titles and labels make graphs easy to understand.

Example

plt.title("Line Plot")
plt.xlabel("X Values")
plt.ylabel("Y Values")

---

2. Changing Plot Colors

We can change graph colors using Seaborn.

Example

sns.lineplot(data=data, x="x", y="y", color="blue")

---

3. Changing Line Width and Markers

Line width and markers improve graph appearance.

Example

sns.lineplot(
    data=data,
    x="x",
    y="y",
    linewidth=3,
    marker="o"
)

---

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

Conclusion

Seaborn is an easy and powerful visualization library used for creating statistical plots and graphs.
It helps in analyzing and understanding datasets using attractive visualizations.