# Assignment 3 + 4: Critique by Design

## Step 1: Finding a data visualization

I decided to use Economic Research Service's visualization on food expenditure series to complete this assignment. [Source](https://www.ers.usda.gov/data-products/chart-gallery/gallery/chart-detail/?chartId=99193)

The reason why I chose this visualization is that I am interested in seeing some data on COVID to learn more about how the trends of a particular subject change as a result. After I came across this visualization, I knew I wanted to do it primarily because I am also interested in learning about food sales. To be honest, I  considered other graphics that are related to food such as grocery sales breakdown or sales of food consumption by age, but those ones did not have a formal database. Considering my interests and the availability of data, I thought that this visualization would be the best for me. Additionally, this visualization has a lot of space for improvement! 

<p align="center">
  <img src="Images/usda-food.png" width = "400">
</p>

To briefly summarize, this graph shows the total food sales and breaks it down to food at home and food away from home from January 2019 to June 2020. The data from this graph can be found by going to this [link](https://www.ers.usda.gov/data-products/food-expenditure-series/) and clicking the "Monthly sales of food, with taxes and tips, for all purchases".

## Step 2: Critiquing the data visualization

To critique this visualization, we will be using Stephen Few's Data Visualization Effectiveness Profile. The seven criteria include usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. Below is a chart to describe what the scores of a good chart is versus what the ERS graph score

<img align="right" src="Images/radar.png" width = "450">

### Usefulness

The graph shows information from 2019 and 2020 to point out the change in customer behavior after the pandemic started. It could be useful but takes quite a while to comprehend it.  

### Completeness

There is a lot of data included in the information; there's information regarding food at home and food away from home. It also shows the total sale of food each year so that the audience can understand how the numbers are changing altogether. 

### Perceptibility

Because of how the data is presented in a double bar graph, users are forced to make harder comparisons between each category since the bars are not connected. In a sense, the audience has to alternate between reading food information away from home and food at home, which can be difficult to perceive. Additionally, the colors are distracting. While users can easily see the total sales in the green line, it is more challenging to make the comparison between the other information.

### Truthfulness

The reason this graph is a 9 and not a 10 is because of the number labels. Notice that in January 2019, the food at home and food away from home are both labeled as 64 billion dollars. However, the length of the chart does not match. The reason behind this is because of rounding numbers, but the illustrator did not make that clear.  

### Intuitiveness

This graph is not easily understood because it takes a while to digest. There is too much information on the graph and the visualization used impairs the reader from grasping the content quickly. Some users have a difficult time interpreting double bar charts and making comparisons from that. 

### Aesthetics

The color scheme and visualization type are terrible because the colors are distracting and the bars increase cognitive overload. On top of that, there are number labels on every data point, which takes up the white space. The arrows at the bottom are unnecessary. 

### Engagement

All things considered, this graph would most likely not draw audience into the data because of the lack of aesthetics, intuiveness, and perceptability. 

### What I would do differently

- I would change the color scheme
- I would change the type of visualization used. I might even make two visualizations instead (one to present food at home versus food away from home and another to present total food sales).
- I would omit the number labels and only focus on important points (perhaps the difference from April 2019 to April 2020).
- I would take out the arrows on the year.
- I would rearrange the graphed values, lines, and legend so that they are closer to one another.

## Step 3: Wireframing a solution

First, I started by drawing a few ideas on paper. This is a really rough sketch to get a sense of what I want to make when I actually do wireframe it. Then I transferred these drawings into Figma. Below are the four ideas that I focused on (note: the data presentation is not accurate and is just to give a rough idea of what the graphs will like): 

### 1. Bar chart

I am interested in this graph because I thought highlighting the net sales of food between the categories would be interesting because it seems to change a lot during the COVID period. Originally it seems that the difference between food away from home and food at home is not too large although food away from home sales is slightly higher. However, from March 2020, there seems to be a huge switch. From all four visualizations, I like this one the best because of how aesthetic looks and how the information comes across easily. Some things that I wasn't sure about is whether this graph is intuitive to other people and whether the titles are clear. 

<p align="center">
  <img src="Images/food-net-diff.png" width = "400">
</p>

### 2. Stacked chart

The reason that I used this visualization is to restructure the information that is presented in the original graph. This way, users will still be able to see the total food sales information without doing mental math. I also decided to only highlight certain points, in this case, just April 2019 and April 2020. I got this inspiration from the original graph, where they discussed changes in annual sales spending. Personally, I think this is significantly better than the original graph, considering that it delivers the same information. However, there are too many things going on for a user to quickly grasp this is less than a minute. 

<p align="center">
  <img src="Images/food-stacked.png" width = "400">
</p>

### 3. Line chart

This line chart is probably the most straightforward way I can imagine this graph. I highlighted the areas between the two lines so that it would be even more obvious. I believe that having the shading inside would bring more attention to the audience's eyes. I also decided to include an additional caption to highlight the difference between the two lines to emphasize my point. This line chart would probably be my second favorite just because of the simplicity but also the effectiveness of the graph. However, one thing I was uncertain about is how I should mark the dates. Should I just mark the year change, or should I mark something else and craft a different story? 

<p align="center">
  <img src="Images/food-line.png" width = "400">
</p>

### 4. 100% Stacked chart

I was curious about how the stacked chart would turn out and whether this would help see the trends of how the food at home versus food away from home changes because now you see the values in percentage and not raw values. That way, you are comparing these numbers to the total sales and help users gauge a better idea of the ratio. After seeing the graph, I feel like it is hard to read the graph and make the comparison still. A better way might be rotating the axis so that the percentage is on the x-axis and the year on the y-axis. The reason why I believe this would help is primarily that comparing percentages vertically and reading information backward is difficult.

<p align="center">
  <img src="Images/food-100.png" width = "400">
</p>

## Step 4: Testing the solution

Now that I have some idea about what I want my graphs to look like, I interviewed two people to test out my solution. For anonymity purposes, I will refer to my interviewees as YK and ZW. I expored 1 and 3 more deeply because I thought those two fit the data visualization effectiveness profile the best. 

### 1. 

Both YK and ZW thought that the graph looks really clean and aesthetically pleasing. They agreed that using colors to help point out the bars on the FAH side makes the information pop. They also liked the division line between 2019 and 2020. 

YK said, "it took me a moment to understand what the net difference in sales is. It might be because I am tired, but it doesn't come to me right away. After I thought it through, I got the concept."

YK also suggested that I rearrange some of the titles. For instance, putting FAFH and FAH to the right makes it seem as if there is a different axis to look at. Instead, she recommended that I put it closer to the top of each side.

YK was also confused by the term "net difference" and the label because she thought net loss is negative. She suggested that I simplify it and say difference instead. ZW said something similar and suggested that I put down the word sales such as "net difference of sales" to make it more obvious what I am comparing. He mentioned that even though I already included this piece of information in the title, it does not hurt to reiterate such a strong point. 

ZW said that "it is easy to interpret, but it could be even easier". He recommended that I change the y-axis title to just be the equation FAFH - FAH because that is the definition of difference. 

On top of that, ZW mentioned that altering the y-axis eliminates the need to write FAFH and FAH on the right-hand side. 

Another recommendation that ZW provided is to label when COVID took place or an important date. 

### 3. 

A question that I asked both of my interviewees is whether having the shaded areas between the line helps the audience see the information better. Both of them agreed, in which ZW commented that the shaded areas "help bring your attention towards the big gaps" and IK stated that the swap was done nicely. 

IK thought that nothing is confusing in this graph. However, she commented on things that she thought would help improve the visualization. For instance, I should consider changing the frequency of the date to month instead of a quarter because there is not a lot going on anyways. She said, "I am lazy, it doesn’t say the month directly so I have to think about it more."

ZW pointed out that the caption of the net difference might be better as a subtitle. At the same time, he said to make sure to be descriptive and informative because I "should not repeat the information when creating a new text box." Because of how large the gap is, the audience is immediately drawn to that so putting it as a text next to it is somewhat useless. 

Another minor note that ZW had is the gridline on the row side is unnecessary to see the trend. Because it does not add value, there is no need to include it. 

ZW mentioned how he like the fact that the legend extends from the line and that the line and words are in the same color. "It's as if I just continued reading the line to read the titles of the key. This makes it easier for me to see."

All in all, both YK and ZW like this visualization the best. They agree that this visualization is the most straightforward and delivers the point the best. At the same time, it is simple but not too simple that it looks empty. 

### Ranking the net sales bar chart and the sales line chart

We will now revisit the data critique method and evaluate which of the two graphs performs better in the respective categories. 

- Usefulness: *line chart* because users can understand information quicker and the comparisons and absolute numbers are shown
- Completeness: *line chart* because the bar chart only shows the difference between the two values. It does not tell the full story of how the overall trend is
- Perceptibility: *bar chart* because the difference between the two categories are more clear. The information is also emphasized with the use of colors
- Truthfulness: Because this is also a prototype and a rough estimate of different curves, this does not matter.
- Intuitiveness: *line chart* because the bar chart using sales difference is more difficult to understand. People understand the face value better than second calculations.
- Aesthetics: *bar chart* because of the good balance between content and white space.
- Engagement: *line chart* because considering all of the above, the line chart delivers the point, tells a story, and still looks aesthetically appealing.

### Overall thoughts

Based on the feedback and the critique, I decided to go with V3 for my final visualization because it seems to match the criteria of a good visualization per the critique method. Moving forward, I took some of the feedback that I received and incorporated them into my final product.

I made the following changes:

- Change the color scheme
- Change the wording of the titles
- Add another reference line to tell a story about COVID
- Adjust the y-axis title position
- Move the text to the subtitle place instead 
- Take out grid lines
- Add source

Here is the final prototype, and in the next step, you will see my final visualization on Tableau! 

<p align="center">
  <img src="Images/final.png" width = "600">
</p>

## Step 5: Building my solution

<div class='tableauPlaceholder' id='viz1644287959234' style='position: relative'><object class='tableauViz'  style='display:none;'>
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
  <param name='embed_code_version' value='3' /> 
  <param name='site_root' value='' />
  <param name='name' value='Assignment34_16442870976310&#47;Sheet1' />
  <param name='tabs' value='no' /><param name='toolbar' value='yes' />
  <param name='animate_transition' value='yes' />
  <param name='display_static_image' value='yes' />
  <param name='display_spinner' value='yes' />
  <param name='display_overlay' value='yes' />
  <param name='display_count' value='yes' />
  <param name='language' value='en-US' />
  <param name='filter' value='publish=yes' />
  </object>
</div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644287959234');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

While this is not everything I wanted, I tried my best to get the final visualization to as similar as my final prototype. I tried different tactics to get the shading in the two lines. Many of the tutorials that I used involved having the opacity be 100%, which meant I could not achieve the color scheme that I wanted. Below is a photo of how it looks. 

<p align="center">
  <img src="Images/area.png" width = "400">
</p>

I had to make a trade-off decision considering the previous graph and this image. Do I want to get the type of spending filled in, or do I prefer a less saturated graph? Obviously, being able to change the opacity of the area part would have been the most optimal choice, but between the two options I could choose from, I thought that doing a simple line graph was the best. I went back to ask my interviewees, and they agreed that the white space is sufficient. It still communicates the same problem with less cognitive burden for the reader. Additionally, with the width size that I used for the lines are easily spotted, and users can still interpret the white space as the gap. 



