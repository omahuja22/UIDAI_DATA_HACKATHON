# Aadhaar Update Stress & Exclusion Risk Analysis

This repository contains the analysis and visualisation work carried out as part of the **UIDAI Data Hackathon 2026**.  
The project focuses on identifying state-level patterns in Aadhaar enrolment and update behaviour, with particular emphasis on address update challenges faced by adults.

The objective of the study is to derive policy-relevant insights that can support inclusive and preventive improvements in Aadhaar update mechanisms.

---

## Problem Overview

Aadhaar plays a critical role as a foundational identity system in India. While enrolment coverage is extensive, the effectiveness of Aadhaar depends on the accessibility and reliability of update processes, especially address updates.

Adults, particularly those affected by migration, employment-related relocation, or temporary housing, may face difficulties in updating address details due to documentation requirements. Such barriers can result in repeated update attempts, system-level stress, or potential exclusion from Aadhaar-linked services.

This project analyses anonymised Aadhaar datasets to identify patterns that indicate address update stress and geographic concentration of update pressure.

---

## Datasets Used

The analysis is based on anonymised and aggregated datasets provided by UIDAI through the Open Government Data (OGD) Platform:

- Aadhaar Enrolment Dataset  
- Aadhaar Demographic Update Dataset (Address Updates)  
- Aadhaar Biometric Update Dataset  

All datasets are aggregated at the state level and do not contain any personally identifiable information.

---

## Methodology

- Data consolidation and cleaning were performed using Python.
- State names were standardised to ensure consistent aggregation.
- Address update counts were analysed by age group:
  - Children (5–17 years)
  - Adults (18 years and above)
- Descriptive analytics was used to maintain transparency and interpretability.
- Visualisations were developed using Power BI to support comparative and geographic analysis.


---

## Visualisation and Dashboard

State-level visualisations were created using Power BI to illustrate:

- Geographic distribution of adult Aadhaar address updates
- Top states by address update volume
- Comparison between adult and child address updates
- Proportional analysis in high-pressure states

The Power BI dashboard file is provided in the `/powerbi` directory for reference and reproducibility.

---

## Disclaimer

This project uses only anonymised and aggregated data made available by UIDAI for the purpose of the UIDAI Data Hackathon 2026.  
The analysis is intended solely for academic and policy exploration and does not represent official views or conclusions of UIDAI.

---

## Authors

- **Team Name:** Muskan(Lead),Om Ahuja,Tanish Kumar Goyal  
- **Institution:** [Chandigarh grouup of Colleges  
- **Hackathon:** UIDAI Data Hackathon 2026

