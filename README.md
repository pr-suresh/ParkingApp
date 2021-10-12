# Park Smart Parking App

## Abstract

The goal of this project is to help the client build an app "Park Smart" which can be used by someone who is trying to find a free public parking spot in NYC. I used datasets from the website NYC Open data.

## Design
According to New York Safety Council, Parking tickets are pretty much a way of life in New York City.They keep drivers on their toes and generate lots of revenue for the city. The cost of a parking ticket in New York City varies greatly, based on the violation code and how many times a driver has made the same offense. Fees also vary based on location in the city, especially in Manhattan, 96th Street and below. To prevent drivers from paying a heavy parking violation fee, Park Smart app can help them find other parking options.

## Impact Hypothesis
We hypothesize that by identifying locations and times that have been reporting parking violations, the Park Smart app can help the user avoid a Parking violation ticket and help find an alternative low risk option.

## Data Science Solution paths
Based on the address/location data in the Parking violations data set and the fines imposed on it, the app can be built using any of these 3 ideas:

Build a multi class classification model using the Fine amount as Target with 99 classes to determine how much fine amount  location/time will result in a fine or not and suggest alternate parking locations nearby the area where such a risk is less.

Build a regression model to determine the Fine amount as Target and use that to decide whether the Parking spot is a good choice or not.

Determine the latitude and longitude of the addresses where the violations are high and perform clustering on the geographical data.

Measure of success

How well the model can predict a good spot for parking without fines.

Amount of money spent by the same person in Parking Violations before and after using the app should be considerably low. 

## Assumptions and Risks
There may not be any cost effective alternative at a particular location and they may end up paying a huge amount in either tickets or finding paid parking garages which are expensive and may not translate to saving any money by the user.

## Data
There are about 2200 rows in the final data set after cleaning. 

For the Parking fines information, I used the data set from NYC open data that includes the fees for the different Parking Violation codes and merged it with the Parking Violations data set to figure out the Fine incurred by each violation.

## Tools

Excel/Google Sheets for data cleaning, aggregation and analysis

Tableau for plotting and interactive visualizations

## Communication
In addition to the slides and visuals shared here, the Tableau dashboard  for the Park Smart mobile app can be found here.
