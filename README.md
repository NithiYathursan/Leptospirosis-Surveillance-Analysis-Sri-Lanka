# Leptospirosis-Surveillance-Analysis-Sri-Lanka
# Leptospirosis Surveillance Analysis – Sri Lanka

A Power BI dashboard developed to analyze **Leptospirosis surveillance data in Sri Lanka from 2021 to 2025**. The project focuses on identifying yearly trends, high-risk provinces, and RDHS regions to support better understanding of disease distribution and surveillance patterns.

## Project Objective

The main objectives of this project are to:

* Analyze the annual trend of reported Leptospirosis cases.
* Compare case distribution across provinces.
* Identify RDHS regions with the highest number of reported cases.
* Provide an interactive dashboard for easier exploration of surveillance data.
* Support data-driven public health monitoring and decision-making.

## Tools Used

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel / CSV**
* Data cleaning and transformation techniques
* Data visualization and dashboard design

## Dataset

The dataset contains **Leptospirosis case data from 2021–2025**, organized by Regional Director of Health Services (RDHS) areas in Sri Lanka.

During preprocessing:

* Sri Lanka total rows were excluded to avoid double counting.
* RDHS names were standardized.
* RDHS areas were mapped to their respective provinces.
* Numerical fields were converted into suitable formats.
* The dataset was transformed into long format for analysis.

## Dashboard Features

The Power BI dashboard includes:

* Total reported cases
* Year-wise case trends
* Province-level analysis
* RDHS-level comparison
* Top affected RDHS areas
* Interactive filters and slicers
* Geographic and regional comparisons

## Key Findings

* **2021:** 6,946 reported cases
* **2024:** 13,328 reported cases, the highest during the analyzed period
* **2025:** 11,191 reported cases
* **Sabaragamuwa Province:** highest cumulative number of reported cases with 11,024
* **Ratnapura RDHS:** highest affected RDHS area with 6,449 cases

The leading RDHS areas included:

1. Ratnapura
2. Kegalle
3. Galle
4. Kalutara
5. Kurunegala

## Public Health Insights

The analysis indicates the importance of strengthening surveillance and preventive activities in high-burden areas, particularly within:

* Sabaragamuwa Province
* Southern Province
* Western Province
* North Western Province

Preventive awareness, early detection, timely reporting, and increased monitoring during high-risk rainy periods may help improve disease-control efforts.

## Dashboard Screenshots

### Dashboard Overview

![Dashboard Overview](screenshots/dashboard_overview.png)

### Regional Analysis

![Regional Analysis](screenshots/regional_analysis.png)

### Trend Analysis

![Trend Analysis](screenshots/trend_analysis.png)

> Replace the image file names above with the exact names of your screenshots.

## Repository Structure

```text
Leptospirosis-Surveillance-Analysis-Sri-Lanka/
│
├── Leptospirosis_Dashboard.pbix
├── README.md
│
├── screenshots/
│   ├── dashboard_overview.png
│   ├── regional_analysis.png
│   └── trend_analysis.png
│
└── data/
    └── cleaned_leptospirosis_data.csv
```

## How to View the Dashboard

1. Download the `.pbix` file from this repository.
2. Install or open **Microsoft Power BI Desktop**.
3. Open the downloaded `.pbix` file.
4. Use the available filters and slicers to explore the dashboard.

## Project Purpose

This project was developed as a **Business Intelligence and Data Visualization project** to demonstrate the use of Power BI for transforming public health surveillance data into meaningful and interactive insights.

## Author

**Nithianandan Yathursan**
BSc (Hons) in Data Science
Sabaragamuwa University of Sri Lanka

## Disclaimer

This dashboard is intended for **academic and analytical purposes**. The findings should not be considered a replacement for official epidemiological reports or public health recommendations.
