# Indian Flight Delay Analysis

## Overview

This project is a Power BI-based analysis of Indian domestic flight operations, using flight-level data from January 2023 to December 2025. It transforms the dataset into calculated measures and interactive visualizations to examine flight performance, delay patterns, and operational risk factors.

## Objective

To analyze flight operations and identify patterns associated with departure delays, covering airline performance, airport performance, route analysis, temporal trends, weather conditions, and operational risk.

## Dataset

**Dataset:** Indian Flight Delay Datasets
**Platform:** Kaggle
**Source:** https://www.kaggle.com/datasets/leofire123/indian-flight-delay-datasets
**License:** CC0: Public Domain
**Coverage:** January 2023 to December 2025

The dataset contains 23 fields covering flight information, scheduling, routing, temporal attributes, weather conditions, airport congestion, operational risk, and delay information.

| Category | Fields |
|---|---|
| Flight Information | Flight_Date, Airline, Flight_Number |
| Route Information | Origin_Airport, Destination_Airport |
| Scheduling | Scheduled_Departure_Hour, Scheduled_Departure_Minute |
| Temporal Information | Day_of_Week, Month, Is_Weekend, Peak_Hour |
| Weather Conditions | Weather, Temperature_C, Humidity_pct, Wind_Speed_kmh, Visibility_km, Rainfall_mm, Cloud_Cover_pct |
| Operational Factors | Origin_Congestion_Index, Previous_Flight_Delay_Minutes, Turnaround_Risk_Index |
| Delay Information | Departure_Delay, Delay_Target |

## Technology

- Microsoft Power BI
- DAX measures
- Power BI data modeling and visualization features

No Python or SQL is used in this project.

## Planned Report Structure

The Power BI report is planned as a multi-page analytical report:

1. Executive Dashboard
2. Temporal Analysis
3. Airline Performance
4. Airport Analysis
5. Route Analysis
6. Weather Impact Analysis
7. Operational Risk Analysis
8. Delay Driver Analysis

The report will include drill-down and drill-through functionality, along with a dedicated data storytelling section covering historical trends and forecasting.

## Repository Structure

```text
indian-flight-delay-analysis/
│
├── data/
│   └── indian-flight-delay-analysis.csv
│
└── README.md
```

Additional folders (`powerbi/`, `screenshots/`) will be added once the corresponding files exist.


## Data Source and Attribution

This project uses the following publicly available dataset:

**Dataset:** Indian Flight Delay Datasets
**Platform:** Kaggle
**Source:** https://www.kaggle.com/datasets/leofire123/indian-flight-delay-datasets
**License:** CC0: Public Domain

All analytical measures, dashboard designs, visualizations, and storytelling developed in this repository are part of this project.

## Author

Sankari