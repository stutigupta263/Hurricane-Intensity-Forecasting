**Hurricane Intensity Forecasting using LSTM and Vulnerability Analysis**

This project integrates machine learning with socio-demographic analysis to forecast hurricane behavior and identify vulnerable regions. The project focuses on Hurricane Ian, which struck the U.S. in September 2022, and aims to improve disaster preparedness through accurate path and intensity predictions combined with targeted vulnerability assessments.

**Objectives**

1. Vulnerability Analysis:

  -Identify counties most affected by Hurricane Ian.
  
  -Use socio-demographic data (e.g., income, vehicle availability, age distribution) to compute aid scores for disaster management.
  
2. Hurricane Path and Intensity Forecasting:

  -Develop an LSTM-based model to predict hurricane path and intensity using sequential data.
  
  -Evaluate the model's performance with different sliding window sizes.
  
**Methodology**

_Phase 1: Vulnerability Analysis_

Data Sources:

-Hurricane Cone and Track Data: Extracted from the National Hurricane Center (NHC).

-Demographic Data: Census data (age, income levels, vehicle ownership).

-Geographic Data: Census TIGER/Line shapefiles for spatial intersections.

Key Metrics:

-Vehicle Availability Index: Prioritizes evacuation needs.

-Income-Based Vulnerability Score: Quantifies economic resilience.

-Aid Need Score: Combines age, sex, and population factors.

_Phase 2: LSTM-Based Prediction_

Model: Long Short-Term Memory (LSTM) network.

Data Preprocessing:

-Feature engineering: Calculated derivatives for wind speed and storm movement.

-Sliding window approach to capture temporal dependencies.

Evaluation:

-Mean Absolute Error (MAE) for path and intensity predictions.

-Compared performance with varying window sizes.
