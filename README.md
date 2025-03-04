# Project
# We researched U.S. honey bee productions, more specifically how the number of honey producing colonines, production of those colonies, and value of that production changed over the course of the past five years.  
#
# Data Source
# Link to our data source: https://usda.library.cornell.edu/concern/publications/hd76s004z?locale=en
# Our data source is the website for U.S. Department of Agriculture's Economics, Statistics and Market Information System honey publication. The files contain in the website show the annual reports (by each state and the overall U.S.) of the number of colonies producing honey, yield per colony, honey production, honey stocks, average price per pound of honey, value of production, and price by color.
# The data types presented by this data source is string, integer, and floating point in a table format.
# The restrictions found with this data type is since the tables are looking at statistics for each U.S. state, when colonies produce honey in more than one state as bees are not restricted to state lines, the sourse counted those colonies as apart of each state. 
# One of the biggest pros of this data sourse, is that it is easily accessable and shows up when researching honey bee production in the U.S. Another pro is that each years' data is given in a variety of formats including PDF, TXT, and ZIP format with CSV. Within each file this source gives clear explanations of the data, how certain issues with the data were resolved, and small write-ups of the statistics shown. 
#
# Data Pulling
# For the data pulling, we downloaded the latest five available data publications (the years 2019, 2020, 2021, 2022, and 2023) as ZIP files. Each years' ZIP file contained CSV files for all individual tables avaible. We uploaded only the tables containing the data points we were using into our GitHub repository. 
#
# Data Cleaning
# We chose to not use the tables on "Honey Price by Color Class," "Income and Expenditures," "Queen, Package, and Nuc Prices Paid," "Apiary Workers," or "Reliability of Honey Estimates" as they were not relevent to our analysis. 
# Our data source stated that when colonies produce honey in more than one state, they counted those colonies as apart of both states. This could make the numbers for the yield per colony lower than they actually were. Since the yield per colony may not have been entirely accurate, we chose to remove that from the data set. The data source clarified that the total production would not be impacted by this, so we chose use that data instead. 
# As well as omitting "Yield per Colony" from our data, we also chose to not use the stocks held by production companies data colomn and average price per pound of honey as these numbers were not the focus of our analysis.
#
# Visualizations
![Alt text](producing_colonies.png)
![Alt text](production.png)
![Alt text](value.png)
# We chose to use line graphs for our visualizations since our data looks at change over time and we wanted to represent the trends seen.
# We focused on the five most recent data publications from our data source, which were the years 2019, 2020, 2021, 2022, and 2023. 
# In those publications we chose to focus on the number of honey producing colonies, the honey production by those colonies, and the value of the production.
#
# Storytelling/Insight
# Honey bees are important for agricultire and the environment. Honey bees pollinate over 130 species of fruits, nuts, and vegetables in the United States every year. Honey bees are also important to human health as honey has been consumed by humans for thousands of years for their claimed antioxidant, antimicrobial, anti-inflammatory, and anticancer properties.
# Climate, weather conditions, and region have a large impact on honey bee productions. Flowers need moisture to bloom and when plants are stressed, they do not produce necatar. Without that nectar, bees cannot produce honey. 
# As the number of honey producing colonies decreases, annual honey production tends to decreases as well. Honey bees are also facing pressures from herbicides and land use. 
# While there is a general downward trend in annual honey production, in 2023 United States honey production went up 11 percent from 2022. Our data source did not clarify a reason for this, but after some research, we found it was likely due to rainier weather in 2023 allowing for more flower bloom. 
# Honey production closely impacts the value of the production. As seen with the raise in honey production in 2023, the value of production went down for that year.  
# Scaling up the data we used would have resulted in clearer long-term trends in each of these categories and could benefit this data analysis. 
# It was also important to our data that we remove one column of the data specifically to ensure our data was the most accurate. 
