---
marp: true
theme: default
paginate: true
html: true
style: |
  section {
    background: white;
    color: #2E4A5D;
    font-family: 'Helvetica Neue', Arial, sans-serif;
    padding: 2em 4em;
    position: relative;
  }
  h1 {
    font-size: 1.5em;
    color: #0D2B4E;
    border-bottom: 1px solid #E31937;
    padding-bottom: 8px;
    margin-top: 0;
  }
  .presenter {
    position: absolute;
    bottom: 3em;
    font-size: 1.2em;
    color: #555;
  }

---

# **Hospitalization Utilization Insights: Diagnoses Driving Costs & Stays.** 

<div class="presenter">
Javier Benitez | April 10, 2025  
</div>

---
# Introduction 
**Critical Factors**  
- **Cost**: Most common range between $4k-$17k
- **Length of Stay**: Ranges from 1 to 14 days  
- **Severity**: Moderate/Extreme cases drive cost
- **Diagnoses**: Most common diagnoses by case count

**Dataset**  
- **Source**: [NY Health Data (2012)](https://health.data.ny.gov)  
- **Scope**: 1.2M discharges (NYC-focused)  
- **Size**: 930 MB (34 clinical/demographic fields)

---
# Most patients are 30 years old and older 
![age_group](../images/age_group_dist.png)


---
# Most patients are admitted from the ER and have a mix of illness severity.
![admission_type_illness_severity](../images/admission_type_illness_severityt.png)

---
# Most patients are female 
![gender_distribution](../images/gender_dist.png)

---
# Most cost centers around $20k
![alt text](../images/cost_distribution.png)

---
# Most common diagnoses
![](../images/top_diagnoses.png)

---
# Most common diagnoses and their respective length of stay 
![](../images/los_top_diagnoses.png)

---
# **Most Common Diagnoses Overview**
![most_common_diag_overview](../images/top_diag_vol_cost_los_sev.png)

---
# Key Insights 
**Summary**:
- Dataset: 2012, NYC Focused
- Demographics: female, 30 years and older
- Length of stay: 1-14 days
- Cost range: $4k-$17
- Most common diagnoses: Septicimia, chest pain, alcohol-related conditions, asthma

---
# Next steps
▶ Compare features to state and national benchmarks
▶ Explore conditions for cost savings
▶ Efficient clinical management
▶ Non-clinical factors affecting length of stay
▶ Build real-time dashboard for monitoring