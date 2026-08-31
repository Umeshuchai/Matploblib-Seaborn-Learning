# Matplotlib & Seaborn Learning

A practical learning repository covering Matplotlib and Seaborn — the two core Python visualization libraries used in data analysis and machine learning workflows. All concepts are applied directly on the Titanic dataset to keep practice grounded in real data rather than synthetic examples.

---

## What This Repository Covers

### Matplotlib
- Line plots, bar charts, histograms, scatter plots
- Subplots and figure layout
- Customizing colors, labels, titles, legends
- Transparency (alpha) for overlapping plots
- Visualizing distributions, correlations, and feature relationships

### Seaborn
- Heatmap for correlation matrix visualization
- Boxplot for distribution and outlier detection
- Histplot with KDE curve
- Barplot for categorical comparisons
- Pairplot for exploring all feature relationships at once
- Violinplot for distribution shape analysis
- Scatterplot with hue for multi-variable visualization

---

## Why Titanic Dataset

The Titanic dataset is small, real, and messy enough to practice meaningful visualization without spending time on data collection. Every plot in this repository answers a specific question about the data — not just demonstrating syntax but showing what each plot type is actually useful for.

---

## Notebooks

| Notebook | Contents |
|---|---|
| `matplotlib_titanic.ipynb` | All Matplotlib plots and concepts |
| `seaborn_titanic.ipynb` | All Seaborn plots and concepts |

---

## Key Concepts Demonstrated

| Concept | Library | Notebook |
|---|---|---|
| Overlapping histograms with transparency | Matplotlib | matplotlib_titanic.ipynb |
| Scatter plot colored by categorical variable | Both | Both |
| Subplots layout | Matplotlib | matplotlib_titanic.ipynb |
| Correlation heatmap with annotations | Seaborn | seaborn_titanic.ipynb |
| Distribution with KDE overlay | Seaborn | seaborn_titanic.ipynb |
| Pairplot for multi-feature exploration | Seaborn | seaborn_titanic.ipynb |

---

## Dataset

**Titanic Dataset** — download from Kaggle:
[https://www.kaggle.com/datasets/yasserh/titanic-dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

Place the downloaded CSV in the same directory as the notebooks and rename it to `Titanic-Dataset.csv`.

---

## Requirements

```bash
pip install matplotlib seaborn pandas numpy
```

---

## Repository Structure

```
├── matplotlib_titanic.ipynb    # Matplotlib concepts and plots
├── seaborn_titanic.ipynb       # Seaborn concepts and plots
├── Titanic-Dataset.csv         # Dataset (download separately)
└── README.md
```

---

## Libraries Used

| Library | Version | Purpose |
|---|---|---|
| Matplotlib | latest | Core plotting and customization |
| Seaborn | latest | Statistical visualization |
| Pandas | 3.0.5 | Data loading and preparation |
| NumPy | 2.3.5 | Numerical operations |

---

*Part of an ongoing ML engineering learning path. Previous repository: [NumPy and Pandas Learning with Titanic Dataset](https://github.com/umesh)*
