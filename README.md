# AirBNB-case-Study
This is the data of amsterdam and following results were found after decriptive analysis.

What Each Column Means:

'room_id': Every Listing has its unique Room id
'survey_id': the survey number airbnb has done
'host_id': Every host has its unique host id but several hosts have multiple listings
'room_type': 3 types of rooms are available ( Entire apt/house , Private room, shared room)
'neighborhood': 23 neighborhoods location data is available in this data sets
'reviews': Number of reviews given for each listings
'overall_satisfaction': ratings given by guests
'accommodates': number of people listing can accomodate
'bedrooms': number of bedroom in the listing ( 0 means studio apartment )
'price': price of each of the listing for in night in Euro
'name': name of the listings
'last_modified': last date when the datafield was edited
'latitude': latitude of the location
'longitude': longitude of the location
'location: place where it is situated


===============================================================================

 2780 hosts have multiple listings and host id : 48703385 has maximum number of listing 93.
Survey id is the survey number airbnb has done so it is same for every record
and is insignificant in this case so it was dropped.

===============================================================================

 Shared roomtype was very less as compared to others so it was dropped as it didnt effect much.

===============================================================================
There are Total 23 Neighbourhoods.
De Baarsjes / Oud West  has the most number of listings : 3280 whereas 
Westpoort has Least number of listings: 15

===============================================================================

room_id :4289398
host_id : 6333496
room_type: Entire home/apt
price : 359.0
accommodates :  4
bedrooms :2.0
neighborhood: De Pijp / Rivierenbuurt
Has the maximun number of Reviews 532

===============================================================================
There are 7697 listings with 5 overall satisfaction rating and 5721 listings
with 0 overall satisfaction. 

===============================================================================

Almost 90% of the houses accomodate 2,3 and 4 people

=========================================================

Almost 90% of the houses are Either studio or with 1,2 or 3 bedrooms

==============================================================================

Prices of the houses range from 12 euros to 6000 euros

==============================================================================


There is Positive corelation of 0.44 between bedrooms and price hence it may 
affect price positively.

This means that as the number of bedrooms increase the price is likely to 
increase.

==============================================================================

Reviews does not show any significant relationship with price.

==============================================================================

Overall Satisfaction does not show any significant relationship with price.

==============================================================================

There is Positive corelation of 0.5 between accommodates and price hence it may 
affect price positively

This means that as the capacity of the guests increase the price is likely to 
increase.

==============================================================================

There is Positive corelation of 0.7 between listings in a neighborhood and 
median price in that neighborhood hence it may affect price positively

==============================================================================

Thank you. 
Will be Updating soon with the price prediction model.
