# Project1

## Is Airbnb profitable business?

### To understand Airbnb business model better we've analyzed L.A. City market to find out:

* What would be the average night rate for a room/apartment in LA?
* What variables determine the price of the night rate in Airbnb? (Pendiente Alfonso)
* How big is LA Airbnb market?
* Which part of the city is more profitable?
* Are they changing their rates according to the month/season?
* Is price influenced by location or reviews?

Data preparation
Challenge:
Gather information from a web site with no API support
CSV files were separated per month
No "month" column included
Some columns like price hadn't int or float values but strings
Solution
Build a script to download every csv file according to url directory: http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/data/listings.csv.gz
Rename CSV files according file downloaded
Build a loop script to insert "month" column inside each file and apply a replace/regex function to convert price column from string to float