# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
- Get the number of free bikes in each of all bike sharing stations in Vancouver
- Discover the number of bars near each bike station
- Investigate the relationship between number of free bikes and other variables

## Process

### Step 1
#### Collecting Data from 3 different APIs: 
- CityBikes
- Foursquare
- Yelp
#### EDA
#### Joining Tables and data visualization

### Step 2
Data Modeling

## Results
I found that Yelp API in this case is more complete than foursquare. Besides, the distribution of yelp data were more normal than that of foursquare. So I continued my project with Yelp data. In the statistical model, I identified 4 independent variables and one dependent one (number of free bikes). Using OLS and Backward selection method, I realized that I should only keep average reviews. There is a correlation between that and number of free bikes, though not a strong correlation.

## Challenges 
- Getting the data from Yelp API, as the Authorization was not successful at first. Because, my code was missing a word. I must have included the word 'Bearer' before my Api key. My initial assumption was that the codes are similar with 4square, but it was not in fact. Finally I could understand my mistake and collect the data!
- When I was trying to iterate through the different locations to gather the information about bars, in the middle of processing my formula gave an error. Then I had to figure out to write some more lines of code to solve it. (I used try except in my formula)
- Another challange was choosing the right data from the Yelp and 4square APIs as there were lots of information there.
- Lastly, finding the best model that can be a good fit

## Future Goals
- Going through the data collection process again and collect different sets of data and POIs. For example , instead of choosing bars, I would choose nearby parks, coffee shops, schools or universities. 
- Choosing a different city and looking at the differences/ similarities.
- Doing the strech part