![image](https://github.com/pecham1911/AviationProject/assets/159095917/49aa359d-4891-4691-ac7c-dedca0e19dcd)




## Commercial and Private Airplane Maker Recommendations 

## Overview
This project aims to provide your company leadership with the best commercial and private airplane investment recommendations based on the risk of airplane destruction or fatality in an accident.
The purchase price of airplanes can be exorbitant, but the costs of replacement and even more so, fatalities, can be astronomical.  
## Business Understanding
Your company is diversifying its portfolio to include airplanes, but needs to conduct analysis considering the risk to determine the best planes to purchase. 
        
## Data Understanding and Analysis
Data are sourced from the National Transportation Safety Board (NTSB) Aviation Investigations Accident/Incident database. "The NTSB aviation accident database contains civil aviation accidents and selected incidents that occurred from 1962 to present within the United States, its territories and possessions, and in international waters. Foreign investigations in which the NTSB participated as an accredited representative will also be listed." (https://www.ntsb.gov/Pages/AviationQueryV2.aspx; accessed 03/05/2024) Data were pulled for use in this analysis
    from kaggle.com. (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses; accessed 03/01/2024)
    
## Description of data
### Describe shape, important features and limitations
The data used for this analysis contains 18017 rows and 21 columns. Columns: Event.Year, Make.Model, Fatal, and Commercial were all generated using the original NTSB dataset; the remaining columns came directly unaltered from the original data set. 
        Data were filterd to exclude: (a) amateur built planes, (b) events occurring outside the United States, (c) aircraft other than airplanes (including null values), (d) any event with missing make or model, and (e) any event prior to the year 2000. The top 200 makes were printed out, reviewed for likeness, and combined as needed, e.g., Boeing company, BOEING, and Boeing were combined into one make. 
        There are limitations to this dataset and analysis: (a) this database only contains accident/incident data and does not represent successful flights, (b) this analysis was limited to events with "airplane" listed in Aircraft.Category; with a large number (32%) of null Aircraft Category values many probable airplanes not specifically called out as such were dropped from the dataset. (c) this analysis did not filter out the Purpose.of.flight; some values in this column indicate more risky behavior than others and could have impacted the success of the flight. 
           
#### Describe interesting techniques used to prepare/filter data Written interpretation of statistics which inform business questions
### Three visualizations (the same visualizations presented in the slides and notebook)

<img width="361" alt="image" src="https://github.com/pecham1911/AviationProject/assets/159095917/b53b14ef-a445-451a-a3c9-e2b81d101aab">


<img width="370" alt="image" src="https://github.com/pecham1911/AviationProject/assets/159095917/da1db1a0-b078-40c7-a385-e421ec2c35c4">


<img width="368" alt="image" src="https://github.com/pecham1911/AviationProject/assets/159095917/825e27b6-428d-468d-9219-a4d36ea9b01e">

#### An  Dashboard with appropriate visuals 
## Conclusion
### Summary of conclusions including three relevant findings

### LINKS TO THE JUPYTER NOTEBOOK AND PRESENTATION AND TABLEAU
Make sure to also add and commit a PDF of your presentation to your repository with a file name of presentation.pdf   
### Resources
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses![image](https://github.com/pecham1911/AviationProject/assets/159095917/af560a9e-829c-4556-89eb-b7e772652093)

https://www.ntsb.gov/Pages/AviationDownloadDataDictionary.aspx![image](https://github.com/pecham1911/AviationProject/assets/159095917/a3dfbefc-0d92-4447-bea1-1660eadfba93)

https://pixabay.com/photos/airbus-a380-aircraft-airplane-788573/

