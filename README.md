# Global Earthquake-Tsunami Risk Assessment
### Final Project Data Science 2020: Data Acquisition and Exploratory Data Analysis (Fall 2025)

**Author:** Betsy Hahn  
**Date:** 2025-11-05  

---

## Project Overview

This project analyzes the **Global Earthquake-Tsunami Risk Assessment Dataset**, exploring patterns between earthquake characteristics and tsunami occurrence worldwide. Using R and `tidyverse`, the analysis investigates how factors such as earthquake **magnitude, depth, location, and monitoring coverage** relate to tsunami risk. The goal is to provide actionable insights for disaster preparedness and risk assessment.

---

## Key Questions Explored

- How do **depth** and **distance to the nearest seismic station** affect earthquake intensity recordings?  
- Are tsunamis more frequent in certain **years, months, or locations**?  
- Do **high-magnitude earthquakes** always generate tsunamis?  
- How are earthquakes **spatially clustered** relative to known tectonic faults?  
- Are there **unexpected intraplate earthquakes** or data anomalies?  
- Does earthquake **magnitude correlate with proximity to major faults**?

---

## Methods

- **Data preprocessing:** converting month numbers to names, creating a `Date` column  
- **Exploratory Data Analysis:** scatterplots, bar charts, and geospatial maps  
- **Visualizations:** earthquake depth vs. intensity, tsunami counts over time, earthquake locations worldwide  

---

## Key Findings

1. **Magnitude, depth, and event significance** are strong predictors of tsunami occurrence; larger, shallower earthquakes are most likely to generate tsunamis.  
2. Tsunamis are **highly location-dependent**, concentrated along tectonic boundaries such as the Pacific Ring of Fire.  
3. Not all **extreme earthquakes produce tsunamis**; depth and tectonic setting matter.  
4. Earthquakes are **densely clustered along known fault lines**, with a few intraplate or anomalous events.  
5. **Magnitude alone does not strongly predict proximity to faults**, indicating complex interactions between tectonic context and earthquake mechanics.

---

## Limitations & Considerations

- Dataset shows **no recorded tsunamis before 2013**, likely reflecting reporting gaps.  
- `dmin` (distance to nearest station) is an **imperfect proxy for fault proximity**.  
- Visual and linear models provide **preliminary insights** but do not fully capture tsunami physics.  

---

## Future Directions

- Incorporate more geophysical variables: fault type, rupture mechanism, ocean floor topography  
- Apply **predictive models** (logistic regression, machine learning) for tsunami risk  
- Extend temporal coverage and integrate additional monitoring data for improved reliability  

---

## Repository Structure

- `earthquake_data_tsunami.csv` – Raw dataset  
- `FinalProject_DS201.Rmd` – R Markdown analysis file  
- `plots/` – Folder containing generated visualizations  

---

