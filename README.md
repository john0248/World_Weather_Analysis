# World Weather Analysis

Our employer an online travel agency has asked us to generate latitude and longitude data and show weather data related to the corresponding city.  Some of the tools used for this challenge were Jupyter Notebook, Pandas Library, Googles Maps, CitiPy, Python Requests, APIs, and JSON Traversals. We applied analyses, visualizations, statistical skills, and utilized API data retrieval to complete three separate deliverables. 

## Results

### Deliverable 1:
The first deliverable was to generate 2000 random latitudes (lat) and longitudes (lng).  Once we were able to generate the lat and lng, we used the CitiPy module to figure out the nearest city.  Our API calls accessed weather data from OpenWeathermap.org.  After all the weather data was collected, we create a dataframe to store the data and wrote the dataframe to a CSV file for later use.  Please find below a snapshot of the TAIL of the dataframe.   I choose the tail to document how many cities were generated from the 2000 original lat/lng list. Since the lat/lng generated randomly, this dataframe will change each time the jupyter notebook is ran.   

![](Weather_Database/Weather_Dataframe_tail.png)

### Deliverable 2:
In deliverable 1 we created a dataframe with numerous hotels and weather information.  That information is useful but not friendly to use with a customer is mostly concerned about weather during their vacation.  In the second deliverable we created a user input box allowing the customer to determine what kind of temperature they find suitable during their vacation.  After the min and max temperature ranges are determine we can execute the rest of the code to generate a dynamic map.  The map generated uses Google maps and includes a pop-up marker.  See below for an example of our Google Map:

![](Vacation_Search/WeatherPy_vacation_map.png)

### Deliverable 3:




