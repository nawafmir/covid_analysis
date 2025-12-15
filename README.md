# COVID-19 Power BI Dashboard  

Power BI analysis of COVID-19 dataset  

This project explores how different factors influenced COVID-19 cases and outcomes using a public dataset. The analysis was done in Power BI, covering administrative, clinical, comorbidity, and demographic aspects of patients.  

---

## Table of Contents  
- [Objectives](#objectives)  
- [Dataset](#dataset)  
- [Dashboard Sections](#dashboard-sections)  
- [Tools Used](#tools-used)  
- [Key Insights](#key-insights)  
- [Repository Contents](#repository-contents)  

---

## Objectives  
- Clean and prepare raw COVID-19 data for analysis.  
- Build an interactive Power BI dashboard.  
- Highlight the effect of administrative, clinical, comorbidities, and demographic factors on COVID-19 outcomes.  

---

## Dataset  
- **Source**: [COVID-19 Dataset (Kaggle)](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data)  
- **Records**: 1M patients (Mexico)  
- **Key fields**: Sex, Age, Diabetes, Hypertension, Obesity, ICU, Intubation, Date of Death, Patient Type, etc.  

---

## Dashboard Sections  

### Overview | Administrative | Clinical Care  
<p align="center">
  <img src="images/Overview.png" width="32%" style="margin: 5px;" />
  <img src="images/Administrative.png" width="32%" style="margin: 5px;" />
  <img src="images/Clinical_Care.png" width="32%" style="margin: 5px;" />
</p>

### Comorbidities | Demographics  
<p align="center">
  <img src="images/Comorbidities.png" width="48%" style="margin: 5px;" />
  <img src="images/Demographics.png" width="48%" style="margin: 5px;" />
</p>

---

## Tools Used  
- **Power BI**: Data modeling, DAX, dashboard design  
- **Excel**: Data cleaning and preparation  
- **DAX**: Calendar table and measures for time-based analysis  

---

## Key Insights  
- Hospital type and medical units influenced admission and outcomes.  
- ICU and intubation patients had higher mortality compared to outpatients.  
- Comorbidities like diabetes, hypertension, and obesity increased risk.  
- Age and gender were major demographic factors affecting severity.  

---

## Repository Contents  
📁 **images/** → Dashboard screenshots  
📄 **COVID-19 Patient Analysis.pbix** → Power BI file  
📄 **README.md** → Documentation  

## Report  
View the full PDF report [here](docs/COVID-19_Patient_Analysis.pdf).
