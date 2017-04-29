# Outbrain-Click-Prediction
<hr>

![screen shot 2017-04-28 at 11 06 49 pm](https://cloud.githubusercontent.com/assets/21116708/25552417/6fe17abc-2c67-11e7-8e0a-5714286a572f.png)

# Deliverables
<hr>

Project Proposal Video : https://www.youtube.com/watch?v=IeKPIaOxPJI

RShiny Deployed Link: https://outbrainproject.shinyapps.io/WebOutBrain/

Tableau Online link: https://us-east-1.online.tableau.com/#/site/ads_outbrain_finalproject/workbooks

Final Report document: ADS_Final_Project_Report_Team8.docx

DockerHub Link : : https://hub.docker.com/r/sweta/outbrain_prediction/

Demo Link: 

Tools used: R, R-shiny for web devolpment, Python, Plotly and Tableau for analysis, Docker, Luigi, IBM Data Science, Microsoft Azure

# Note
In Exploratory analysis we have used plotly in offline mode, hence the graph will not be visible unless the code is run.
The Report has all the graph images along with the explanation.


## PROBLEM STATEMENT:
<hr>

Millions of user use social network for surfing, visiting countless websites and clicking on countless ads/recommendations  on these website.
Knowing what the users are interested in and what the users are using in real world would be of great significance for future recommendations used by marketing team to attract potential users
as well as ad placements and real time bidding
Predicting the likelihood of users clicking on a particular content
Ranking the recommendations in each group by decreasing predicted likelihood of being clicked


* Below is a screenshot of rest API that will predict advertisement ids for an individual display id.

![click probability](https://cloud.githubusercontent.com/assets/21116708/25552442/c4d45670-2c67-11e7-9f97-e2ccf68b36d7.JPG)


# Exploratory Analysis

![screen shot 2017-04-28 at 11 16 21 pm](https://cloud.githubusercontent.com/assets/21116708/25552472/c0150d2c-2c68-11e7-9c9e-53e411ab7090.png)

### Observations
* Maximum percentage of clicks were made through mobile phones, followed by desktop and then tablets. Mainly because: 

* App Availability: the app is available that is available on desktop is now present on model too.

* Convenience:  Games or social networking apps frequently serve as a way to pass the time while on the subway commuting home or in a cab or surfing net. This directly reflects the increase in uses of mobile devices    

