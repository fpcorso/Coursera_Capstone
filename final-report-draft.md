# Identifying best locations for new pizza place in Gainesville, FL

## Introduction
Gainesville, FL is Florida's 15th largest city with 134,945 people within the city and 295,266 in the overall area and it has grown 8% between 2010 and 2020. As it continues to grow, we know there will be opportunities for new restaraunts including new pizza places.

To identify the best potential areas for our new pizza place, we will analyze the different parts of the city to identify what areas would have the least competition for a pizza place. However, a challenge with Gainesville is that the population is spread out into several dense areas and many less dense areas.

As such, we will want to identify areas that have low competition for a pizza place but also have enough people in the area to support a new establishment.

## Data
Based on our problem, we will look at:
1. All the restaraunts in the area
2. All the pizza restaraunts in the area
3. The number of other businesses in the area

We will be dividing Gainesville up into equal areas to define our neighborhoods. Then, using the Google Maps API, we will generate the geographical coordinates for our neighborhoods.

From there, we will use the FourSquare API to generate the lists of businesses wthin each neighborhood as well as the specific restaraunts.
