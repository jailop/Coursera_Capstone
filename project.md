Project description:  
**Where to go on Washington D.C.  
using the Foursquare API**

By Jaime Lopez  
Mar. 24, 2019

**A. Problem description**

Washington D.C. has many interesting things to be known. Users would like to
receive advise where to go on Washington D.C., based in some preferences like
coffees, museums, shopping, etc. Using the Foursquare API, a search for
neighborhoods to visit will be built. This application will work clustering and
ranking neighborhoods based in similarity with user preferences on things to do.
Moreover, for the more similar neighborhoods, the application will show
recommendation of top venues to go while visiting a neighborhood.

**B. Data**

Data sources:

- Neighborhood Labels  
Link: <https://opendata.dc.gov/datasets/neighborhood-labels>  
The dataset contains neighborhood labels provided by the DC Office of Planning (DCOP).
- Foursquare API (explore and venues)  
Link: <https://developer.foursquare.com/>

Data processing:

- From “Neighborhood Labels”, label and location data for each Washington D.C.
  neighborhood will be obtained.
- Using location for each neighborhood, a list of venues will be obtained. A
  category-record will be created for each neighborhood counting how many venues
  are by category.
- An user input area will created.  Users could pick among different categories
  to get recommendation on which neighborhoods to visit.
- Using clustering, the more similar user preferences neighborhoods will
  recommended to visit.
- For each neighborhood recommended to visit, a list of top venues will be
  gotten from the Foursquare API based on user category preferences.

