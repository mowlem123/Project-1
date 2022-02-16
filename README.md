# Project 1
## Hungry for some Michelin
### Contributed by Alex, Abib, Amy

For our project, we've decided to go outside of the Fintech Industry and examine something that someone not in the tech industry could relate to. 
In our project we reviewed Michelin star restaurants in the San Francisco and New York city areas. 
Our project is to uncover locations of these restaurants, as well as find them by cuisine, and how many stars they have based on a one through five factor. 
These are the questions we asked and what we found to answer them.

## Questions and Answers

### Which city has the higher concentration of Michlein Starred restaurants? and by which cuisine type?

  To start using our data we collected, we first had to clean it. We used methods we learned in class. We wrote code for a bar chart using px.bar. Then we used city for x and start levels for Y. This bar chart we mained has each city so there are two bars. In each bar, there are 1, 2, and 3 stars for each bar. This makes it easy to determine how many stars each city has. We can also see the total through this bar chart as well. The answer is going to be New York City. 

### What is the cuisine type of each restaurant?

  To look for the cuisine type of each restaurant, we cleaned the data then made a dataframe. This way, the data would be easier to see. We dropped the data that we didn’t need to focus on for this question using the .drop function. From here, we can see the cuisine type of each. This makes a list of each restaurant and presents each cuisine type next to the name of the restaurant. This chart also provides the zip code, city, and price level you're going to be paying.
  
### What is the total number of restaurants that have Michelin stars in each city, sorted by each star rating?

  For this, we started by combining information for each city together. We used the term all_star_counts as a name to put all information together. From here, it was totaled. This also makes a list. On this list, we can see the city name, 1, 2, and 3 star amounts. We dropped all other columns to make the data nice and neat. We did this using the .drop function to make it as neat as possible.
  
### What is the variation between categories? (by price, rating, location)

  To look at this, we made maps for each city. We joined all the information per city together, to then make a scatter mapbox. This shows where the restaurant is and what the rating is as well. The maps make it easy to see location and zip code. The restaurants are represented as dots on the map. The color of the dot represents the amount of stars each restaurant has.
  
## Results

  From the information we collected, we concluded that as the stars increase, the variety of cuisines decrease. 1 star restaurants across both cities have the highest diversity of cuisines. When we hit three star level restaurants, it appeared that asian, contemporary, and seafood are the only cuisines that have three stars. 
