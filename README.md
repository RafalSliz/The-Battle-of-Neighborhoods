# Capstone project "The Battle of Neighborhoods" - Introduction 

<stronh>In this project I will try help people who are looking for renting an apartment in Warsaw, the capital of Poland. If someone is looking to move to Warsaw then they can see in raport:</stronh>
<ul>
<li> Which district has cheaper rent
<li> Someone can choose to live in residential or commercial areas and can see for example which residential districts is better
</ul>

<stronh>Or, if someone already live in one of the 18 districts in Warsaw then will be able to see:</stronh>
<ul>
<li> Whether they are paying more than the average price for their apartment
<li> Whether there are similar districts to theirs with lower rents
</ul>

# Capstone project "The Battle of Neighborhoods" - Data
The data on apartments (district, size, number of rooms, price, price per m2 ) is collected by scraping a local website with apartment listings "olx.pl". In the next step, data about the location of each district was added. Using Foursquare API I collected the closest venues (supermarket, restaurant, park, etc.). After the data collection I was able to run k-means clustering to cluster the districts into residential and commercial areas and visualize all the data on a single choropleth map.
