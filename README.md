
# Inverted IPL Analytics 22

Analytics of Indian Premier League data till 2022.
This dashboard has been built with an intention of keeping the dashboard as vanilla as possible. Every element of the dashboard design is kept as simple as possible. Analytics has been inverted giving opposite data for each request made though the slicer.

## Preview:

![Picture](PICTURE.PNG)

[Download the pbix file](Rainfax_July.pbix)

## Process

### Data Cleaning and Transformation

•	Cleaning the excel sheet by renaming it as required and replacing the null values with median values.

•	Changing the data type of the columns as required.

•	Ensured that the character set of all the columns is uniform and accurate.

### Data Visualization

•	Loaded two sheets to power BI, Made all the necessary transformation and then loaded the data.

•	Connected the two sheets and joined it through a common column as key.

•	Created a combination of five dashboards, built a navigation bar for it and connected it using bookmarks and action.

•	**Overview Page** – Built cards by using measures created using selected value, Built different graphs for Runs by player, Games by player, Boundaries by player and wickets by player for the entire league irrespective of the team and filtered using top N filtering.

•	**North Page** – Built two slicers, one for the teams filtered for north and another dropdown slicer for player. Built cards for team and player selected using selected value. Built different graphs using top N filter. The graphs are inverted for the bowlers as it shows the wickets and balls bowled against the selected team rather than for the selected team. Card fetched the maximum of the five selected through a measure written using calculate. 

•	**South Page** - Built two slicers, one for the teams filtered for south and another dropdown slicer for player. Built cards for team and player selected using selected value. Built different graphs using top N filter. The graphs are inverted for the bowlers as it shows the wickets and balls bowled against the selected team rather than for the selected team. Card fetched the maximum of the five selected through a measure written using calculate. 

•	**Other Page** - Built two slicers, one for the teams filtered for all the other teams and another dropdown slicer for player. Built cards for team and player selected using selected value. Built different graphs using top N filter. The graphs are inverted for the bowlers as it shows the wickets and balls bowled against the selected team rather than for the selected team. Card fetched the maximum of the five selected through a measure written using calculate. 

•	**Team Page** – Built a slicer for teams, and cards for selected team using selected value, extra runs, Batsman runs, Balls faced and total faced.

## Conclusion & Insights

•	**Overview Page** – Player with the highest score, games, boundaries and wickets. Top 5 Run getters, games played, boundaries scored and wickets taken along with the value for each of the top five.

•	**North Page** – Top 5 Runs and Top 5 Balls played by a particular player for a particular team in the north region. Top 5 Wickets and top 5 balls bowled against the selected team by a particular player if selected.

•	**South Page** – Top 5 Runs and Top 5 Balls played by a particular player for a particular team in the south region. Top 5 Wickets and top 5 balls bowled against the selected team by a particular player if selected.

•	**Other Page** – Top 5 Runs and Top 5 Balls played by a particular player for a particular team in other regions. Top 5 Wickets and top 5 balls bowled against the selected team by a particular player if selected.

•	**Team Page** – Total runs, Batsman runs, extra runs and balls faced by each team as a whole as selected from the slicer. Every slicer in all the pages have been enabled for multiple selections.

## Inspiration

Always wanted to work on something related to sports so decided to work on IPL Stats. Wanted to make it a little different so built it as a combination of straight and inverted Analytics.


