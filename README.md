# Chicago Crime Analysis Project

## Problem Statement
Crime is a critical problem in metropolitan cities around the world. Chicago, as a culturally rich and economically significant city, has also seen many crime-related problems over the years. Crime pattern comparison over time and space could potentially provide important findings for law enforcement agencies, policymakers, and the public.

The goal of this project is to do an extensive data analysis of crimes committed in Chicago to identify trends, hotspots, and the effectiveness of enforcement.

---

##  Business Understanding

Crime analysis can help:
- Law enforcers more effectively deploy resources.
- City planning authorities better understand risk areas.
- Public safety and education improvement.
- Policy development on temporal or demographic crime patterns.

This project applies data visualization, correlation analysis, and aggregation techniques to support crime reduction.

---

## Problem Being Solved

The project solves for:
- What are the types of crime most prevalent and where?
- Is there a peak year or month for crime?
- How do demographics (e.g., race or location) relate to types of charges?
- What are the trends in crime by time and zip code or district?

By addressing these, the project hopes to help stakeholders to observe when, where, and why crimes occur.

---

## Dataset Overview

This project utilizes some sheets from an aggregated Excel file of Chicago crime data:

- **Total Cases**: Total offenses by year.
- **By Year**: Breakdown of offenses by year.
- **Race**: Demographic breakdown by race.
- **Charge Description**: Frequency of different charges.
- **By Month**: Monthly trends in offenses.
- **Dashboard**: Visualized aggregates and KPIs.
- **Data**: Raw detailed data to examine in detail.

---

## Technologies Used

- **Excel**

---

## Key Insights

- Crime is highest in some years/months — and requires further examination.
- Some districts and zip codes consistently have high crime rates.
- Some ages and races may be disproportionately represented among charge types.
- The heatmap of correlations shows low or zero strong linear relationships — which means that crime depends on non-linear or context-dependent factors.

---



##  Visual Analysis and Insights


---


###  Crimes Filed by Year
![](https://github.com/Danush-US/Chicago-Crime-Analysis/blob/main/By%20year.png)

- Dropped reports after 2019, especially in the COVID-19 period.
- 2014 was the year with the highest filing.

---


###  Crimes Filed by Month
![](https://github.com/Danush-US/Chicago-Crime-Analysis/blob/main/By%20month.png)

- Highest cases filed during **spring to early summer**.
- Facilitates seasonal planning and deployment of law enforcement.

---

### Most Common Charges
![](https://github.com/Danush-US/Chicago-Crime-Analysis/blob/main/Charge%20Description.png)

- **Leading charges** are:
  - Issuance of Warrant
  - Drug Possession (PCS)
  - Driving on Suspended License
- Facilitates comprehension of priorities of enforcement and gaps in policy.

---

### Interactive Dashboard Summary
![](https://github.com/Danush-US/Chicago-Crime-Analysis/blob/main/Dashboard.png)

Includes:
- **Year** and **Race** filters
- Crime trends over time
- Breakdowns by charges and race
- KPI measures for breakdown of number of charges

---

### Raw Dataset Preview
![](https://github.com/Danush-US/Chicago-Crime-Analysis/blob/main/Dataset.png)

Snapshot of structured tabular data utilized for visualizations and metrics computation. 

---

### 🔢 Total Criminal Cases Overview

![](https://github.com/Danush-US/Chicago-Crime-Analysis/blob/main/Total%20Case.png)

This visual summarizes the total number of criminal cases filed in Chicago from 2014 to 2023:

- **Total Cases Filed**: 585,418
- **Cases with Multiple Charges**:
  - **Charge 1**: 585,418 (100% of cases)
  - **Charge 2**: 247,963 (~42%)
  - **Charge 3**: 136,051 (~23%)
  - **Charge 4**: 75,410 (~13%)

These numbers show that a large proportion of criminal incidents involve more than one offense, suggesting recurring patterns of co-offending. This insight is valuable for legal resource planning and understanding the complexity of criminal behavior in urban environments.


---



## Future Improvements

- Employ machine learning to predict crime hotspots.
- Time series forecasting to predict crime rates in the future.
- Use spatial analytics (e.g., Folium or GeoPandas) to enhance geo-mapping.
- Add socio-economic variables to give more depth to the analysis.

---



