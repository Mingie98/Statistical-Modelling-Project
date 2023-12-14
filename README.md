# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The aim of this project is to construct a statistical model to uncover insights regarding the correlation between the number of bicycles at each station in a specific area and the attributes of nearby Points of Interest.

## Process

### Step 1: Data Acquisition from CityBikes API
Establish a connection with the CityBikes API to gather data about bike stations' latitude, longitude, and bike count in the selected location.

### Step 2: Data Retrieval from Foursquare API
Connect to the Foursquare API to obtain details on restaurants and coffee/tea shops associated with the bike stations identified in the first step.

### Step 3: Gathering Data via Yelp API
Utilize the Yelp API to collect similar information on restaurants and coffee/tea shops as in step 2.

### Step 4: Data Integration
Combine the data collected from steps 1, 2, and 3 into a unified DataFrame.

### Step 5: Data Visualization
Employ data visualization techniques to examine and understand the gathered data.

### Step 6: Database Creation in SQLite3
Develop an SQLite3 database for storing the compiled data.

### Step 7: Regression Model Development
Construct a regression model to analyze the relationship between the number of bikes at each station and nearby places of interest, specifically restaurants and coffee/tea shops.

### Step 8: Analysis and Reporting of Findings
Analyze the model's results and prepare a report to present the key findings.

## Results
Based on the analysis from the regression model, the results indicate a minimal correlation between the selected variables and the dependent variable, which is the number of available bikes. This lack of strong association may be influenced by the current winter season in Montreal, where the Bixi bikes are stationed, as bicycle usage typically decreases during colder months. The low R-squared value and the non-significant F-statistic in both the Foursquare and Yelp models further support the conclusion of a weak relationship between the variables studied and bike availability.

## Challenges 
Encountered multiple technical issues thoughout the project that were all resolved eventually.

## Future Goals
Since the models did not successfully predict the intended variable, exploring alternative focal points could be beneficial to see if they yield different results.
