# solveathon2019_disastergithub
Github Repository for the Disaster Vulnerability Mapping at Local Level
![Our logo](https://github.com/Together-Against-Disaster/Economic-Disaster-Loss-Estimation-Portal/blob/master/disaster%20management/images/logo.png)

# Problem Statement
Most of the planning and decision making for Disaster Risk Reduction and Management is still being done on an ad hoc basis. Lack of proper identification, impact, and analysis of past data has been a huge setback for effective planning and evidence based decision making.

## About
The portal provides the estimated economic loss data based on the past disasters from 2011 till present. The data is sourced from BIPAD (Building Information Platform Against Disaster), a government-led integrated Disaster Information Management System (DIMS). 

The estimated loss data generated aims to help the decision makers to identify high priority areas for effective preparedness and mitigation planning and decision making. The output will also help the decision makers to plan for effective budget allocation. The data has been estimated using OSL (Ordinary Least Square) method. 


## Methodology 
The estimated model has been generated using the OSL Regression Model (Ordinary Least Square). Ordinary least squares (OLS) regression is a statistical method of analysis that estimates the relationship between multiple independent variables and a dependent variable; the method estimates the relationship by minimizing the sum of the squares in the difference between the observed and predicted values of the dependent variable configured as a straight line. The total loss has been taken as the dependent variable and different hazards that caused the economic loss has been taken as the independent variable. Particularly, the independent variables used are the province, belt, and hazards (animal terror, drowning, epidemic, fire, flood, hailstorm, heavy rainfall, high altitude, landslide, thunderbolt and other natural hazards.
The OLS regression analysis used is  
Y= a + b1x1 + b2x2 + ……………. + bnxn  
  
Y= Total Estimated Economic Loss  
x1 = Province fixed effect  
x2 = Belt fixed effect  
x3 = Animal terror  
x4 = Drowning  
x5 = Epidemic  
x6 = Fire  
x7 = Flood    
x8 = Hailstorm  
x9 = Heavy rainfall  
x10 = High Altitude  	 
x11 = Landslide  
x12 = Thunderbolt  
x13 = Other natural hazards  
  
## Findings
  
Fire was the most frequent hazard  
The total economic loss was most affected by hailstorm  
Most of the hazards were concentrated within some specific location (data error maybe)  
We estimate Morang to have the largest economic loss by hazards at log10(8.4872)  

### Disclaimer

The estimate generated are solely based on the total estimated loss and the indicators used is hazards. Due to unavailability of time and data, other indicators have not been used. 

The R2 error (goodness of fit) for the estimated model is 0.5273.

### Team Members
Aashna Karmacharya  
Alabhya Dahal  
Ankita Shah  
Ankur Shrestha  
Ayasha Khadgi  
Gunjan Ghimire  
Laxman Koirala  
Mohatav Ansari  
Reena Bajracharya  
Sandhya Nepal  
Selina Nakarmi  
Sudhir Bhattarai  






