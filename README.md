# Pedestrian activity in the City of Melbourne before and during COVID-19
 Please run the code in the following order.
 
## Step 1: Modify the "api_keys_tokens.py" file in the *Hypotheses 3 and 4* folder
Update the variables **MyAppToken** and **google_key** by following the instructions below.

##### google_key
Insert your Google Maps API key in here.

If you require instructions for setting up a Google Maps API key, please watch this [video](https://www.youtube.com/watch?v=2_HZObVbe-g&t=10s) or read this [documentation](https://developers.google.com/maps/documentation/javascript/get-api-key).

##### MyAppToken
Insert your app token provided to you by the City of Melbourne here.

If this is your first time using any of the City of Melbourne APIs, please follow the following instructions for obtaining an App Token.

1) Visit this [website](https://data.melbourne.vic.gov.au/signup) and sign up to create an account.

2) Visit this [link](https://data.melbourne.vic.gov.au/login) to sign in (if necessary).

3) Go to this [link](https://data.melbourne.vic.gov.au/profile/edit/developer_settings) and click **Create New App Token**.

![alt text](https://github.com/James-Akerman/project-one/blob/main/Readme%20images/get%20app%20token.PNG "Create New App Token")

4) Copy your app token.

## Step 2: Go inside the *Hypothesis 1* folder

**Hypothesis One:** The overall pedestrian activity in the City of Melbourne had decreased since March 2020 when the first lockdown happened in Melbourne.

The **data exploration** and **data analysis** is reported in **Hypotheses 1 - Prabh_analysis.ipynb**.

Results are exported to the folder 'Hypothesis1/Analysis' which includes csv and png files.


1) Run the "Prabh_analysis.ipynb" file.


## Step 3: Go inside the *Hypothesis 2 and 5* folder


**Hypothesis Two:** Pedestrian activity had increased after the first lockdown, but not to pre-pandemic levels (average of August 2019 to February 2020).

**Hypothesis Five:** Pedestrian activity increases as the number of Victorian full-time workers increases.

### If **API key is available**, 
add a keys.py file with api_keys variable and run the following file:
**DataGatheringViaAPI.ipynb**
### else, run the following scripts:
The **data exploration** and wrangling process is reported in **Hypotheses 2 and 5 - data_exploration.ipynb**
- Data Frames needed for Data Analysis have been locally stored in .csv format also to avoid dependency on API keys.

For **data analysis** with illustrations and stats, the report is in **Hypotheses 2 and 5 - DataAnalysis.ipynb**

1) Run the "data_exploration.ipynb" file.

2) Run the "DataAnalysis.ipynb" file.



## Step 4: Go inside the *Hypotheses 3 and 4* folder

**Hypothesis Three:** Pedestrian activity would increase as JobKeeper claims increased.

**Hypothesis Four:** Pedestrian activity would decrease after JobKeeper was tapered.


1) Run the "Hypotheses 3 and 4 - Data Wrangling.ipynb" file.

2) Run the "Hypotheses 3 and 4 - Analysis.ipynb" file.

