This project is part of the udacity “Data Scientist” nanodegree program.
Analyzed data is Airbnb data from 2016 in Seattle USA.

Project motivation:
The motivation of the project is to analyze the data regarding prices inside the various neighborhoods, occupancy rates as well as to develop a linear regression model for the prediction of prices of new airbnb-listings.

Installation:
The following python-packages were used in the project:
- Tensorflow
- math
- pandas
- numpy
- matplotlib

File Descriptions:
- airbnb-project.ipynb: Jupiter notebook file including the code.
- calendar.csv: calendar data including availability of airbnbs, dates on a daily basis and airbnb prices
- listings.csv: listings data including unique listings of airbnbs with accomodation properties, reviews and various other values
- reviews.csv: review data including customer reviews for airbnbs

Results:
- Prices in the various neighborhoods of Seattle vary from 66 USD to 251 USD with a mean of 129 USD.
- Yearly differences of the mean over all neighborhoods of 121 UDS to 152 USD were observed.
- Occupancy rates vary from from 2.6 % to 54 % with a mean of 31 %.
- Occupancy rates can vary by around 20% when observing the mean over all neighbourhoods throughout the year
- The linear regression model is unsufficient to predict prices of new airbnb-listings with a r-squared of 0.638

A more detailed analysis of the results is given in the following article: 
https://medium.com/@savo.asanin/where-to-stay-in-seattle-a-data-scientists-guide-for-your-next-stay-53ecdcf13482
