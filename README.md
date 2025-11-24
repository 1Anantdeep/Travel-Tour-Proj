# Travel-Tour-Proj
Capstone Project for soloving over tourisum 
Created By: 
-  Atharshan Kennedy
-  Uzer Hamza Khan
-  Caroline Kaurungai
-  Anantdeep Kaur
-  Pratik Patel

Project is an application that will guide users to lower crowded areas.

Website built with Stream Lit & deployed through Heroku and can be accessed through here:
-  https://capstone-travel-and-tourism-3aff3f983f6c.herokuapp.com/
To run locally either fork then pull to remote or just download project:
-  Then rigth click in the folder with the app.py file and click CMD and type in:
  -  streamlit run app.py or python -m streamlit run app.py
  -  local host Website will appear in browser   
    
Provides:
-  Suggestions for different travel dayss to a location
-  Recommendations to another location with lower crowd levels
-  Translate suggestions and recommendations to user specifiyied language
-  A crowd forecast/historical window of the selected location
-  Itineraries/filter options for fine tuning location options

Currently only two city's that being NewZealand Auckland & Ireland Dublin are avaiable.
More will be added in the future.

Data sources and API's:
- Uses data from SerpAPI for future fligth paths and prices
- Uses weather data from Open Meto Weather API for forecasting model
- Uses OpenAI API for translating the suggestions and recommendations to specfiyed language
- Support data manually created:
  - Used for location data of POI's
  - Used for Airport data for creating the fligth data set  
- Main data sets for NewZealand Auckland & Ireland Dublin goverment websites for crowd data
  - https://www.hotcity.co.nz/city-centre/results-and-statistics/pedestrian-counts
  - https://data.smartdublin.ie/dataset/dublin-city-centre-footfall-counters
  - All data sets here have simliar structure to them, any future data will need same or similar structure to them
     
