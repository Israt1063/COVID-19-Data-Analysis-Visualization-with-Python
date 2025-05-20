
---

# 🦠 COVID-19 Data Analysis & Visualization with Python

This project performs **exploratory data analysis (EDA)** and **visualization** on COVID-19 global time series data using Python, with libraries including **pandas**, **matplotlib**, **seaborn**, and **folium**.

---

## 📁 Dataset

* **Source**: [Kaggle - COVID-19 Clean Complete Dataset](https://www.kaggle.com/datasets/imdevskp/covid-19-in-india)
* **License**: Public dataset shared under Kaggle’s dataset license terms.
* **Access**: Directly imported into Google Colab via `kaggle.json`.

---

## ✅ Project Objectives

* Load and explore COVID-19 time series data
* Clean and preprocess the dataset
* Visualize confirmed, recovered, and death cases globally and by country
* Plot daily trends and compare country-level outbreaks
* Create **interactive geospatial maps** using **Folium**

---

## 🧰 Tools and Libraries

* **Python 3**
* `pandas`, `numpy` – Data manipulation
* `matplotlib`, `seaborn` – Data visualization
* `folium` – Geospatial mapping
* `kaggle` – Dataset download

---

## 📊 Analysis Steps

| Step | Description                                       |
| ---- | ------------------------------------------------- |
| ✅ 1  | Connected Google Colab with Kaggle                |
| ✅ 2  | Downloaded COVID-19 dataset                       |
| ✅ 3  | Loaded and previewed the dataset                  |
| ✅ 4  | Cleaned and explored missing values               |
| ✅ 5  | Grouped global data by date                       |
| ✅ 6  | Plotted global trends of confirmed cases          |
| ✅ 7  | Analyzed country-specific trends (e.g., India)    |
| ✅ 8  | Computed daily new cases                          |
| ✅ 9  | Plotted Top 10 affected countries                 |
| ✅ 10 | Created an **interactive world map** using Folium |

---

## 🌍 Folium Map Preview

An interactive world map showing the latest confirmed COVID-19 cases by country:

```python
# Example: Folium Circle for confirmed cases
folium.Circle(
    location=[lat, long],
    radius=confirmed_cases * 5,
    color='crimson',
    fill=True,
    fill_color='crimson'
)
```

---

## 📌 Sample Visualizations

* Line charts of global trends
* Bar plots for top affected countries
* Interactive geospatial map of confirmed cases

---

## 📁 Folder Structure

```
covid19-analysis/
│
├── covid_19_clean_complete.csv       # Dataset (from Kaggle)
├── covid19_analysis.ipynb            # Colab notebook
├── kaggle.json                       # Kaggle API key (Do NOT share publicly)
└── README.md                         # This file
```

---

## 🔮 What’s Next?

* [ ] Add time-series forecasting (Linear, Polynomial, ARIMA, Prophet)
* [ ] Build interactive dashboard using Streamlit or Plotly Dash
* [ ] Publish as a public Kaggle Notebook

---

## 📌 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `kaggle.json`
3. Run the notebook cell-by-cell
4. Visualizations and maps will display inline

---

## 🙌 Credits

* Kaggle Datasets: [@imdevskp](https://www.kaggle.com/imdevskp)
* COVID-19 Open Data Sources

---

