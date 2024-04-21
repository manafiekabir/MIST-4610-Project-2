# MIST-4610-Project-2
## Team Name:
61608 Group 5
## Team Members:
1. Manafie Kabir [@manafiekabir](https://www.github.com/manafiekabir)
2. Avanish Thota [@avanishthota](https://www.github.com/avanish-thota27)
3. Albert Sun [@albertsun](https://www.github.com/Glockgeta)
4. Haley Ford [@haleyford](https://www.github.com/HaleyFord)
5. Nicholas Price [@nicholasprice](https://www.github.com/nickprice347)
6. Sydney Seid [@sydneyseid](https://www.github.com/sydneyseid)

## Dataset Description
Source: 
The dataset originates from the Shark Incident Database for California, which is maintained and published by the California Department of Fish and Wildlife.

Overview: 
The dataset comprises 12 distinct subsets: Attacks 1950_2021, WhiteSharks, Fatalities, Counties, Species, Activity, Month, TimeofDay, MoonPhase, GIS_All_Incidents, GIS_Injuries, and GIS_Fatalities. Each subset serves the purpose of organizing data in a user-friendly manner while sharing common columns across them.

Common Columns: The subsets contain a set of 16 common columns/records, providing consistent data attributes throughout. 
The columns are as follows:

1. IncidentNum (Integer): Unique numerical identifier for each incident. (Primary Key)
2. Date (Date): The date when the incident occurred.
3. Time (Time): The time of day when the incident took place.
4. County (String): Name of the county where the incident occurred.
5. Location (String): Description of the specific location within the county.
6. Mode (String): Method or activity engaged in during the incident.
7. Injury (String): Description of the injury sustained during the incident.
8. InjuryType (String): Type or severity classification of the injury.
9. Depth (String): Depth of the water at the incident location.
10. Species (String): Identification of the shark species involved, if applicable.
11. Comments (Text): Additional remarks or details regarding the incident.
12. Moon Phase(String): What phase the moon was in when an incident occurred.
13. Percent-Full(Decimal): Percentage describing how close the moon was to being full.
14. Longitude(Integer): Longitude where an incident occurred.
15. Latitude(Integer): Latitude where an incident occurred.
16. Confirmed Source(Text): News source that provided confirmation of a given incident.
