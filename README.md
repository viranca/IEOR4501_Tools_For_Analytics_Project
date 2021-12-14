# IEOR4501 Tools For Analytics Project
**Group 41
Swarnim Srivastava, ss6108
Viranca Balsingh, vrb2116**

Introduction
This readme contains a brief documentation on the files Top10.ipynb and Parking.ipynb. They are both made to perform an analysis on the dataset "311_Service_Request_2020.csv" which is available on https://drive.google.com/drive/folders/1BRd8_RSST69UaZRBeD_dtXGw9fuKoBZE?usp=sharing.

The data consists of incidents that were reported to the 311 phone number in the area of New York. The datapoints contain the following parameters: 
'Unique Key'- Unique ID
'Created Date'- Date of creation of incident
'Closed Date'- Date of closing of indcident
'Agency'- Acronym of Agency
'Agency Name'- Name of Govt Agency 
'Complaint Type'- Type of Complaint
'Descriptor'- Details on the type of complaint
'Location Type'- Home/Restaurant/Bar/Sidewalk etc
'Incident Zip'- Zip code where the incident occured
'Incident Address'- Address of the incident
'Street Name'- Street name of the incident
'Cross Street 1'- Address details
'Cross Street 2'Address details
'Intersection Street 1'- Address details
'Intersection Street 2'- Address details
'City'- Brooklyn/Bronx/Manhattan/Queens
'Landmark'- Nearby landmark for identification
'Status'- Open/Closed
'Resolution Description'-Description of how the incident was resolved
'Resolution Action Updated Date'- Date when resolution action was taken
'Community Board'
'BBL'- Identification for location of buildings
'Borough'- Borough name
'X Coordinate (State Plane)'- coordinates of the incident
'Y Coordinate (State Plane)'- coordinates of the incident
'Open Data Channel Type'- Incident contact type
'Latitude'- Coordinates of the incident
'Longitude'- Coordinates of the incident
'Location'- Coordinates of the incident

**Decription to find Top 10 incident types in zip 10025**
##Top10.ipynb
In this Jupyter notebook, the dataset with zip code 10025 is used to filter the data. Then, I look at different columns to identify what are the different types of incidents and find a count (No. of Occuranecs) of these incidents based on their complaint type.Finally, I convert this filtered dataset to a series as asked in the question.

**Description to analyze illegal parking inclidents in Zip 10025**
##Parking.ipynb
In this this Jupyter notebook, the dataset of 311 incidents is analyzed regarding the location of illegal parking incidents. 
Specifically, the fraction of incidents that are due to illegal parking is computed for the whole dataset, and for a subset containing only the data that corresponds to the area with zip code 10025.
These are finally compares, and a boolean called higher_parking_proportion is set True if the proportion of illegal parking incidents within the 10025 zip area is larger that that proportion for the whole dataset, and False otherwise.


