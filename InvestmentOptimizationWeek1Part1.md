
![Investment%20Optimization.JPG](attachment:Investment%20Optimization.JPG)

Problem Statement:

Social scientists might be interested in understanding how people in cities react to ever-changing businesses, perhaps towards the study of gentrification. Across many domains, it’s helpful to understand the dynamics between businesses and the people affected by them. However, relying on costly and infrequent government census services to provide demographic information for large, changing cities quickly becomes unfeasible.
Location-based social media might help us address this problem. Many companies (think Yelp, Twitter, Foursquare) have real-time data about user check-ins, preferences, and their local businesses. The complete data set for addressing the problem was created by compiling FourSquare check-in data along with census data for New York City census tracts.

Background:

Investment and marketing strategies of enterprises can be optimized by studying the wealth of local demographics.This will help the enterprises to better cater their products and services towards the individuals who live there.
For evaluation purposes, we need to structure the problem even more, so we split the data into quartiles, 4 balanced classes that could be used for prediction: 0–25% (poorest), 25–50%, 50–75%, and 75–100% (wealthiest).
At this point, we have a clear classification task: for each census tract, predict median household income quartiles.

How data will solve the problem? :

To address the above problem two separate data sources were used:
i> NYC Census Data: demographic data for 2,167 census tracts in New York City based on 2015 American Community Survey 5-year estimates.
ii>FourSquare Check-in Data in NYC: 227,428 check-ins collected from 12 April 2012 to 16 February 2013.

If we assume that high amounts of activity are positively correlated with higher income then the total checkins for a given census tract might be representative of a region’s wealth. Similarly, one might assume that frequencies of check-ins at different types of businesses  might hold different signals for wealth. Given the timestamps of each check-in, we can also associate activity during different days of the week or times of the day with different levels of wealth.

Finally, we can validate some of these assumptions by visualizing our data with heatmaps.
Location-based social media might help us address this problem. Many companies (think Yelp, Twitter, Foursquare) have real-time data about user check-ins, preferences, and their local businesses. New dataset was created by compiling FourSquare check-in data along with census data for New York City census tracts. With this new dataset, we did quite a bit of exploration to manually construct features and apply model wealth as a function of those features.
