Negros_Occidental_Cities:
	I got this dataset by extracting the list of cities in Negros Occidental from the Philippines Statistics Authority
	website, and at the same time using wikipedia in order to get their decimal coordinates. And after getting the 
	name of the cities and their corresponding coordinates I turn them into a csv by googlesheets. After that I import the 
	csv to my jupyter notebook and process them further in order to get the detailed informations (latitude, longitude
	venues and each of their respective latitudes and longitudes), after getting their detailed information, I create 
	a bar chart to see which city have the most venues, and from their onwards make my comprehensive analysis about
	that city.
	
Bacolod City Article:
	This is a text file which I will later use for my word cloud, my word cloud will help me to gain additional insights
	in order reinforce my decision at the conclusion.
	

negros_cities_with_venues (extracted via foursquare API):
	This dataset will be my main data for analysis, I will use a k-means algorithm in order to cluster them
	and after clustering them I will see which cities have similarities and have the most number of venues, 
	after that, I will make a pie chart in order to see what percentage each venue contributes to the total
	count, after that I will map each venue by using folium and decide on what type of business that I would 
	want and where should I place it in order to maximize profits.
