# Hospitalization Utilization Insights: Diagnoses Driving Costs & Stays 


## Project Overview 
This exploratory data analysis (EDA) investigates key drivers of **hospitalization costs** and **length of stay (LOS)** using 2012 New York State inpatient data (NY SPARCS), with a focus on NYC cases. The project aims to: 
1. **Identify high-impact diagnosis**
2. **Analyze severity-LOS relationship**
3. **Pinpoint cost outliers**

## Dataset
- **title**: Hospital Inpatient Discharges (SPARCS De-Identified): 2012
- **provider**: [NY State Department of Health](https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/u4ud-w55t)
- **last updated**: April 1, 2025
- **data accessed**: April 6, 2025
- **dataset overview**:
  - 2.5 million rows 
  - 34 columns 
- **nyc subset data overview**:
  - 1.2 million rows
  - 14 columns

## Technical Stack  
- **Languages**: Python 3.11  
- **Libraries**:  
  - Data Wrangling: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
- **Environment**: VS Code with Jupyter Extension  
- **Version Control**: Git/GitHub  

## Notebook


## Key Findings & Insights
- **Demographics**: Predominantly female patients, aged 30+  
- **Length of Stay**:  
  - Range: 1–14 days  
  - Outliers: Schizophrenia (14-day median) vs. Chest Pain (1-day median)  
- **Cost Distribution**:  
  - Range: $4K–$17K per case  
- **Top Diagnoses**:  
  1. Septicemia (highest cost: $17K)  
  2. Nonspecific chest pain (most frequent)  
  3. Alcohol-related disorders  
  4. Asthma

## Next Steps
- **Explore cost-saving conditions**
- **Compare benchmarks** (NY State and national)
- **Analyze non-clinical LOS factors**
- **Optimize clinical and non-clinical management** 
- **Build real-time dashboard**

---  
**Note**: This analysis is for educational and portfolio presentation only. 

