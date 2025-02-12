# PROJECT TITLE: INTERNAL DISPLACEMENT UPDATE (IDU)- DISASTER & CONFLICT DISPLACEMENT FLOWS
# 📖TABLE OF CONTENT
- [PROJECT OVERVIEW](#project-overview)
- [OBJECTIVES](#objectives)
- [DATA SOURCE](#data-source)
- [TECH TOOLS](#tech-tools)
- [DATA PROCESSING AND TRANSFORMATION](#data-processing-and-transformation)
- [DATA CLEANING](#data-cleaning)
- [DATA ANALYSIS Descriptive Analysis](#data-analysis-descriptive-analysis)
- [DISASTER DISPLACEMENT FINDINGS](#disaster-displacement-findings)
- [CONFLICT DISPLACEMENT FINDINGS](#conflict-displacement-findings)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)
- [CONCLUSION](#conclusion)

# 📌PROJECT OVERVIEW
This repository contains an in-depth analysis of internal displacement trends in Nigeria caused by both conflicts and disasters from 2013 to 2023. The study leverages structured datasets to derive actionable insights that can support policymakers, humanitarian organizations, and government agencies in addressing internal displacement challenges.

# 🎯OBJECTIVES
• Analyze trends in displacement caused by conflicts and disasters over time.

• Identify the demographic distribution of displaced individuals by age and gender.

• Assess the impact of different hazards (floods, storms, wave action) on displacement.

• Investigate major causes and locations of displacement.

• Providing actionable insights for policymakers, humanitarian organizations, and government agencies to improve disaster preparedness, conflict resolution, and risk reduction.

# 📊DATA SOURCE
The datasets used are sourced from the Global Internal Displacement Database (GIDD) and Internal Displacement Monitoring Centre (IDMC). The two main datasets include:
1.	Disaster Internal Displacement Data (2013-2023)
2.	Conflict Internal Displacement Data (2013-2023)
   
# 🛠TECH TOOLS
• Excel → Data cleaning, calculations, and exploratory analysis.

• PostgreSQL → Database management and querying.

• Power BI → Data transformation, visualization, and dashboard development.

# 🔍DATA PROCESSING AND TRANSFORMATION
• Cleaned and structured raw data for consistency and accuracy.

• Created calculated measures to analyze displacement patterns.

• Developed relationships between datasets to enhance comparative insights.

• Categorized displacement cases by age, gender, location, and hazard type.

• Developed interactive dashboards for exploratory analysis.

# 🗑️DATA CLEANING

_**Disaster Dataset**_

- No duplicates found in the dataset.
- Redundant columns removed: ISO3, Event Codes, Event ID, Disaster Internal Displacements.
- Column headers renamed appropriately:
*Date of Event → Event Date
*Displacement Occurred → Displacement Cases
*Disaster Internal Displacement → Disaster Displacement Flows
- Missing values:
Cells/values in the displacement cases have two entries: Preventive and No Preventive Evacuation. The missing values can be detected as Spontaneous Evacuation. These three categories encompass different scenarios under which displacement occurs:
*Displacement without Preventive Evacuations: Occurs without prior warning.
*Displacement with Preventive Evacuations: Occurs due to organized measures.
*Spontaneous Displacement: Occurs due to perceived threats without formal evcuation orders.
*Standardized datatype for Date and Disaster Displacement Flows.

_**Conflict Dataset**_
- No duplicates found in the dataset.
- Redundant columns removed: ISO3, Event Codes, Event ID, Disaster Internal Displacements.
- Column headers renamed appropriately:
*Name → Country
*Conflict Stock Displacement → Internal Displacement People (IDPs)
*Conflict Internal Displacement → Internal Displacement Flows
- Age columns renamed appropriately:
0–4 → Toddlers
5–11 → Children
12–17 → Adolescents
18–59 → Adults
60+ → Aged
- Standardized datatype for Date and Disaster Displacement Flows.


# 📊DATA ANALYSIS Descriptive Analysis
Using Excel Calculations and Pivot Tables, the data was summarized as follows
o Total count of rows - 125

o Total count if Hazard Type is FLOOD, STORM or WAVE- 94, 30, 1

o Total Disaster Displacement Flows – 4097365

o Maximum Disaster Displacement Flows - 2437411

o Minimum Disaster Displacement Flows – 9

o Average Disaster Displacement Flows- 32779

# 🌊DISASTER DISPLACEMENT FINDINGS
• Key Metrics: 4.1M total disaster displacement flows.

• Displacement Cases: 63 cases due to lack of preventive evacuation, 61 due to spontaneous evacuation, and only 1 preventive evacuation recorded emphasizing a lack of disaster preparedness.

• Top Affected Locations: Niger, Adamawa, Benue, and Gombe.

• Hazard Type Analysis: Floods account for the majority (4.05M) of disaster-induced displacements, followed by storms and wave actions. Floods contributed 94% of total displacements, significantly more than storms and wave actions.

• Trend Analysis: Disaster displacement peaked around 2022, with a sharp increase in flood-related displacements.

# ⚔CONFLICT DISPLACEMENT FINDINGS
• Key Metrics: 27.9M total displacement flows.

• Demographic Breakdown: 12.6M adults, 5.5M children, 4.6M toddlers, 3.9M adolescents, and 1.3M aged individuals.

• Gender Displacement Analysis: Both male and female displacement flows show similar trends.

• Trend Analysis: Adult displacement has shown a sharp rise in recent years.

# 💡INSIGHTS
• Conflict remains the dominant driver of internal displacement, affecting all age groups significantly.

• The majority of displaced individuals are adults, emphasizing the socioeconomic impact on the workforce.

• Natural disasters, particularly floods, are a major contributor to forced migration.

• A lack of preventive evacuation measures contributes to high displacement numbers.

• Certain regions experience recurrent displacement, suggesting policy gaps in conflict resolution and disaster preparedness.

# 📢RECOMMENDATIONS
✅ Conflict Mitigation: Strengthen conflict resolution mechanisms to reduce violence-induced displacement.

✅	Disaster Preparedness: Implement more preventive evacuation strategies to minimize displacement impact.

✅	Targeted Aid Distribution: Prioritize support for the most affected demographics, particularly adults and children.

✅	Flood Management: Improve early warning systems and disaster preparedness to reduce flood-related displacements.

✅ Enhance data collection and monitoring for better policymaking.

# 📌CONCLUSION
This project highlights the urgent need for proactive measures to tackle both conflict and disaster-induced displacement. By leveraging data analytics, governments and humanitarian organizations can implement sustainable policies that protect vulnerable populations and enhance long-term resilience.

### 👉Explore the Project Report [here](https://tinyurl.com/nigeriainternaldisplacement)

