The formal problem statement entails employing data
and visual analytics techniques to predict crime hotspots
and assign risk scores to different neighborhoods in Atlanta. The project aims to utilize machine learning algorithms and time series modeling to analyze crime data
from 2009 to 2020, cluster crimes geographically, assign
risk scores based on crime severity, and forecast future
risk scores. The end goal is to visualize these risk scores
on a choropleth map, facilitating smarter policing strategies.
We have broken down our project into the following
steps -
• Basic exploration of the data (EDA) and sanity
checks to ensure data consistency. This would also
include identifying missing values/outliers and understanding the distribution of crime types.

• Post obtaining geographical clusters, we assigned a
risk score for each cluster based on the crime type.
This was done based on the severity of the crime
(eg: 10 for Homicide and 1 for Petty Theft etc).
Thus we obtained a risk score for each cluster for
each month/year.
• We used time series modeling techniques like Exponential Smoothing to predict the risk score for
future periods based on the existing data for each
geographical cluster.
• Then we visualized this result on a choropleth map
of Atlanta showing each geographical cluster, risk
score associated with it, and the top 5 types of
crime in that area for different time periods.
This risk score can then be utilized for citizen safety
and for smart policing where we can send more police
officers to areas that have a higher risk score.
Technologies/Algorithms Used: Python, k-means,
GMM, Exponential Smoothing, Plotly, Dash
