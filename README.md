# Understanding Maternal Experiences In Nigeria

**Project Type:** Data Retrieval → Cleaning / EDA → Interactive Visualization

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Dataset Tables](#dataset-tables)
- [Tools Used](#tools-used)
- [Objectives](#objectives)
- [Steps Taken](#steps-taken)
- [Power BI Visualizations](#power-bi-visualizations)
- [Key Insights](#key-insights)
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
- Developed interactive dashboards for Demographics, Pregnancy Experience, and Postpartum. 

---

## Power BI Visualizations

### Demographics Dashboard
<img width="1154" height="647" alt="Maternal Demographics" src="https://github.com/user-attachments/assets/d7745cec-55ac-4e87-bb62-6d199c32e066" />


### Pregnancy Experience Dashboard
<img width="1166" height="653" alt="Maternal Pregnancy" src="https://github.com/user-attachments/assets/2fb991bb-cc17-47ff-9d50-0bc226475696" />


### Delivery & Postpartum Dashboard
<img width="1157" height="652" alt="Maternal Postpartum" src="https://github.com/user-attachments/assets/f9c55fed-19ec-4fe5-a5fc-22fb28a86f3d" />

---

## Key Insights

### 1. Demographics  
- Most mothers fall within the **20–29 years** range, the critical reproductive age bracket.
- Most mothers have at least some secondary education. This suggests that awareness campaigns can effectively leverage existing literacy levels.  
- Rural communities report slightly higher maternal cases than urban areas
- 2577 women are informally employed.  

### 2. Pregnancy & Antenatal Care  
- **Quality of care remains low**: only **41% received good quality antenatal care**, while the majority had poor to fair experiences.  
- The **average number of pregnancies is 4**, consistent with high fertility rates in similar populations.  
- **Preterm births account for ~5% (259 cases)**, underlining the need for better monitoring and early intervention during pregnancy.  

### 3. Delivery & Postpartum  
- **Postpartum depression and mental health issues** are underreported, signaling a gap in maternal support services.
- **Delivery settings are mixed**: 52% in hospitals vs. 48% at home or with traditional birth attendants (TBAs). This split shows gaps in access and trust in formal health systems.  
- **15% of mothers reported postpartum depression**, a significant figure that highlights the need for stronger maternal mental health services.  
- **Postnatal care was accessed by 61% of mothers**, leaving nearly 40% without essential follow-up care.  

### 4. Child Outcomes  
- **Most newborns were healthy (88.7%)**, but **6.6% were underweight** and **4.8% experienced complications**.  
- Low birth weight was strongly associated with **poor antenatal attendance and inadequate nutrition** during pregnancy.  


**To Interact with the dashboards:**  
1. Open `Maternal Health In Nigeria (Simulated).pbix` in Power BI Desktop.  
2. Load the CSV files.  
3. Interact with slicers and charts to explore different maternal health patterns.

---

## Conclusion  
The evaluation highlights clear gaps in **early antenatal care, delivery safety, mental health support, and postnatal follow-up**. While education levels suggest mothers can adopt improved health practices, rural residence and reliance on TBAs remain barriers. Addressing these areas could significantly improve both **maternal and child health outcomes**. 

---

## Contributions
💡 **Ideas or improvements?** Feel free to fork this repository or open a pull request.

---

## License
📜 This repository is licensed under the **MIT License**.

---

> Made with ❤️ by [Precious Clement] | Driven by data, grounded in community love.
