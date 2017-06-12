# Create Visualizations II

## Table and Matrix
If you grab a categorical field or text field and drag that on to the canvas, you'll get a table of results by default. This is because it's a textual data, and the easiest visualization is a table, you can scroll up and down through them and by default it's shorted alphabetically. But we can also short it just clicking on the column name, for example by Revenue:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/12.PNG)

You can also reorder the columns. If you want to see the CountryZip between Manufacturer and Revenue, you can do it moving them from the *Values* field

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/13.PNG)

Another tabular visualization is the matrix. Here you can put different categories on the columns, as well as on the rows. Create a Matrix with the Manufacturer on the Rows, the Year on Columns and Units in the Values Field. That should look like this:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/14.PNG)

Now we've got all of the units sold for each manufacturer, sorted by year. Notice that a new columns and a new row had been added, with the total units of each year and Manufacturer respectively.

## Scatter Chart
A common visualization is the Scatter Chart. Let's take a look on how we can create it. We are going to compare the revenue and the units. So first of all, click on the Scatter Plot Visualization:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/15.PNG)

Then select the axis: *Revenue* on the X Axis and *Unis* in the Y one. You haven't finished the chart yet, now you'll have a dot in the middle of the chart because you are aggregating your total revenue and your total unit sales across all of your data. You need to specify another field in the details, for example the *Segment*. So now we can see for example, that the *Convenience* has the highest revenue or that the productivity sells the highest number of units.
We can also add a new dimension to our chart, putting the *Manufacturer* field in the legend. By doing this, we'll see a bubble for each manufacturer.

Now we are going to add a new dimension and colours for our bubbles. Put the *Category* field in the *Legend* and *Segment* again in the *Size*. We should have a chart like this:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/16.PNG)

There is one more thing that we can put in the chart. We can animate it over the time. Drag the *Year* field and drop it in the *Play Axis*.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/17.PNG)

Now we have different animated charts for each year and showing the evolution of the revenue and the units in throughout years.
If you click in one of the bubbles, you can see all of the previous movements of that bubble. For example, go to 2006 an click in a random bubble. You'll see a trace line of the previous revenues and units.Then click in the play button and the trace will continue.


So as you can see, scatter plot is a good way to compare three different measures on your X and Y axis, but you can also track that and animate it over the time.


## Gauge and cards
The visualizations we've looked at, have tipically been used to compare values across different categories. However, if you're building a report, sometimes you want to just show a single KPI or a single metric, so you can track that see how it changes over time. We have a few different visuals for that. Gauge is a really good one if you want to show progress towards a particular target, for example out total revenue. Select the Gauge visualization.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/18.PNG)

Now click on the revenue. By default, the maximum value of the revenue will be the double of the total. Here we have a variety of options to configure, in the *Format* tab. For instance, we can set a target value from the *Gauge* Axis. We can also set a maximum. Put your own values and you'll get a chart like this:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/19.PNG)

Another useful tool, is the card visualization, which shows us an stressed number inside a framework. For instance, we'll represent the revenue. Select the *Card Visualization* and the *Revenue*:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/20.PNG)

We can also have a KPI visuals that can be really useful for showing this sort of information. We'll see an indicator and also a trend over the last few time periods, about how that number has changed. Click on the *KPI* visualization and the the *Units* Field:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/21.PNG)


## Adding custom visualizations
As you have seen, there are a lot of different visualizations that we can use, such as bar charts, pie charts, maps or treemaps. But we can also import new ones or even create our own visualizations. Check out the custom [visuals gallery](https://app.powerbi.com/visuals/) of Power BI.

Select and download a visualization. For instance, the Chord chart. Then go to the Power BI Service and import it from the three dots next to the last chart of the list.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/22.PNG)


Select the .pbiviz file that you have just downloaded and you can start trying it. For example, you can represent the flow of *Revenue* between *Province* and *Segment*.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%202%20-%20Visualizations%20II/Images/24.PNG)

[Create your first dashboard in Module 3](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%203%20-%20Dashboard%20and%20sharing%20data)