# Pedestrian activity in the City of Melbourne before and during COVID-19
 Please run the code in the following order

To avoid reliance on API key during key, dataframe copies have been stored in .csv files.
Each hypothesis is addressed in a different folder.
Data Analysis files are stored in each folder for hypothesis related statistical and visual analysis.


### Next Go inside the directory Hypotheses 3 and 4
#### Step 1: Modify the "api_keys_tokens.py" file

##### Google Maps API Key
Insert your Google Maps API key in here.
If you require instructions for setting up a Google Maps API key, please watch this [video](https://www.youtube.com/watch?v=2_HZObVbe-g&t=10s) or reading this [documentation](https://developers.google.com/maps/documentation/javascript/get-api-key)


##### MyAppToken
Insert your app token provided to you by the City of Melbourne here.

If this is your first time using any of the City of Melbourne APIs, please follow the following instructions for obtaining an App Token.

1) Visit this [website](https://data.melbourne.vic.gov.au/signup) and sign up to create an account.

2) Visit this [link](https://data.melbourne.vic.gov.au/login) to sign in (if necessary).

3) Go to this [link](https://data.melbourne.vic.gov.au/profile/edit/developer_settings) and click **Create New App Token**

![alt text](https://github.com/James-Akerman/project-one/blob/main/Readme%20images/get%20app%20token.PNG "Create New App Token")

4) Copy your app token

#### Step 2: Run the Hypotheses 3 and 4 - Data Wrangling.ipynb file

#### Step 3: Run the Hypotheses 3 and 4 - Analysis.ipynb file

### Hypothesis 2 and 5
**Hypothesis Two:** Pedestrian activity had increased after the first lockdown, but not to pre-pandemic levels (average of August 2019 to February 2020).

**Hypothesis Five:** Pedestrian activity increases as the number of Victorian full-time workers increases.

The data exploration and wrangling process is reported in data_exploration.ipynb
- Data Frames needed for Data Analysis have been locally stored in .csv format also to avoid dependency on API keys.
For data analysis with illustrations and stats, the report is in DataAnalysis.ipynb


**Conclusion:**

There was an average drop of 87% in pedestrian activity at various locations in Melbourne during covid19.

Since the first lockdown, the pedestrian activity has still not returned to pre-lockdown which might suggest a new trend.

The negative correlation found in most postcodes may be because businesses were struggling to pay their workers as the number of pedestrians and hence customers decreased.

No statistically conclusive evidence of pedestrian numbers decreasing after JobKeeper. Apparent decline maybe due to chance.

Full time workers were still active during years affected by lockdown. 


