# National_Transportation_Safety_Board_USA_Aircrash_Database_Analysis
This repository holds all the Python scripts,Powerpoint presentations and excel sheets used for this analysis
**Who is National_Transportation_Safety_Board (NTSB) :**
The National Transportation Safety Board (NTSB) is an independent U.S. government investigative agency responsible for civil transportation accident investigation. In this role, the NTSB investigates and reports on aviation accidents and incidents, certain types of highway crashes, ship and marine accidents, pipeline incidents, bridge failures, and railroad accidents.The NTSB is also in charge of investigating cases of hazardous materials releases that occur during transportation. The agency is based in Washington, D.C. It has four regional offices, located in Anchorage, Alaska; Denver, Colorado; Ashburn, Virginia; and Seattle, Washington.The agency also operates a national training center at its Ashburn facility.
Source : https://en.wikipedia.org/wiki/National_Transportation_Safety_Board

**Objectives of this Analysis :**

1. What is the Yearly Trend of number of aircraft accidents?
2.  Which States report the maximum aircraft accidents
3. Which periods (months,day,time of the day) have maximum aircraft accidents
4. Which Aircrafts of which manufacturers  are involved in maximum aircraft accidents
5. Is bad weather a factor ?
6. Is there a relationship between number of seats and number of injuries,fatalities?
7. What are the  major contributing factors to the accidents identified by NTSB ?

**Dataset :**
This is an internal administrative database owned by NTSB which is publically available below at https://data.ntsb.gov/avdata 
The following subset of this dataset has been created and analysed.
NTSB dataset has the following aircraft categories :
"Airplane,Balloon,Blimp,Glider,Gyrocraft,Helicopter,Powered-Lift,Ultralight"
Only "Airplane" is retained in the subset.
NTSB dataset has the following event categories :
"Accident,Incident,Occurrence,Unknown Event Type"
Only "Accident" is retained in the subset.

**Challenges :**
NTSB database is a MS Access database with 18 different tables related to each other.These have to be exported to Excel,combined and filtered to produce the data subset.
A VBA macro was developed to export all 18 tables from MS Access at once to Excel.
Python scripts are used for developing corelation charts but majority of the visualizations are created in Tableau

**Tableau Storyboard Link**
https://public.tableau.com/app/profile/alankar2299/viz/NTSB_Aircraft_Accidents/Story1?publish=yes


