### Introduction
<br>
In March 2020, a global pandemic was declared by the World Health Organization due to the Covid-19 virus outbreak. As a result, the South African Government imposed a National Lockdown which prohibited individuals from leaving their homes except under strictly controlled circumtances to reduce the transmission of the virus. In that same year, according to the Global Peace Index (GPI) produced by the Institute for Economics and Peace (IEP) (https://www.visionofhumanity.org/wp-content/uploads/2020/10/GPI_2020_web.pdf), South Africa went up from the 127th safest country in the world to the 123rd. Though this ranking has been as a result of several known factors, a very prominent one is the Rate of Crime in the Country which has been quite rampant in the past few years and consumes as much as 19% of the Country's GDP which is about $ 67 billion per annum.(https://www.managementstudyguide.com/impact-of-crime-on-south-african-economy.htm).
<br>


**The Following will be achieved in this project:**
<br> Analyse the changes in the crime distribution in South Africa. Has there been a significant change in South Africa's crime rate? If so, we determine the hypothetical reason behind it..<br>

<br>Determine if there is a correlation between the total number of police stations in a province compared to the total amount of crimes and the total amount of crimes committed compared to the population and density of a Province<br>

<br>Determine if there is a correlation between the Covid-19 Lockdown and South Africas crime rate in the year 2020/21 by comparing the rate in 2020/21 to the historical data and then identifying the time period with significant increase/decrease. Did the Lockdown permit for more crimes to be committed or did it reduce the number of crimes in the country? What crimes had a significant increase/decrease, and what could have been the cause?<br>

<br>Create a Regression Model using Machine Learning to predict the expected crime rate without the influence of the Covid-19 Lockdown.<br>

**Research Question**
Is there a significance change in crime distributions in South Africa and does population and number of stations per province have effect on crime rate?
What impact did the Covid-19 Lockdown Restriction have on the crime rate in South Africa?

**Methodology**
<br>A brief overview of the methodology used in this Notebook:
<br>
**Load data**
Reading data
Data Wrangling
Exploratory plots
Modelling
Hypothesis Testing
Interpreting Results
Conclusion
Hypothesis
Will crime rate in South Africa increase in the next 5 years?
<br>
**Data Description**
<br>
This Notebook Contains 3 datasets from the sources referenced below:

SouthAfricaCrimeStats_v2.csv dataset was downloaded from Kaggle.com (https://Kaggle.com/slwessels/crime-statistics-for-south-africa) on the 15/03/2021. The dataset was published by Stephan Wessels on the 19/10/2016 and was updated by the publisher on the 17/11/2019. It was sourced by the publisher from the South African Police (SAPS) Official website http://www.saps.gov.za/resource_centre/publications/statistics/crimestats/2015/crime_stats.php in collaboration with StatsSA and contains South African crime statistics, broken down per province, station and crime type.

2018_2019_crimestatistics.xlsx dataset was downloaded from (https://www.saps.gov.za/services) on the 19/04/2020
<br>
**Observation**
<br>According to the information about the datasets, we have two csv files one for South African crime stats and Province populations. South African crime stats dataset consists of a mix of categorical and numerical data and has 14 columns and 30861 rows, the Province populations dataset has 4 columns and 9 rows.<br>

The crime categories in the South African Crime stats dataset are as follows:

**Crime Categories**
<br>Each category of crime which was recorded between the year 2005 - 2020:<br>

All theft not mentioned elsewhere
Theft out of or from motor vehicle
Drug-related crime
Robbery with aggravating circumstances
Common assault
Commercial crime
Burglary at residential premises
Assault with the intent to inflict grievous bodily harm
Theft of motor vehicle and motorcycle
Shoplifting
Malicious damage to property
Common robbery
Burglary at non-residential premises
Sexual Offences
Driving under the influence of alcohol or drugs
Stock-theft
Attempted murder
Carjacking
Robbery at non-residential premises
Robbery at residential premises
Murder
Illegal possession of firearms and ammunition
Arson
Truck hijacking
Robbery of cash in transit
Bank robbery
Sexual offences as result of police action
17 Community Reported Serious Crimes
Attempted sexual offences
Contact-related crime
Contact sexual offences
Crime detected as a result of police action
Kidnapping
Other serious crime
Property-related crime
Rape
Sexual Assault
Sexual offences detected as a result of police action
TRIO Crime
Abduction
Crimen Injuria
Culpable homicide
Neglect and ill-treatment of children
Public violence
<br>
**Provinces**
<br>The provinces we will be looking at crime are as follows:<br>
<br>
Gauteng
Kwazulu-Natal
Eastern Cape
Western Cape
Limpopo
Mpumalanga
North West
Free State
Northern Cape
<br>

**Limitation**
<br>The South African Police Service regardless of being the major source of the crime statistics in the country still does not represent all crimes in the country as not all crimes are reported/recorded by the police due to several reason .i.e Lack of trust in the police by victims/communities, police officers taking victims/communities seriously depending on the type of crime committed, the race of who is reporting the crime or the area where it is committed etc. This means that the official numbers might be under-representing a particular category/the total crime rate in the country.<br>
