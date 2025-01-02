# Victoria Traffic Accident Analysis
This repository contains the complete workflow and analysis for a data-driven project aimed at enhancing road safety in Victoria, Australia. Leveraging advanced data analytics and machine learning techniques, the project examines over a decade's worth of traffic accident data (2012–2023) to extract actionable insights, build predictive models, and develop recommendations aligned with **Victoria's Road Safety Strategy 2021-2030**.

## Project Overview
Traffic accidents remain a significant public safety and socio-economic challenge in Victoria. This project tackles the issue by analyzing **165,643 traffic accidents**, uncovering patterns and trends, and identifying key factors contributing to accident severity (fatal, serious injury, and other injury accidents). The ultimate goal is to provide evidence-based recommendations to reduce severe accidents, save lives, and support Victoria's long-term road safety objectives.

## Key Features
- **Data-Driven Insights**:
  - Comprehensive Exploratory Data Analysis (EDA) revealing patterns related to severity, accident types, environmental conditions, and demographics.
  - Identification of high-risk areas, vulnerable populations, and key contributors to traffic accidents.

- **Machine Learning Models**:
  - Developed and tuned multiple models, including Logistic Regression, Random Forest, Decision Tree, K-Nearest Neighbors, and XGBoost.
  - The tuned **XGBoost model** emerged as the best-performing model with a **67.29% accuracy and recall**, despite challenges like class imbalance and high-dimensional data.

- **Results Analysis**:
  - Feature importance analysis using XGBoost, identifying critical factors such as police attendance, collision types, and speed zones.
  - Visualizations of model performance through ROC curves, feature importance plots, and grouped metric comparisons.

- **Data-Driven Recommendations**:
  - Actionable strategies for improved road safety, resource allocation, policy-making, public awareness, and urban planning.
  - Recommendations include hotspot interventions, predictive insights for high-risk scenarios, and targeted public awareness campaigns.

## Technologies Used
- **Programming Language**: Python
- **Key Libraries**: GeoPandas, Pandas, NumPy, Scikit-learn, SciPy, XGBoost, Matplotlib, Seaborn, and Folium.
- **Data Sources**: VicRoads, Victorian Government Data Directory, Kaggle.

## Google Drive URL
Due to file size limitations, the complete Python script file for this project (220MB) is available via Google Drive:
**[Download Python Script File](https://drive.google.com/file/d/1OMhqEILa-BLQHXCgUD4jYYqGT2YWXQX6/view)**
