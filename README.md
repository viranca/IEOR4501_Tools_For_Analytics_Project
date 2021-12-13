# IEOR4501 Tools For Analytics Project
**Group 41**

**Contributors****
**Swarnim Srivastava, ss6108
Viranca Balsingh, vrb2116**

This readme contains a brief documentation on the files Top10.ipynb and Parking.ipynb. They are both made to perform an analysis on the dataset "311_Service_Request_2020.csv" which is available on https://drive.google.com/drive/folders/1BRd8_RSST69UaZRBeD_dtXGw9fuKoBZE?usp=sharing.
The data consists of incidents that were reported to the 311 phone number in the area of New York. The datapoints contain the following parameters: ['Unique Key', 'Created Date', 'Closed Date', 'Agency', 'Agency Name',
       'Complaint Type', 'Descriptor', 'Location Type', 'Incident Zip',
       'Incident Address', 'Street Name', 'Cross Street 1', 'Cross Street 2',
       'Intersection Street 1', 'Intersection Street 2', 'Address Type',
       'City', 'Landmark', 'Facility Type', 'Status', 'Due Date',
       'Resolution Description', 'Resolution Action Updated Date',
       'Community Board', 'BBL', 'Borough', 'X Coordinate (State Plane)',
       'Y Coordinate (State Plane)', 'Open Data Channel Type',
       'Park Facility Name', 'Park Borough', 'Vehicle Type',
       'Taxi Company Borough', 'Taxi Pick Up Location', 'Bridge Highway Name',
       'Bridge Highway Direction', 'Road Ramp', 'Bridge Highway Segment',
       'Latitude', 'Longitude', 'Location']
 


##Top10.ipynb
In this Jupyter notebook, the dataset with zip code 10025 is used to filter the data. Then, I look at different columns to identify what are the different types of incidents and find a count (No. of Occuranecs) of these incidents based on their complaint type.Finally, I convert this filtered dataset to a series as asked in the question.

##Parking.ipynb
In this this Jupyter notebook, the dataset of 311 incidents is analyzed regarding the location of illegal parking incidents. 
Specifically, the fraction of incidents that are due to illegal parking is computed for the whole dataset, and for a subset containing only the data that corresponds to the area with zip code 10025.
These are finally compares, and a boolean called higher_parking_proportion is set True if the proportion of illegal parking incidents within the 10025 zip area is larger that that proportion for the whole dataset, and False otherwise.


