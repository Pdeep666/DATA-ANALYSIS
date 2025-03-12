# SQL Wildfire Analysis

## Overview
This project analyzes **California Wildfire Data (2013-2024)** using **SQL queries** to extract valuable insights about wildfire incidents, causes, damages, and financial impact. The analysis includes **data modeling**, aggregation, and filtering techniques to help understand wildfire trends and their consequences.

## Business Problem
Wildfires have become increasingly frequent and devastating in California, causing massive destruction to property, loss of life, and significant economic damage. Despite efforts to mitigate wildfires, authorities and businesses struggle with:
- Identifying **high-risk areas** prone to wildfires.
- Understanding the **primary causes** behind wildfire outbreaks.
- Assessing the **financial and human impact** of wildfires.
- Improving **resource allocation and emergency response** strategies.

## Objectives
The primary objectives of this analysis are:
1. **Identify High-Risk Areas**: Determine counties with the most wildfire incidents and burned acreage.
2. **Analyze Causes of Wildfires**: Categorize wildfires based on human activity, natural causes, and unknown factors.
3. **Assess Financial & Human Impact**: Quantify economic losses and fatalities associated with wildfires.
4. **Highlight Extreme Events**: Identify incidents where **over 45,000 acres** were burned.
5. **Classify Business Losses**: Distinguish between **BigLoss and NormalLoss** categories for insurance and risk assessment.
6. **Support Disaster Preparedness**: Provide actionable insights for emergency services and policymakers.

## Features
- **Data Modeling**: Created structured relationships within the wildfire dataset.
- **Year-wise Case Analysis**: Trends in wildfire incidents over the years.
- **Location-based Burned Area Analysis**: Identifies counties with the highest wildfire damage.
- **Fatalities and Financial Loss Assessment**: Summarizes total fatalities and economic impact.
- **Vehicle and Home Damage Reports**: Determines destruction caused by wildfires.
- **Cause-wise Analysis**: Examines the primary reasons for wildfires.
- **High Fatality Incidents**: Identifies locations with the most casualties.
- **Extreme Wildfire Events**: Filters incidents where **over 45,000 acres** were burned.
- **Business Impact Classification**: Categorizes losses as **BigLoss or NormalLoss** based on business destruction.

## Technologies Used
- **SQL** (for data extraction, transformation, and analysis)
- **Wildfire Dataset** (structured data containing wildfire records)

## Key Insights
1. **Year-wise Wildfire Cases (2013-2024):**
   - The highest number of cases were recorded in **2014 and 2021 (13 cases each).**

2. **Top 5 Locations by Average Acres Burned:**
   - **Orange County, Mendocino County, Santa Barbara County, Butte County, and Riverside County** suffered the most damage.

3. **Total Wildfire Fatalities:**
   - **993 deaths recorded from 2013 to 2024.**

4. **Financial Loss Due to Wildfires:**
   - **Total estimated loss: $239.6 million.**

5. **Total Vehicles Damaged:**
   - **15,033 vehicles were destroyed** in wildfire incidents.

6. **Cause-wise Home Destruction:**
   - **Human activity led to 33,432 homes destroyed**, followed by **lightning (30,422) and unknown causes (30,335).**

7. **Most Fatal Wildfire Incident:**
   - **Mendocino County (March 20, 2021) recorded the highest fatalities (20 deaths).**

8. **Financial Loss by Location:**
   - **Los Angeles County alone suffered a financial loss of $16,599.43.**

9. **Extreme Wildfire Events (Over 45,000 Acres Burned):**
   - Locations affected include **Butte County, Mendocino County, Riverside County, Santa Barbara County, Shasta County, Napa Valley, and Sonoma County.**

10. **Fatalities by Cause:**
    - **Lightning: 283 deaths**
    - **Human Activity: 345 deaths**
    - **Unknown Causes: 365 deaths**

11. **Business Impact Classification:**
    - Incidents where **over 400 businesses** were destroyed were categorized as **BigLoss**, while others were classified as **NormalLoss.**

12. **Loss Category Breakdown:**
    - **BigLoss Incidents: 18**
    - **NormalLoss Incidents: 82**

## How to Use This Analysis
- **Government & Fire Management:** Develop policies to reduce wildfire incidents and allocate resources efficiently.
- **Insurance & Financial Planning:** Estimate risk and financial loss projections for affected areas.
- **Emergency Response Planning:** Identify high-risk locations and prepare emergency protocols.
- **Climate Change Research:** Study wildfire trends to assess environmental impact.

## Future Enhancements
- **Predictive Wildfire Analysis** using machine learning.
- **Integration with GIS Mapping** for visualizing wildfire-prone areas.
- **Real-time Monitoring System** for early wildfire detection.

## Contributing
Feel free to submit issues and pull requests if you want to contribute to this project.

## License
This project is licensed under the MIT License.
