# PRODIGY_DS_01

**Population Data Visualization**  
*A Prodigy InfoTech Data Science Internship Task*

---

## 📌 Project Overview
This project explores **world population data** and demonstrates basic **data visualization techniques** using Python. The focus is on representing distributions with **bar charts** and **histograms** to extract meaningful patterns from demographic datasets.  

---

## 📊 Dataset
Two datasets were provided:  
1. **API_SP.POP.TOTL_DS2_en_csv_v2_23-checkpoint.csv**  
   - Source: *World Development Indicators (World Bank)*  
   - Contains country-wise population figures across multiple years.  

2. **Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_23-checkpoint.csv**  
   - Contains metadata (country codes, region names, and related details).  

---

## 🛠 Tools & Libraries
- Python 3  
- **pandas** – Data handling and preprocessing  
- **numpy** – Numerical operations  
- **matplotlib** – Data visualization (static plots)  
- **seaborn** – Enhanced visualization with styling  

---

## 🔎 Workflow
1. **Load Dataset** – Import CSV files into pandas DataFrames.  
2. **Data Cleaning** – Handle missing values, merge with metadata for context.  
3. **Visualization** – Generate histograms and bar charts to show:  
   - Population distribution across countries  
   - Population trends over different years  
   - Regional comparisons  

---

## 📈 Sample Insights
- Countries like **China and India** dominate global population distribution.  
- Population growth shows an **upward trend globally** over recent decades.  
- Several smaller nations and island countries have **populations under 1 million**, creating a highly skewed distribution.  
- Regional grouping highlights clear contrasts between **high-density** (Asia) and **low-density** (Oceania) areas.  

---

## ▶️ How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/BhargavSawant/PRODIGY_DS_01.git
   cd PRODIGY_DS_01
