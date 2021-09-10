# california_ed_discharge_encounters
Uses the facility level datasets for a preliminary analysis into discharge encounters in California counties.

Note: this analysis do was conducted using publicly available data. The contents of this project are for educational purposes and a ficticious company.

# Context
CaLED, a fictitious company, specializes in developing user experience (UX) related solutions for healthcare facilities and patients. A UX research manager wants to investigate patient encounters in California. 

# Goal
Conduct a preliminary investigation of discharge encounters related to patient race groups and ED discharge types.


# Guiding Questions
The UX research manager at CalED wants results relating to the follwing questions:
<ul>
  <li>What race group is has strong associations with patient discharge encounters?</li>
  <li>Are there any additional profiles based on facilities related to patient discharge encounters?</li>
</ul>

# Data Overview
### Source: Datasets from the Office of Statewide Health Planning & Development (OSPHD)

<ul>
<li>[Hospital Emergency Department - Characteristics by Facility (Pivot Profile)](https://data.chhs.ca.gov/dataset/hospital-emergency-department-characteristics-by-facility-pivot-profile)</li>
<li>[Hospital Encounters by Facility to use ED visits and Admission data](https://data.chhs.ca.gov/dataset/hospital-emergency-department-encounters-by-facility/resource/eb592e95-d6bd-4ec7-9493-840978188c88)</li>
<ul>[COVID-19 Related Data for Addional Analysis](https://data.ca.gov/dataset/covid-19-time-series-metrics-by-county-and-state1/resource/6a1aaf21-2a2c-466b-8738-222aaceaa168)</ul>
</ul>

## Data Collection 
OSHPD collects the data from multiple healthcare institutions. Although the quality of the data depends how the institutions collect the data, the data is deemed trustworthy by the analyst. The data are sourced from two databases, the ED Treat-and-Release Database and the Inpatient Database (i.e., patients treated in the ED and then formally admitted to the hospital). 

## Data Content
The dataset contains annual Excel pivot tables that display summaries of the patients treated in each Emergency Department (ED). The summary data include number of visits, expected payer, discharge disposition, age groups, sex, preferred language spoken and race groups.

## Data Relevancy 
Based on the criteria outlined in the given project brief, the data contain more than 5 categorical and numeric variables, and over 5000 rows when combined before cleaning. The locations are on a facility level but the analysis with focus on counties within California. The county names will suffice because the numerical codes are available. The combined data are also timely, i.e., from 2005 to 2020.

## Why this dataset?
I previously studied about patient privacy concerns and healthcare workers information needs. The chosen datasets fit my interests because I want to conduct analysis on a facility level as opposed to individuals. Open data related to healthcare that fit the criteria of the project brief are not readily available. After an intense search, this was the only dataset that fit my interest in emergencies and satisfies the requirements. I hope that this dataset will spur further investigations into emergency and privacy related datasets.


# Deliverables
<ul>
  <li>Python codes </li>
  <li>[Tableau Report](https://public.tableau.com/views/InvestigatingEmergencyEncountersinCalifornia/Story?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)</li>
  <li>[Storyboard Planning and Project Relection](https://drive.google.com/file/d/1BqoZd55Z-mw75ogBUxGXljTFnwbG7L8X/view?usp=sharing)</li>
</ul>
