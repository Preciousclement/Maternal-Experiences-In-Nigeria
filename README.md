# Understanding Maternal Experiences In Nigeria

**Project Type:** Data Retrieval → Cleaning / EDA → Interactive Visualization

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Dataset Tables](#dataset-tables)
- [Tools Used](#tools-used)
- [Objectives](#objectives)
- [Steps Taken](#steps-taken)
- [Key Insights](#key-insights)
- [Power BI Visualizations](#power-bi-visualizations)
- [Conclusion](#conclusion)
- [Contributions](#contributions)
- [License](#license)

---

## Project Overview
This project simulates a realistic dataset of **5,000 Nigerian mothers** to explore maternal health, pregnancy experiences, and delivery outcomes. The dataset is designed for **educational and exploratory use**, providing insights into demographics, pregnancy experiences, and postpartum conditions.

---

## Data Source
The dataset is fictional but statistically inspired by data from:  

- **NDHS 2018**: Fertility rate ~5.5, antenatal care ~60% (≥4 visits)  
- **WHO data**: C-section rate ~2–5%  
- **Studies on postpartum depression**: ~10–15% prevalence in Nigeria  

---

## Dataset Tables
| File | Description |
|------|------------|
| `nigeria_maternal_demographics_5000.csv` | Age, Location (State, rural/urban), Education Level, Marital Status, Employment Status |
| `nigeria_pregnancy_experience_5000.csv` | Number of Pregnancies, Weeks at Delivery, Antenatal Visits & Quality, Cravings, Aversions, Moods, Symptoms |
| `nigeria_delivery_postpartum_5000.csv` | Delivery Method, Place of Delivery, Birth Complications, Support Systems, Postpartum Depression Baby Weight, Health Condition, Access to Postnatal Care |

---

## Tools Used
- **Python** (pandas, numpy)  
- **Jupyter Notebook**  
- **Power BI**

### How to Use
1. Clone the repository
2. Run `Maternal Experience Project Simulation.ipynb` in Jupyter
3. Use CSVs for analysis or modeling

## Objectives
1. Simulate a realistic maternal health dataset for Nigeria.  
2. Analyze patterns in demographics, pregnancy experiences, and postpartum outcomes.  
3. Provide interactive visualizations to explore maternal health trends.

---

## Steps Taken
- Generated a synthetic dataset using Python and Jupyter Notebook.  
- Modeled the data using a **star schema** for efficient analysis.  
- Created calculated measures in Power BI to derive insights.  
- Developed interactive dashboards for Demographics, Pregnancy Experience, and Delivery & Postpartum.

---

## Key Insights
- **Demographics Dashboard**:  
  - Age distribution: 20–34 years dominant  
  - Education: 30.4% none, 39.74% secondary  
  - Urban/Rural: 50.36% urban, 49.64% rural  

- **Pregnancy Experience Dashboard**:  
  - 41% received good quality antenatal care  
  - Common symptoms: nausea, fatigue  
  - Popular cravings: oats, fruits  

- **Delivery & Postpartum Dashboard**:  
  - C-section rate: 16%  
  - Birth complications: 61% (3988 none, 539 hemorrhage)  
  - Postpartum depression: 15% prevalence  

---

## Power BI Visualizations
This project includes **Power BI dashboards** to explore maternal health patterns:

- **Demographics Dashboard** – Visualizes age distribution, education levels, employment, and urban/rural populations.  
- **Pregnancy Experience Dashboard** – Tracks antenatal visits, pregnancy symptoms, cravings, and mood trends.  
- **Delivery & Postpartum Dashboard** – Displays delivery methods (80% vaginal, 16% C-section), birth complications, baby health outcomes (88.67% healthy), and support systems.


### Demographics Dashboard
![Demographics Dashboard](assets/demographics_dashboard.png)

### Pregnancy Experience Dashboard
![Pregnancy Experience Dashboard](assets/pregnancy_dashboard.png)

### Delivery & Postpartum Dashboard
![Delivery & Postpartum Dashboard](assets/delivery_dashboard.png)


**To Interact with the dashboards:**  
1. Open `MaternalHealthDashboard.pbix` in Power BI Desktop.  
2. Load the CSV files.  
3. Interact with slicers and charts to explore different maternal health patterns.

---

## Conclusion
This project provides a comprehensive view of maternal experiences in Nigeria through simulated data and interactive visualizations. It serves as a **valuable educational resource** and can be extended with real data or additional analyses.

---

## Contributions
💡 **Ideas or improvements?** Feel free to fork this repository or open a pull request.

---

## License
📜 This repository is licensed under the **MIT License**.

---

> Made with ❤️ by [Precious Clement] | Driven by data, grounded in community love.
