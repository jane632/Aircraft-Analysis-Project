## Project Overview
As the company tends to expand into the aviation industry, the company's aim is to analyze historical data on aircrafts to identify aircrafts that pose the lowest risks for our new commercial and private operations. By leveraging data on aircraft acccidents and incidents,it provides actionable insights that will guide the aircraft purchase.

## Business Understanding
* Business Problem
As the company explores the aviation industry, understanding the risk profile of different aircrafts is essential. There is need to analyze past incidents to make informed decisions about which aircraft to purchase, ensuring safety in operating and minimal risks associated with aircrafts operation.

* Stakeholders
Have a responsibility for aircraft purchasing decisions which is based on the risk assessment framework on aircrafts.

## Key Business Questions
* What types of incidents have been most prevalent in the aviation sector?
* Which aircraft makes have the less aircraft accidents and injuries?
* How can we correlate weather conditions and flight phases with injury severity?

## Data Understanding and Analysis
 * Source of Data
Our analysis is based on a rich dataset sourced from kaggle dataset.The NTSB aviation accident database contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters.

## Description of Data
 * The dataset includes the following relevant columns that are very useful in the risk assessment framework of low-risk aircraft analysis:

1.Accident.Number: Official accident number assigned by authorities.
2.Event.Date: Date of the incident.
3.Location: Geographic location of the incident.
4.Country: Country where the incident occurred.
5.Injury.Severity: Severity of injuries reported (e.g., fatal, serious).
6.Aircraft.damage: Extent of damage to the aircraft.
7.Aircraft.Category: Classification of the aircraft.(e.g., airplane,helicopter)
8.Make/Model: Manufacturer and model of the aircraft.
9.Purpose.of.flight: Reason for the flight (e.g., commercial, personal)..
10.Total.Fatal.Injuries: Number of fatal injuries reported.
11.Total.Serious.Injuries: Number of serious injuries reported.
12.Total.Minor.Injuries: Number of minor injuries reported.
13.Total.Uninjured: Number of individuals uninjured.
14.Weather.Condition: Weather conditions at the time of the incident.
15.Broad.phase.of.flight: Phase of flight during which the incident occurred (e.g., takeoff, landing).

## Visualizations
  * Incident Frequency by Aircraft Make

This bar chart shows the frequency of incidents by aircraft model, helping to identify the safest options.

![Alt text](Image1.png)

















 * Injury Severity by Aircraft Make

This visualization illustrates how different aircraft models impact injury severity in aviation incidents.

![Alt text](Image2.png)


* Injury Severity Based on Phases of Flight

A multiple line graph detailing the distribution of accident severity during various flight phases, highlighting critical areas for safety focus.

![Tableau Visualization](Injury%20Severity%20Analysis.png)


















* Total Uninjured by Aircraft Make

  
This visualization shows the total number of uninjured by the aircraft make:

![Alt text](Image3.png)













* Occurences of Each Weather Conditions 

The bar graph below shows the weather conditions in which various accidents occur:

![Alt text](Image4.png)


## Conclusion

Model-Specific Risks: Some aircraft models consistently show lower incident rates, indicating they are safer choices for purchase.Although due to perfomance,( Cessna make) is mostly used in the aviation industry.This is shown by the graphs above where Cessna has the highest number of injured and uninjured in the accidents that occur.
Weather Impacts: Weather conditions significantly affect incident severity, suggesting the need for enhanced training and protocols during adverse weather. VMC(Visual Meteorological Conditions) is an ideal weather condition for flying aircrafts which is demonstrated by the graph above thats why its the highest weather condition by the aircraft makes.
Critical Flight Phases: The landing phase has the highest occurrence of serious incidents, highlighting an area where operational improvements can be made.
This project empowers our aviation division with valuable insights into aircraft safety, guiding our strategic decisions as we enter the aviation market. 





## A link to my tableau workbook: https://public.tableau.com/app/profile/jane.njuguna2492/viz/NTSBAviationData/AviationData
