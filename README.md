# Meve-Capstone-Project

Motivation 

My motivation comes from my own migration journey from Sudan, through Egypt, and eventually to the United States. Experiencing this firsthand made me aware of how widespread and complex migration is for many foreign families, focusing on the route of Egypt. This project explores the displacement patterns of their populations from 2001 to 2024. My research focuses on these main questions:

1. How many people are coming to the United States and with what classifications?
2. What are the demographics of these populations (age and gender)?
3. Where in the United States has the most settlement of Sudanese?
4. How does the Sudanese population size compare to its East African neighbors?

The Data

I used three primary sources for this analysis:

* UNHCR Demographics: Contains age and gender breakdowns. https://www.unhcr.org/refugee-statistics

* U.S. Admissions Data: Yearly Excel files (2007–2023) showing total arrivals to the United States. https://ohss.dhs.gov/topics/immigration/nonimmigrant/annual-flow-report

* Census Data: ACS data used to identify where Sudanese communities are settled within the U.S. https://data.census.gov/

* Wikipedia: Where it talks about Sudanese- Americans  https://en.wikipedia.org/wiki/Sudanese_Americans

Problems and Hurdles 

The original dataset included global records from 2001 to 2024, which required extensive cleaning and filtering in Python. To focus on Sudanese displacement, I limited the data to cases where Egypt was the country of asylum and Sudan or South Sudan were the countries of origin. The U.S. admissions data presented additional challenges because it was spread across 17 Excel files and contained withheld or non-numeric values that required cleaning. Since the U.S. dataset lacked detailed demographic information, Egypt’s data was used as a proxy to represent age and gender distributions. After analyzing that data, I realized that there is still missing information that I would like to further research. 

Findings

* Family Crisis: South Sudanese groups include a higher percentage of children under 18 and more females than males. This may be because men are often targeted in war, leaving women to raise families.
* Data Gaps: We know how many people come to the U.S., but we often don’t know details like their age and gender. I like to further research that to see if my current analysis is accurate. 

* Volume Spikes: There is a clear correlation between conflict periods in Sudan and sudden spikes in both regional displacement and U.S. resettlement.

How to Run This Notebook
To view or run the analysis:
1. Ensure you have Python and Jupyter Notebook installed.
2. Open Capstone.ipynb and run the cells in order.
* Note: The notebook is designed to automatically clean and combine 17 years of Excel data into one master file which may take a few minutes to process. 

