![Firefly 20250530173218](https://github.com/user-attachments/assets/3d2d7dc6-b422-433e-b0ce-f9202ec9b75e)


# ☄️ Meteorite Landings Analysis (NASA Dataset) — Python + Power BI

This project explores over 45,000 meteorite landings collected by NASA, combining Python-based data science techniques with Power BI for interactive dashboarding. We deep-dive into mass trends, fall patterns, geographical distribution, and classification modeling to uncover insights hidden in cosmic debris.

---

## 🔗 Dataset Source

[NASA Open Data Portal – Meteorite Landings](https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/data)

---

## 🛠️ Tools & Technologies Used

| Tool         | Purpose                              |
|--------------|---------------------------------------|
| Python       | Data cleaning, visualization, modeling |
| Jupyter      | Exploratory analysis & testing        |
| Pandas       | Data manipulation                     |
| Seaborn/Matplotlib | Visualization                   |
| Scikit-learn | Machine learning models               |
| Power BI     | Interactive dashboard & reporting     |

---

## 📊 Python Analysis

**Performed in:** `metor.ipynb`

### ✅ Key Steps:
- Data loading and cleaning (handling missing values, converting types)
- Exploratory Data Analysis (EDA)
  - Mass vs. Year scatter plot
  - Mass distribution by Fall type
  - Meteorite counts by decade
  - Pairplots to explore multivariate trends
- Hypothesis Testing
  - Compared masses of “Fell” vs “Found” meteorites using statistical tests
- Feature engineering
  - Log transformation of mass for skew handling
  - Decade column for time analysis
- Machine Learning
  - **Linear Regression**: Predict meteorite mass based on features
  - **Classification Model**: Predict whether a meteorite was “Found” or “Fell” based on numeric and geographic features

---

## 📈 Power BI Dashboard

![image](https://github.com/user-attachments/assets/a3f4dd48-e944-448a-946b-3e3fa2065c60)
![image](https://github.com/user-attachments/assets/c68dc145-5388-4cfc-84ca-e832ba7ae87a)

The Power BI report provides an interactive view of the meteorite landings dataset. It includes:

### ✅ Power BI Visuals:
- **Map** of global meteorite landings by mass and fall type
- **Column chart**: Meteorites per decade (with fall type breakdown)
- **Box plot**: Mass distribution by Fall type
- **Bar chart**: Most common meteorite classes (`recclass`)
- **Histogram**: Distribution of mass with binning
- **Donut chart**: Fell vs Found meteorite breakdown
- **Line chart**: Average mass over time
- **Slicers**: Interactive filters for class, fall type, decade, and mass range

---

## 📌 Key Insights & Conclusion

- **Mass is extremely skewed** — log transformation was key to uncover trends.
- **Found meteorites tend to be heavier** — possibly due to discovery bias.
- **Meteorite discoveries have increased** over the last century.
- **Certain meteorite classes** are far more common than others.
- Simple machine learning models showed promise in classifying fall types and estimating mass based on available features.

---

## 📁 Project Structure
├── metor.ipynb # Python analysis notebook

├── powerbi-dashboard.pbix # Power BI dashboard (not included here)

├── README.md # Project documentation

├── Meteorite_Landing Dataset

---

## 🚀 How to Run

### Python:
```bash
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run `metor.ipynb` in Jupyter Notebook
```
### Power BI:
```bash
1. Open `powerbi-dashboard.pbix` in Power BI Desktop
2. Refresh data source if necessary
```
## 👨‍💻 Author

**Your Name** – [Manas Sawant](https://github.com/Monike123)  
*Project for portfolio, learning, or data storytelling purposes.*

