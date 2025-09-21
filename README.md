 Air-Purifier-Analysis

📚 Overview
This project analyzes air quality data across various regions in India, focusing on pollutants,
air quality index (AQI) trends, and health correlations. 
The goal is to inform strategic decisions regarding air purifier products in Southern India.

🔍 Problem Statements
1. Top and Bottom Areas by AQI: Identify the top 5 and bottom 5 areas with the highest average AQI from December 2024 to May 2025.
2. Prominent Pollutants: Determine the top 2 and bottom 2 pollutants for each state in Southern India
   (Andhra Pradesh, Telangana, Karnataka, Kerala, Tamil Nadu) since 2022.
3. AQI Improvement Analysis: Analyze whether AQI values improve on weekends compared to weekdays in major Indian metro cities.
4. Worst Air Quality Months: Identify months that consistently exhibit the worst air quality across
   the top 10 states with the highest number of monitored areas.
5. Bengaluru Air Quality Categories: Count the number of days falling under each air quality category for Bengaluru from March 1, 2025, to May 31, 2025.

📊 Strategic Analysis for Product Decisions
1. Severity Mapping: Identifies cities with persistently worsening AQI trends and tracks the number of days spent in "Unhealthy+" categories.
2. Health Impact Correlation: Investigates the correlation between AQI spikes and the occurrence of health 
   events from the IDSP data, producing a correlation measure per state and month.
3. Demand Triggers: Analyzes the temporal relationship between pollution spikes (AQI) and inferred demand triggers, 
   using vehicle registrations and population growth as a proxy for potential market demand.
4. Market Size Proxies: Computes market size proxies for top cities and states, including per-capita
   AQI burden and per-household potential, using Vahan and population data.

📊 Data Sources:- 
   AQI Data: Air Quality Index data for various regions.
   Health Data: Health event counts from the Integrated Disease Surveillance Programme (IDSP).
   Population Data: Population projections for different states.
   Vehicle Registration Data: Data on vehicle registrations by state.
   
⚙ Dependencies:
   This project requires the following Python libraries:
  . pandas
  . scipy
  . datetime

 Conclusion:
 This project provides a comprehensive framework for using publicly available data 
 to drive strategic business decisions in the air purification market. 
 The insights gained can help identify key markets,
 understand demand drivers, and justify product development.
