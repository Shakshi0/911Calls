# 911_Calls
This repository contains a comprehensive analysis of 911 Calla Data from Pennsylvania's Montgomery County, focusing on exploring and visualizing key insights using both Python (for processing) and Excel (for analysis).

Table of Content
- Introduction
- DataSet
- Data Collection
- Creating New Features and Analysis
- Conclusion

The data is provided from Kaggle and it contains the following fields:
- lat : String variable, Latitude
- lng: String variable, Longitude
- desc: String variable, Description of the Emergency Call
- zip: String variable, Zipcode
- title: String variable, Title
- timeStamp: String variable, YYYY-MM-DD HH:MM:SS
- twp: String variable, Township
- addr: String variable, Address
- e: String variable, Dummy variable 

Note: There were couple erros in lines 40-42 due to missing data, but I was able to fix it with Pandas for the data processing. 

Conclusion

Overall, most calls were for EMS responses. Notably, the second most frequent 911 call was for Vehicle Accidents, comprising nearly 30% of total calls. As anticipated, there was greater variability in call volume throughout the day, with EMS and Traffic experiencing both higher call volumes and more fluctuation compared to Fire, particularly during daytime hours.
