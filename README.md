# Traffic Accident Risk Analysis

## 📌 Objective

Analyze traffic accident data to identify patterns related to road conditions, weather conditions, and time of day. The aim is to visualize accident hotspots, understand contributing factors, and classify the risk level of accidents.

---

## 📊 Dataset Overview

- **Total Records:** 10,000+
- **Features:**
  - `Accident ID`
  - `Date`
  - `Time`
  - `Location`
  - `Latitude`, `Longitude`
  - `Weather Condition`
  - `Road Condition`
  - `Vehicles Involved`
  - `Casualties`
  - `Cause`

---

## 🧪 Data Processing

- **Data Cleaning**: Removed nulls, fixed inconsistent labels, and parsed datetime columns.
- **Feature Engineering**:
  - Extracted hour from `Time`.
  - Classified risk into:  
    - **High Risk**: Casualties ≥ 4  
    - **Medium Risk**: 2 ≤ Casualties < 4  
    - **Low Risk**: Casualties < 2

---

## 📈 Visualizations

1. **Pie Chart** of accidents by `Road Condition`
2. **Bar Chart** of accidents by `Weather Condition`
3. **Heatmap** of accident hotspots using latitude and longitude
4. **Line Chart** of accident frequency by time of day
5. **Bar Chart**: Casualties by cause of accident
6. **Distribution** of accidents per day/month

---

## 🔍 Key Insights

- Most accidents occurred under **Clear** weather but with **Poor Road Conditions**.
- Accident hotspots were more frequent in urban locations with high traffic density.
- Peak accident times were during **early morning** and **evening rush hours**.
- Majority of **High Risk** accidents were caused due to **Over Speeding** and **Driver Negligence**.

---

## 🤖 Risk Classification

Based on the number of casualties:

| Risk Level   | Condition             |
|--------------|------------------------|
| High Risk    | Casualties ≥ 4         |
| Medium Risk  | 2 ≤ Casualties < 4     |
| Low Risk     | Casualties < 2         |

---

## 🛠 Tools & Technologies

- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Jupyter Notebook**

---

## 📁 Files

- `DS_Task05.ipynb`: Jupyter notebook with all analysis and visualizations
- `accident_data.csv`: Cleaned dataset (optional)
- `README.md`: Project documentation

---

## 📍 Future Scope

- Integrate Machine Learning models for accident severity prediction.
- Use real-time GPS and weather APIs for dynamic risk forecasting.
- Deploy dashboards for public or traffic authority use.

---

## 🙌 Acknowledgements

- Dataset inspired from public safety and transportation sources.
- Project executed as part of data science learning tasks.
