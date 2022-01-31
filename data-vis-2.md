# Data Visualization #2: Visualizing Government Debt (1/30)

## Part 1

### Government Debt Bar Chart

<iframe src="https://data.oecd.org/chart/6Bl8" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Bl8" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>

Source: OECD (2022), General government debt (indicator). doi: 10.1787/a0528cc2-en (Accessed on 30 January 2022)

## Part 2

### Grid of Line Charts

<div class="flourish-embed flourish-chart" data-src="visualisation/8565011"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### The Third Data Visualization

For this part of the assignment, I wanted to take the time to explore Flourish and the different graphs available on the platform. Hence, I decided to create two graphs to test out Flourish as well as the techniques. The show graphs I chose to illustrate are both line graphs, with the second one displaying ranking. The main reason I adopted a line chart is that both year and debt-to-GDP ratios are continuous. Unlike the previous grid of line charts, since these lines are all combined in one graph, it will be easier for users to compare different points. I will explore my design decisions in each section separately!  

#### Line Chart

<div class="flourish-embed flourish-chart" data-src="visualisation/8566874"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

For the line chart, I decided that it would be best to allow users to choose five countries they want to see at a time. That way, users will not be crowded with information and will still see the trend. To help make this information more evident, I replaced the default text with my own, specifying that they can enter up to 5 country abbreviations in the input box. 

I also created an input called average, in which I found the average of all 35 countries at different points in time. That way, users will see the average OECD debt-to-GDP ratio to get a better sense of the overall trend. 

Unlike a typical graph, I decided to place the x-axis at the top instead because I thought that users would be able to read the lines faster. I also labeled the colors of the lines right next to the end to reduce cognitive burden. Because I knew that some of the data points did not start or end at the same point, having a dot at the end of the line would make it easier for readers to notice.

In terms of color, I went with the default palette, Flourish 1, primarily because cool tones are obvious to see and are not harsh on the eyes. 

A couple of things that I would like to improve include the following:

- Greying out not selected lines 
- Removing line connecting the debt-to-GDP ratio line with the countries' name (while it is small, it is unnecessary)
- Making AVG line always there regardless of the five countries the user chooses


#### Race Chart

<div class="flourish-embed flourish-chart" data-src="visualisation/8567310"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

While I was researching what types of graphs are available on Flourish, I saw examples of people creating a race chart, which inspired me to do one. Although this visualization is more for the style and not as much effectiveness, it was still a good experience for me to get accustomed to the program. 

Since I wanted to create a particular type of graph but was not certain on how to display the information, the start was the most challenging part of this assignment. I thought about grouping everything together by region and finding an average debt-to-GDP ratio, but I was curious if there was a way to show all the information. I also knew I wanted to create some filters, but there was a lot to digest.

To begin, I color-coded the countries based on region. I originally grouped the 35 countries based on the continent, but I soon realized there were more countries in Europe than other continents. Therefore, I broke it down into smaller regions within Europe to make the color distinction and distribution better. Then, the next challenge was choosing colors to code each category. I decided to go with lighter colors for groups with a lot of data because it will make it less difficult to see other lines. Had a group like Central Europe been neon pink, users would be distracted by the intensity and the frequency of the lines. Anyways, I chose five main colors (red for Asia, orange for the Americas, purple for Australia, grey for Europe, and blue for Average). Then, for Europe, I chose different shades of grey to distinguish the European regions.

Similar to the previous graph where I included a dot at the end of each line, I thought that it would be a good idea, considering the dot used to help showcase the rank. In addition to just using a colored dot, I decided to experiment by adding an image of the flag so that users will be able to read the data faster (they do not need to hover on the line to find out what the country is). That said, I am worried that this creates more distractions. 

Unlike the previous graph, I added a specific title and caption because I thought that the rank says a lot about which country is doing well or not doing well. I also took out the y-axis grids because those lines would distract readers. Last but not least, I used a log scale instead of a linear scale because of how clumped together the data was in the middle. By implementing a log scale, the data are less focused on a specific area and are more evenly distributed. 

There are a lot of things that I want to improve for the graph, however, currently, I do not have the skills to implement my ideas. Here are some of the things I thought of:

- Specifying how many countries are shown
- Creating different colors for the ALL graph versus the group graph (currently, the color code is based on the region, but within the filtered data, I want each country to have its color to make the lines more distinct)
- Grouping data together in the ALL graph depending on region and having separate lines for different countries when region filter is selected
- Choosing color that better fits the graph
- Reducing the number of tickers

## Final Thoughts on Different Methods of Visualization 

Without a doubt, you choose different visualizations depending on what information you want to showcase. In those three graphs, they were all forms of a line chart: the grid having multiple graphs within one visualization, the line chart having one graph with multiple lines, and the race chart having two graphs that display similar information. While the grid chart intends to compare different lines, the latter options do a better job since you can see the comparisons on the same graph instead of mentally mapping where each one would go. That said, grid charts would be better for users who want to see an overall trend and look at each data separately since you can see more details within each graph. The third graph is essentially the second graph with the addition of a rank feature. Since the debt-to-GDP ratio can be compared, it will be interesting to see which countries are in the lead or are under-developing without seeing the raw values. However, the third graph had more information compared to the second graph, which meant readers will take longer to digest everything. All in all, there are benefits and drawbacks of choosing each graph; it depends on what pieces of information you want to highlight.

