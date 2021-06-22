# NAMUSAZ

NAMUS, the National Missing and Unidentified Persons System, is a national database for identifying missing persons. It was created as a means for law enforcement to help identify crime victims and unclaimed bodies. My idea was to try and and map missing persons to an interactive map that could be filtered in different ways. I won't lie, I still haven't fully conceptualized this project, though I have a data file of missing persons for Arizona, which is where I decided to focus this initial project. 

Issues I've run into:
  The CVS file of missing persons has about 900+ rows. Each person on it is identified by their last known location, both county and in most cases city. However, within each county there are a large number of UNKNOWNS when it comes to city. I can bin them by county, but givin Arizona only has around 10 counties I don't feel that information will be very useful. I'm not really sure how best to aggregate the data to be honest. I think I am possibly going to seperate the unknown city into a seperate list organized by county, but any suggeestions will be helpful. I will try and upload the CSV file so people can take a look. 
