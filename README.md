# Neighborhood Insight: Qurtubah



## OVERVIEW
This project will examine Qurtubah, a neihborhood in Riyadh city according to the following measures: destinations, diversity, density, street connectivity, and different age groups friendliness. 

### Target Audience
- Someone who's moving to Riyadh and looking for a perfect neighborhood for their needs.
- Someone who's looking for a place to buy or rent.
- Business owners looking to expand their business to a new location.

## PROJECT QUESTIONS  
- How diverse are the destinations in Qurtubah?
- What are the best destinations?
- How walkable is Qurtubah?
- How is the neighborhood family friendly?
- How is rent affected in comparsion to other neighborhoods?

## DATA
data was collected from multiple sources due to accessibility limitaions. the collected data included the following neighborhood amenities:
schools, nurseries, resturants, cafes, malls, pharmacies, clinics, parks, grocery stores, clothing stores, tailors, salons and barber shops, gyms, and mosques.

### sources:
- google maps ( scraped using octoparse & apify ).
- Foursquare API.

### Description 
merging and cleaning the multiple csv files resulted in a dataset of 2145 rows and 7 columns.

| col | Description | Type |
| --- | --- | --- |
| title | name of location | string 
| category | type of place  | string
| dist | district | string
| lat | Latitude | float
| lng | longitude | float
| rating | rating retrieved from google places | float
| num_rating | number of ratings the place recived | int
| price | price range of the place | string



## METHODOLOGY  
- Walkscore will be retrieved using www.walkscore.com API.
- Street network will be retrieved using the Osmnx package.
- Other data of neighborhood amenities will be scraped from google maps with the help of Apify & Octoparse.
- Rent data will be retrieved refrom Aqar

