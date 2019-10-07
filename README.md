# PowerBI-Tutorial
This tutorial outlines the basics of working in **PowerBI Online**. Feel free to work through this tutorial with the sample data about [Super Bowl Game Details](https://github.com/BrockDSL/PowerBI-Tutorial/blob/master/SuperBowlGameDetails.csv) and [Super Bowl Wins by Team](https://github.com/BrockDSL/PowerBI-Tutorial/blob/master/SuperBowlWinsByTeam.csv), or using any dataset you have.  (To download the data, right click the link and "Save link as...")

![DSL Logo](dsl_logo.png)

[@brock_dsl](https://twitter.com/brock_dsl)

### Signing In and Main Page Overview
1. To get to PowerBI Online, open your web browser and head to [the PowerBI website](https://powerbi.microsoft.com/en-us/landing/signin/). From there, it'll prompt you to sign in with your Microsoft account. Use your Brock email and password to log in.
> ![photo1](https://user-images.githubusercontent.com/46492847/53821765-68c77300-3f3c-11e9-8241-f6aee01891c7.png)
2. If you've worked in PowerBI recently, this is where you'll see all of your recent projects. You can favourite certain projects and they'll be shown in the top row along with projects that you work on frequently.
3. You'll also see some Microsoft recommended apps. PowerBI is designed with business numbers in mind including sales reports and  inventory counts, so PowerBI is recommending other business centered apps that are offered by Microsoft.
4. Finally, there are some video tutorials about how to use all of the different versions of PowerBI, including online, desktop, and mobile.

### Get Data
1. Unlike it's Desktop companion, PowerBI Online is slightly limited in where we can retrieve data. The desktop version allows information to be extracted from webpages, social media sites, and plenty of others. We do still have some options for data retrieval in PowerBI Online. Click **Get Data** in the bottom left hand corner of the window to see what these options are.
2. Here, we have the option to create new content, or to explore content from other members of our organization. To create new content, PowerBI Online gives us the option to connect to local files or to connect to an SQL Database. For this example, we're working with a local file, so navigate to the **Files** box under **Create New Content** and click **Get**.
> ![photo2](https://user-images.githubusercontent.com/46492847/53821804-767cf880-3f3c-11e9-949a-08461ef93830.png)
3. From the options here, choose **Local File**, and then open the included exercise file (or any Excel/CSV file you'd like to visualize)
4. From here, we have the option to either **Import Excel Data into PowerBI** or to **Upload the Excel File to PowerBI**. If you wanted to make some edits to your data, you could do this by choosing the option on the right. However, choosing this option means that if you want to visualize the data later, you'll have to create a separate file. We want to create visualizations for our data, so we're going to **choose the option on the left - Import Excel Data into PowerBI**
> ![photo3](https://user-images.githubusercontent.com/46492847/53821835-88f73200-3f3c-11e9-859a-2398f9c63903.png)
5. Now, we should be in report view. This is where we'll start creating visualizations about our data.
> ![photo4](https://user-images.githubusercontent.com/46492847/53821866-96acb780-3f3c-11e9-91fb-decf90323844.png)


### Creating Basic Visualizations in PowerBI
1. Deciding what kind of visualization you want to create really depends on what kinds of discoveries you want to make about your data. You'll find that this becomes easier when you're working with your own data rather than an exercise file. For now, we'll stick to our exercise file - let's say we want to visualize the winning/losing rates of the four football teams who have won the most Super Bowls.
2. In the fields tab, we can see our two datasets: **Super Bowl Game Details** and **Super Bowl Appearances by Team**. For this visualization, we'll use the second of these two datasets.
> ![photo5](https://user-images.githubusercontent.com/46492847/53821894-a6c49700-3f3c-11e9-9925-c0900975aa40.png)
3. Tables are the easiest visualization to create in PowerBI, and it's a nice way to be able to see your data while you're creating more complex visualizations. To create a table, **click on the table icon in the visualizations section**
> ![photo6](https://user-images.githubusercontent.com/46492847/53821915-b348ef80-3f3c-11e9-9474-fc693a53210a.png)
4. Once you've done that, it's as simple as checking all the boxes in your dataset that you want to include in your visualization. You can also drag the values from the dataset into the **values** box on the left, and this can be helpful if you want the columns in your table to be in a specific order.
> ![photo7](https://user-images.githubusercontent.com/46492847/53821947-c22fa200-3f3c-11e9-8380-373f26990670.png)
5. If you're including numerical values in your table, you may notice a total appearing at the bottom of each individual column. Having totals can be helpful when working with certain kinds of numerical data, but if it's unnecessary for the kind of data you're working with you can remove the total by **clicking on the drop-down menu for the value in the Values box -> check Don't Summarize**
> ![photo8](https://user-images.githubusercontent.com/46492847/53821979-cfe52780-3f3c-11e9-99da-2763c8eeed08.png)
6. In our example, PowerBI is organizing our table by teams in alphabetical order. If we want the table to be sorted differently, we can **click on the arrow in the column we want to sort our table from**
> ![photo9](https://user-images.githubusercontent.com/46492847/53827036-2015b700-3f48-11e9-9ad1-6042852a5782.png)
7. Now, let's create a pie chart. For this example, we're going to visualize the Win/Loss rate of the four teams in the NFL who have won the most Super Bowls. We'll start with the New England Patriots.
8.  First, **choose the pie chart visualization from the visualizations section**. For this visualization, we're concerned with the wins and losses of each team, so we'll **drag the Wins value and the Losses value into the Values box on the left**
> ![photo10](https://user-images.githubusercontent.com/46492847/53827050-2c017900-3f48-11e9-8765-a1dc4b22babd.png)
9. Right now, we're seeing a pie chart of all of the wins and losses across each Super Bowl. If you hover over each section, you'll see that there are 53 wins and 53 losses - makes sense, since there have been 53 Super Bowls to date and somebody has won or lost each time. However, we're only interested in the Patriots right now, so we'll add a filter.
10. Adding a filter is as simple as adding a value. Since we're interested in filtering by team, **drag the Team value into the Visual Level Filters section on the left**. To only look at one team, **open the drop-down menu in the Team filter**. Here, you can either scroll down until you find the team you're looking for, or you can search for it directly.
> ![photo11](https://user-images.githubusercontent.com/46492847/53827076-3a4f9500-3f48-11e9-9567-21d12f6c3640.png)
11. Once you've checked the box next to the New England Patriots, you should see that your pie chart shows 6 wins and 5 losses - which corresponds to the data in the table we created earlier.

### Formatting Visuals in PowerBI
1. Now that we have our visuals, it's time to make them look a bit nicer. In the visualizations tab, **choose the icon in the middle that looks like a roller paint brush**. This is where you can format all of your visualizations.
> ![photo12](https://user-images.githubusercontent.com/46492847/53827096-4b000b00-3f48-11e9-9c6e-01b75adf1d6f.png)
2. Every visualization will have different formatting options, but there are some options that appear consistently. The first of these is the **Legend**. The legend is turned off in our pie chart visualization, but if you turn it on you can see that it just shows that the lighter blue represents Wins and the darker blue represents Losses. A legend can be helpful if you have a lot of values in a pie chart, but it doesn't really apply to this one, so it can be left turned off.
> ![photo13](https://user-images.githubusercontent.com/46492847/53827104-55baa000-3f48-11e9-92c2-c438f292afa3.png)
3. Next, we have **data colours**. This can be fun, especially when you're visualizing data about football teams. You can create custom colours, or choose colours from a pre-set theme. The sky is the limit!
> ![photo14](https://user-images.githubusercontent.com/46492847/53827119-60753500-3f48-11e9-8ebe-61e972aff7e3.png)
4. **Detail Labels** is a formatting option that's specific to pie charts - this is where we can decide what we want the labels outside of our chart to say. The default setting is **Category**, but you can change yours to include the number of wins and losses, the percentage of the total, or any combination of these labels. You can also change the font type, size, and colour, as well as the placement of the detail labels. 
> ![photo15](https://user-images.githubusercontent.com/46492847/53827133-69fe9d00-3f48-11e9-806a-4aedc496061a.png)

### Map Visualizations
1. Maps can be a great way to tell a story and answer questions about your data. There are a few different ways to create maps in PowerBI. Bing maps is the easiest to use, and is the most applicable for most map visualizations. You can also use a filled map, or ArcGIS maps for PowerBI. ArcGIS maps are a really cool tool, but be aware of the fact that if you want to share your report to the web or PowerPoint that it won't work because the software isn't compatible. For this example, we'll use Bing Maps, and we'll be creating our visualization from the **Super Bowl Game Details** dataset.
2. **Select the Maps visualization**. From here, it's as simple as clicking and dragging the values into the visualizations section. It's important here to use applicable data, or the map won't be accurate. For example, if you were to drag the **Game** value into the **Location** box in the values section, the map will attempt to recognize the roman numerals as latitude and longitude, leading to an inaccurate visual. For this example, we'll **drag the State value into the Location section**. You should be able to see a bubble in every state that has hosted a Super Bowl.
> ![photo16](https://user-images.githubusercontent.com/46492847/53827168-797de600-3f48-11e9-9f7b-868a7bb8a391.png)
3. If you want to see which state has hosted the most games, **drag the Game value into the Size section**. Now, the bubbles change size based on how many games have been hosted in each state. Hovering over the bubbles will show you the exact values in each state.
> ![photo17](https://user-images.githubusercontent.com/46492847/53827183-84387b00-3f48-11e9-98e3-78b30e908b37.png)
4. Next, we'll drag the **Winning Team value into the Legend section**. The bubbles have now turned into little pie charts to represent all the teams that have won a Super Bowl in each state.
> ![photo18](https://user-images.githubusercontent.com/46492847/53827217-94e8f100-3f48-11e9-83eb-c953301dfe43.png)
5. Like we did with our pie charts, we can use filters to look at individual teams. Create a filter based on the **Winning Team** value, and search for the Pittsburgh Steelers. Check the box, and you should only see points on the map where the Steelers are the winning team. You should see that Florida has seen three of the Steeler's six victories, while all of the other states only have one.

### Line Graphs and Trendlines
1. Line graphs are another way to analyze data and answer questions about our dataset. For this graph, we're going to look at Super Bowl attendance. 
2. To create a line graph, **select the line chart visualization** from the visualizations section
> ![photo19](https://user-images.githubusercontent.com/46492847/53827232-9dd9c280-3f48-11e9-842b-5f57a5e00e44.png)
3. Just as we've done before, click and drag the values we want from the fields pane into the values sections. For this visual, drag the **Date** value into the **Axis** section, and the **Attendance** value into the **Values** section.
4. Now we have a line graph! At first glance, it can be a bit difficult to spot any trends on a plot with so many outliers and ups and downs, so we can add a **trendline** to make it a bit easier to read.
5. To add a trendline, **navigate to the icon that looks like a magnifying glass over a graph**. This is the Analytics tab, and you can add all sorts of lines to better point out trends in your data. You won't have this option for every visualization you create (like our map visualization, for example), but since it applies here we'll add a trendline by **revealing the drop-down menu for Trend Line, and clicking Add**
> ![photo20](https://user-images.githubusercontent.com/46492847/53827259-aa5e1b00-3f48-11e9-9319-183e47595b4f.png)
6. Now we can see that there is an overall downward trend in Super Bowl attendance, meaning fewer and fewer fans are going to the games. There could be several reasons for this, and we can use PowerBI to theorize these reasons and analyze the significant outliers at the top of our graph. 

### Learn More
To learn more about using PowerBI, check out our [second PowerBI tutorial](https://brockdsl.github.io/PowerBI-2.0/) online, or get in touch with us by sending an email to **dsl@brocku.ca** or following us on [twitter](https://twitter.com/brock_dsl) 
