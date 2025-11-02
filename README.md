# Healthy-Home-Prediction-and-Map-Visualization
This Machine Learning project predicted NO2 concentration level at San Francisco by using geo-related spatial and health data

# Project Structure
1. Set Environment & Data Upload
2. Data Clearning & Preprocessing
3. Exploratory Data Analysis & Data Visualization
4. Model Training & Evaluation & Feature Importance Analysis

# Outcomes:
<img width="790" height="900" alt="image" src="https://github.com/user-attachments/assets/3e2080ce-112b-4f9c-bd41-d81de3911b78" />

# Findings:
1. The plot ranks features by their mean absolute SHAP value, i.e., their average contribution (magnitude) to the model’s output across all observations. Higher SHAP values = greater influence on predicted NO₂ concentration.
2. The distance to the nearest highway is the most influential factor. Locations closer to highways are likely exposed to higher vehicular emissions, leading to increased NO₂ concentrations.
3. Wind speed has a strong impact. Higher wind speeds may disperse pollutants, reducing NO₂, while lower speeds can cause accumulation near emission sources.
4. The presence or proximity of motorways substantially affects NO₂, consistent with traffic-based emission patterns.
5. Residential road types show a moderate influence, possibly indicating lower NO₂ in residential areas compared to major traffic zones.
6. Areas zoned as residential tend to experience reduced NO₂ levels relative to industrial or commercial zones.
7. The distance to primary roads also affects NO₂, reflecting traffic volume and density around major streets.
8. Temperature influences photochemical reactions involving NO₂; warmer conditions may increase pollutant formation or dispersion.
9. Areas with higher population density may have more traffic or localized emissions, contributing to elevated NO₂.
10. Proximity to secondary roads affects NO₂, but less than highways and primary routes.
11. The density of intersections or stops slightly influences NO₂, as idling and acceleration near signals can increase emissions locally.

# Beeswarm Plot: 
<img width="776" height="900" alt="image" src="https://github.com/user-attachments/assets/ef38dfde-77b9-414a-9d39-e7c135f4920d" />

# Findings: 
1. Traffic proximity dominates NO₂ prediction.
    Being near highways, motorways, or primary/secondary roads substantially increases NO₂ levels.
2. Wind speed strongly reduce NO₂.
    High winds disperse pollutants, while stagnant air raises local concentrations.
3. Land use and zoning matter.
    Residential and open-space areas correspond to lower NO₂, while commercial and industrial zones contribute modestly to higher NO₂.
4. Meteorological and demographic factors amplify patterns.
    Higher temperatures and denser populations associate with elevated NO₂, consistent with urban heat and emission intensity.
