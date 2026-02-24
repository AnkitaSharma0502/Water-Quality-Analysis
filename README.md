# Water-Quality-Analysis

This project analyzes water quality monitoring data from Maharashtra under the National Water Monitoring Programme (NWMP) conducted by the Maharashtra Pollution Control Board (MPCB).
The objective is to evaluate water quality, identify pollution risks, and provide actionable insights to support environmental monitoring and decision-making.

The analysis focuses on identifying unsafe water stations, understanding pollution severity, detecting geographic pollution hotspots, and determining key parameters contributing to water quality degradation.

## Objectives:

- Assess overall water quality across monitoring stations

- Identify high-risk stations exceeding safe pollution limits

- Detect districts requiring urgent intervention

- Analyze pollution drivers such as BOD, Dissolved Oxygen, and Coliform levels

- Provide an interactive dashboard for monitoring and decision support

Data Source

Source: Maharashtra Pollution Control Board (MPCB) — National Water Monitoring Programme (NWMP)

Dataset contains water quality measurements collected from multiple monitoring stations across Maharashtra.

- Key parameters include:

- Dissolved Oxygen (DO)

- Biochemical Oxygen Demand (BOD)

- Total Coliform

- Fecal Coliform

- Total Dissolved Solids (TDS)

- pH

- Turbidity

- Station Name

- District

- Geographic coordinates

- Total records analyzed: 222 monitoring stations

- Districts covered: 23

Tools and Technologies Used

Python (Pandas, NumPy, Seaborn, Matplotlib) — Data cleaning and exploratory analysis

Power BI — Interactive dashboard development

DAX — KPI and metric calculations

Power Query — Data transformation

Jupyter Notebook — Analysis workflow

## Data Preparation and Processing

The following preprocessing steps were performed:

Handled missing and inconsistent values

Converted BDL (Below Detection Limit) values using standard half-detection limit substitution

Removed irrelevant columns

Converted parameters to proper numeric format

Created risk classification based on regulatory safe limits

Cleaned Water Class categories (A, B, C, E)

Risk Classification Method

Stations were classified into risk categories based on MPCB safe limits:

Safe: All parameters within safe limits
Moderate Risk: Some parameters exceeding safe limits
High Risk: Multiple parameters exceeding safe limits

This classification helps identify stations requiring intervention.

## Dashboard Features


Total stations monitored

Typical BOD levels

Average dissolved oxygen levels

Risk Analysis

Distribution of stations by risk level

Identification of high-risk districts

- Geographic Analysis

Visualization of pollution hotspots

- District Analysis

Top districts with highest number of unsafe stations

- Operational View

Table showing individual station details for investigation

 
- Users can filter dashboard by:

District

Water Class

Risk Level

Key Insights

Approximately 38.3% of monitoring stations exceed safe pollution limits

Pollution is concentrated in specific districts such as Mumbai, Pune, and Nashik

Organic pollution (high BOD levels) is a major contributor to water quality degradation

Significant geographic clustering of pollution hotspots exists

These findings can help environmental authorities prioritize monitoring and remediation.

<img width="1030" height="587" alt="image" src="https://github.com/user-attachments/assets/d49da321-c4d8-4c8b-a81e-724b0d36ad57" />

<img width="1063" height="600" alt="image" src="https://github.com/user-attachments/assets/36316a58-c568-4fa0-9994-39adcc3f081c" />


How to Use the Dashboard

Open the Power BI file (.pbix)

Use filters at the bottom to select specific districts or risk levels

Explore the map to identify pollution hotspots

View the district chart to identify high-risk regions

Use the station table to investigate individual monitoring stations

The dashboard is interactive and updates dynamically based on selected filters.
