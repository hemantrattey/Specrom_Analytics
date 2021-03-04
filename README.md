# Specrom_Analytics_Task

This repo is for a task provided by Specrom Analytics.

The aim is to perform exploratory data analysis on the dataset provided. Geocoding is done using geopy and Nominatim to get the latitude and longitude and use them to plot on a map using Plotly where I have fixed the scope to USA only. 

**Analysis :**  The total number of stores are 59 and Texas has the most number of footlocker stores with 9 followed by California with 8. There are also 2 stores which don't have a state value i.e. the last 2 rows of the data provided. The names of these stores are *Las Catalinas Mall* and *Plaza Carolina*. But since we only needed top 5 states by stores, hence they didn't affect it. 

**Libraries :** Make sure to install the following libraries using ```pip install <library name>```

	1. pandas
	2. numpy
	3. plotly
	4. seaborn
	5. matplotlib

***Please note :*** The Geopy and Nominatim has a RateLimit. So as to not exceed this again and again, I saved the dataframe after extracting latitude and longitude values to a csv file called ```cleaned.csv```. 

Also, Github doesnot render the Plotly maps hence I have added the PNG as a seperate file. 