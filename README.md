# UrbanHeatIsland-Prediction-EYChallenge2025


## Overview
The **EY Open Science AI & Data Challenge 2025** is an annual global competition aligned with the **United Nations Sustainable Development Goals (SDGs)** and the **EY Ripples** program. It invites university students, early-career professionals, and EY people to develop AI and machine learning models addressing critical environmental issues.

This year’s theme focuses on the **Urban Heat Island (UHI) effect**, a phenomenon where urban areas experience significantly higher temperatures than surrounding rural areas due to dense infrastructure, limited vegetation, and lack of water bodies. In some cases, the temperature difference can exceed **10°C**, leading to severe health, social, and energy-related challenges.

---

## Objective
Develop a **regression-based machine learning model** that:
1. **Predicts** Urban Heat Island (UHI) Index values for specific urban locations.
2. **Identifies** the key contributing factors behind UHI hotspots in cities.

---

## Dataset Information

**Training Dataset**  
- **Date of collection:** 24 July 2021  
- **Region:** Bronx & Manhattan, New York City, USA  
- **Number of records:** 11,229 measurement points  
- **Variables:** Timestamp, geographic coordinates (latitude/longitude), UHI Index value  

**Important restriction:**  
Latitude and longitude values **must not** be used directly or indirectly (including transformations such as polar coordinates, embeddings, or distance calculations) as predictive features.

## Additional Datasets Used
Participants were encouraged to incorporate publicly available datasets, such as:
- **European Sentinel-2 satellite imagery** (ESA)  
- **NASA Landsat optical satellite data**  
- **NYC Building footprints** (NYC Open Data)  
- **Local weather data** from NYS Mesonet  

---

  ## My Performance
- **Score:** **0.9747** (higher is better)  
- **Rank:** **51st out of 377 valid submissions**  
- **Total participants:** 2,072  
- **Achievement:** Placed in the top 14% of all valid submissions globally

---

  ## Expected Deliverables
- Predictions of UHI Index for the validation dataset (CSV format)  
- Feature importance analysis  
- Contribution to data-driven strategies for **protecting vulnerable communities** and **mitigating UHI effects**  
