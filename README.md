# Coursera_Capstone_Project
Project objective - Leverage the Foursquare API to solve a problem of your choice


The problem I have chosen to solve for this capstone is the following :


Based on the user's input of venue categories, return candidate neighborhoods that contain venues belonging to the categories of interest to the users.

It is easy to search on the web for a specific venue, one venue category or a certain neighborhood and obtain information.

However, what if a person wants to eat Chinese for lunch, watch a movie, go to a café, browse for music at a store, have Italian for dinner and finish the night at a bar, all in the same neighborhood so as to minimize distance traveled ?

What is proposed here is to solve this problem of obtaining candidate neighborhoods based on venue categories of interest, by leveraging the Foursquare API.

This type of solution could be of interest to :
- tourists that may want to book a hotel in proximity of certain venue categories
- a person who would like to buy an appartment in the city of Paris in poximity of specif venue categories (a gym for example)
- a local Parisien who wants to minimize the distance traveled and find all he or she needs in 1 neighborhood

-----------------------------------------------

But first, out of curiosity, I would like to cluster the neighborhoods in Paris using k-means.


-----------------------------------------------
The Dataset:

The starting dataset will be obtained from data.gouv.fr and is composed of the neighborhoods in Paris and certain characteristics such as their geographical coordinates, the surface area, and the district to which they belong.

As specified, Foursquare.com shall also be leveraged to obtain location data mainly concerning the venues in Paris.
