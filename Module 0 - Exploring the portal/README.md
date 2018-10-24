# Module - 0 Exploring the portal
**Objective:** In this module we will see all the capabilities provided by the Power BI Service. The aim is to get some insights about them and highlight the most important ones. Power BI Service enable us to create reports and dashboards, and share them with people inside or outside the organization.

## The Dashboard

Once we have signed in, we need to familiarize with the controls of the portal. Expand the left-hand side menu by clicking in the three strips button, below 6 (look at the figure). These are main features:

1) Left-hand side menu
2) Icons pane
3) Q&A box
4) Help buttons
5) Title of the pane
6) Office 365 indicator
7) Button for the main page of Power BI
8) Some additional actions

 ![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/theDashboard.png)


## Left-hand side menu
Here we can find all of the sections of the Power BI Service. What can they do for us?

* Favorites: we can add dashboards, reports and databases in that section, to enable quick access to our most used resources.
* Recent: here you can find the last activity of the chosen workspace.
* Applications: we won't focus on this section, but it is used to packetize Power BI resources, such as dashboards, reports or data, and sharing them to a customer's Power BI Service.
* Shared with me: all of the content shared in your company, related to Power BI, is in this blade.
* Workspaces: The content in Power BI is organized in workspaces. This enables you to classify all of your works, for example in departments, or in teams.


 ![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/workspaces.png)



## Create a workspace
If you have started this lab with other colleagues, you can create a unique workspace for all of you, and share every new content in the same workspace. It is recommended to start using the sharing options because it's one of the most powerful features of Power BI.

So go to the left-hand side menu, click on *Workspaces* and select *Create app workspace*. A new blade will appear on the right hand. Write a name group and an ID. Remember that the ID must be unique. Invite colleagues to the dashboard and click *Save*.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/creatingWorkspace.png)
 
After that, set the workspace to private in order to share the content only with the people that you want. In the next question, click on the option that enables the other participants of the dashboard to not only view the content, but edit it as well.
And finally add the members of your team. Right after that, a new workshop appears in the left-hand side of the portal

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/createdWorkspace.png)

Invited members of this workshop will receive an e-mail with a link to the new workshop.

### Datasets
Here are the datasets that you can import to the Power BI Service, or connect from other sources. If you want to learn more about other ways of importing data to Power BI, go [here](https://powerbi.microsoft.com/en-us/documentation/powerbi-service-get-data/).

So now we are going to import a Dataset. Click the button *Get Data*.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/getData.png)


Here we have several options:
* My organization: In this section we will find all of the Power BI content, shared only by members of my organization.
* Services: several content packs are offered here, with datasets, reports and dashboards. These packs are prearranged, so for instance it's possible to download the GitHub Service, enter you account and you'll have a full dashboard with graphs and statistics about the use of your GitHub, with commits, activity, contributions, etc... There is no need on creating a new report or dashboard, the service provides all of it for you.
* Files: you can upload Excel, CSV or Power BI Desktop files. **Choose this option**.
* Databases: you can connect to your Azure SQL Database, Azure SQL Data Warehouse, SQL Server Analysis Services or Spark on Azure HDInsight.


![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/getDataOptions.png)


Click again in Local File and select the *Canada sales data.xlsx* file that you can find in the folder of this module. Finally, click on *Import Excel into Power BI*. The other option is just for visualizing the Excel in a Workbook, within the Power BI Service. 

### Reports

This is the tool used for creating our visualizations. We can separate them in one or more pages with charts, graphs, treemaps and many many more graphs. All of the visualizations on a report come from a single dataset. You can create a report from the scratch or a colleague can share a report with you. The other members of the workshop will see the same databases and they can start working with it from their own dashboard. One report can be associated with multiple dashboards.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/emptyReport.png)


### Dashboards
A dashboard is something you create or something a colleague creates and shares with you. It is a single canvas that contains zero or more tiles and widgets. Each tile displays a single visualization that was created from a dataset and pinned to the dashboard.

A dashboard can be filled with tiles from different reports. We will see in Module 3, we will create a dashboard and enrich it pinning tiles on it. So at the end of this lab, you must have a dashboard close to this:

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/finalDashboard.png)


### Quick Insights
Before beginning with a new report, we need to know what the HoL is about, and the best way to do that is taking a look to the dataset. Please open the Excel file and see the type of columns that we have.

We can also see some graphs or statistics with a few clicks. From the left-side bar, go to the *Workspace* - *DATASETS*, and click in the three dots next to the dataset name. A new blade will appear. Select *VIEW INSIGHTS*. Wait a few seconds, click in *View insights* and you'll see some interesting graphs that Power BI make for you.

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/quickInsights.png)


Ok, so in this dataset we can see statistics about sales of products, sold in Canada. We have several information, such as the Product ID, the province where it is sold, the revenue produced for that sell, units sold there and when was it sold.


### Q&A question box.
If you click in the dashboard you've just created importing the dataset, you can make queries in natural language, for example, you can ask:

> Which manufacturer has the highest revenue in Quebec?


Play with it and ask new questions!

![](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%200%20-%20Exploring%20the%20portal/Images/QandA.PNG)

[Let's create some visualizations of our new data](/05.%20Power%20BI%20-%20Hands%20on%20Lab/Module%201%20-%20Visualizations%20I)
