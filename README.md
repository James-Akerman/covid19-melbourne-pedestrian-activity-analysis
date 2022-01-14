# Pedestrian activity in the City of Melbourne before and during COVID-19
### Pedestrian Counting System Background
The City of Melbourne is the local council which oversees what many would consider to be the heart of Melbourne. It spans a wide area range from the postcodes of Port Melbourne to Flemington, Carlton, and South Yarra. It contains several of Melbourne's most important landmarks such as the Royal Botanical Gardens as well as important areas of economic activity like the Melbourne CBD.

With so much going on in the City of Melbourne it is probably not too surprising to learn that they been monitoring pedestrian activity within their council since at least 2009 through their Pedestrian Counting System. The aims of the Pedestrian Counting System, as stated by the City of Melbourne are to:
- inform decisions about urban planning and management
- identify opportunities to improve city walkability and transport
- measure the impacts of events and specific marketing campaigns on pedestrian activity
- monitor retail activity in the city
- assist the business community in developing marketing strategies to maximise their exposure and identify staffing, security and resource requirements.
(City of Melbourne, 2021)


### Our Research and Scope
Like every part of the country, the area within the City of Melbourne has been strongly affected by the disruptions to daily social and economic life caused by the COVID-19 pandemic with research by Deloitte estimating that the Melbourne CBD economy is not expected to bounce back until late 2024 (City of Melbourne, 2021). With this in mind, we wanted examine changes to pedestrian activity both shortly before and during the COVID-19 pandemic and examine possible influences on it during this time period. We limited the scope of our base data to pedestrian activity the two years between August 2019 (around 7-8 months before the pandemic arrived in Australia) and August 2021.

From this base data, as well as data provided by labour force statistics from the Australian Bureau of Statistics, and the Australian Department of Treasury, we sort to answer the following broad sets of questions

- Hypothesis One: The overall pedestrian activity in the City of Melbourne had decreased since March 2020 when the first lockdown happened in Melbourne.
- Hypothesis Two: Pedestrian activity had increased after the first lockdown, but not to pre-pandemic levels (average of August 2019 to February 2020).
- Hypothesis Three: Pedestrian activity would increase as JobKeeper claims increased.
- Hypothesis Four: Pedestrian activity would decrease after JobKeeper was tapered.
- Hypothesis Five: Pedestrian activity increases as the number of Victorian full-time workers increases.

### References

- City of Melbourne,*Pedestrian Counting System*, City of Melbourne, accessed 14 September 2021 <https://www.melbourne.vic.gov.au/about-melbourne/research-and-statistics/city-population/Pages/pedestrian-counting-system.aspx>

- City of Melbourne,*Research shows CBD economy will bounce back*, City of Melbourne, accessed 16 September 2021 <https://www.melbourne.vic.gov.au/news-and-media/Pages/Research-shows-CBD-economy-will-bounce-back.aspx>


## Tools/Packages Used
- Pandas
- Matplotlib


## How to use
Please run the code in the following order.
 
### Step 1: Modify the "api_keys_tokens.py" file in the *Hypotheses 3 and 4* folder
Update the variables **MyAppToken** and **google_key** by following the instructions below.
```
google_key
```
Insert your Google Maps API key in here.

If you require instructions for setting up a Google Maps API key, please watch this [video](https://www.youtube.com/watch?v=2_HZObVbe-g&t=10s) or read this [documentation](https://developers.google.com/maps/documentation/javascript/get-api-key).
```
MyAppToken
```
Insert your app token provided to you by the City of Melbourne here.

If this is your first time using any of the City of Melbourne APIs, please follow the following instructions for obtaining an App Token.

1) Visit this [website](https://data.melbourne.vic.gov.au/signup) and sign up to create an account.

2) Visit this [link](https://data.melbourne.vic.gov.au/login) to sign in (if necessary).

3) Go to this [link](https://data.melbourne.vic.gov.au/profile/edit/developer_settings) and click **Create New App Token**.

![alt text](https://github.com/James-Akerman/project-one/blob/main/Readme%20images/get%20app%20token.PNG "Create New App Token")

4) Copy your app token.

### Step 2: Go inside the *Hypothesis 1* folder

The **data exploration** and **data analysis** is reported in **Hypotheses 1 - Prabh_analysis.ipynb**.

Results are exported to the folder 'Hypothesis1/Analysis' which includes csv and png files.


1) Run the "Prabh_analysis.ipynb" file.


### Step 3: Go inside the *Hypothesis 2 and 5* folder
#### If **API key is available**, 
add a keys.py file with api_keys variable and run the following file:
**DataGatheringViaAPI.ipynb**
#### else, run the following scripts:
The **data exploration** and wrangling process is reported in **Hypotheses 2 and 5 - data_exploration.ipynb**
- Data Frames needed for Data Analysis have been locally stored in .csv format also to avoid dependency on API keys.

For **data analysis** with illustrations and stats, the report is in **Hypotheses 2 and 5 - DataAnalysis.ipynb**

1) Run the "data_exploration.ipynb" file.

2) Run the "DataAnalysis.ipynb" file.



### Step 4: Go inside the *Hypotheses 3 and 4* folder
1) Run the "Hypotheses 3 and 4 - Data Wrangling.ipynb" file.

2) Run the "Hypotheses 3 and 4 - Analysis.ipynb" file.

