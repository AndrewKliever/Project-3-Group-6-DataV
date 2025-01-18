# Project-3-Group-6-DataV

1.13.25 - @11:49 pm zillow finally won and i decided to swtich gears slightly. i was able to locate a list of avg states per state on redfin and scrap the table contents
into a csv file of the top 20 cities in each state. i still need to figure out how to drop the "-" marks as dropna isnt catching it.
this seams like a decent dataset as it has 1000 rows and gives you an insight into which states have a high avg price, price per sqft and days on market. we can also do i heat map of states with low medium and high avgs in each are.

let me know you thoughts and the "new project file" and "redfin csv" are current so check them out. 

https://www.redfin.com/state/Texas

1.17.25 - @11:34pm 
so i finally finished the new scraping method, I could not get it to run really fast like Andrew's original, since I had to use geopy to get the coordinates at the same time that it is scraping the data, so the process to view the map if someone new would be running it would be: run the jupyter notebook .ipynb first to scrape the data and create the csv into the 'Data' folder, this process unfortunately takes about 10 minutes or so.
next, use vs-code to run the .py folder, and that creates the html for the map. once it is created, then run the html as normal and it creates the map.
the way to read the map: the map is a layered map, base layer is the heat map, and on the top right it has a drop down with check boxes that can be utilized to check avg price listing per state, avg price per sqr foot, and avg days on market, all per state, if all these are checked off, the heat map is present, and basically the heat map indicates the more pricier real estate overall in those areas. 
Of course yall dont have to run anything as everything is already saved, but i think someone should do a practice run to check for functionality, be sure to 'pip install geopy', and 'folium' before running anything. 
let me know if you all would like to me to change anything
-jesus

1.18.25 @6:43pm  
Using Jesus' code as a base, i created an interactive bubble map. - YSaul
