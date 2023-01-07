# Exploratory data analyses - by Jan Korinek
Hello and welcome. 

In this repository you can find exploratory data analyses performed as part of the final capstones within *IBM Data Science* and *Enterprise Workflow specializations*.

## Exploratory data analysis for revenue predicting service

The main goal of the `EDA-Revenue_Predicting_Service.ipynb` analysis is to assimilate the business scenario and articulate testable hypotheses and state the ideal data to address the business opportunity and clarify the rationale for needing specific data. To investigate the relationship between the relevant data, the target and the business metric the *Python* script was created to extract relevant data from multiple data sources and automating the process of data ingestion.

All findings are described in `Report_EDA-Revenue_Predicting_Service.pdf` including pair plots and correlation matrixes visualizations of the features and business metrics with emphasis on the strongest pairs. Time-dependency visualization of the features with overall summarization and conclusions is covered as well.

## Lifestyle aspects analysis of the cities in two different geographical locations

The `City_Lifestyle_Aspect_Analysis.ipynb` and it's report focuses on analysis of lifestyle aspects of the cities in two different geographical locations. 

Idea behind the study is to compare city location suitability to maintain healthy lifestyle with help of *Python* tools used in *Data Science* area. Emphasis is to minimize time necessary for routine activities like traveling to job or shopping and dedicate it more to fitness activities in gyms or in parks or spend more time on cultural events. 

The first part of the study is focused on import districts data and processing them to visualize on *Folium* map. Next, city districts are extended about venues data via *Foursquare API* and prepared for clustering process. Third part is focused on usage of *K-Means* algorithm where all venues are clustered. Finally, the last step is focusing on extraction of districts from clusters which are matching the best to defined criteria. 

In-depth description of particular steps, results discussion and conclusions you can find in `Report-City_Lifestyle_Aspect_Analysis.pdf`.

