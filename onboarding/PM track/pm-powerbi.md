# PM Skills: Building Your First Power BI Report


## Course - Building Your First Power BI Report

- Get access by visiting: http://aka.ms/getpluralsight
- Visit http://aka.ms/pluralsight to create an account (if needed) and activate your license using your corporate credentials to log in (if prompted)
- Course: **Building Your First Power BI Report**
- Some other resources you can play around with: [Skill Path: Microsoft Power BI for Analysts](https://app.pluralsight.com/paths/skill/microsoft-power-bi-for-analysts).





## Quickstart - Create a PowerBI Dashboard
Download the 64-bit [Desktop Power BI client](https://www.microsoft.com/en-us/download/details.aspx?id=58494). Launch Power BI.

### Create a Query
In PowerBI, click on Get Data button in the Ribbon:
![image.png](/images/powerbi-getdata-1.png)

Select More.  Type "Azure Data Explorer (Kusto)", press **Connect**.  key in `1es` as the cluster, and `Import` as the Data Connectivity mode.
![image.png](/images/powerbi-getdata-2.png)

**Tip:** You can right-click on the query in the Queries list on the left, and use Advanced Editor to edit or rename the query.

**Tip:** Kusto.Explorer has a convenient button to copy the query to Power BI format, under Tools > Query to Power BI.  You can then copy it to the Advanced Editor.

To apply the changes, click the Close and Apply button.

### Create a Visualization
To create a Visualization, click the Visualizations pane and drag it onto a tab.  Select the fields of the data as Axis or Values.

### Publish
To publish the Power BI Report, use the Publish Button in the Ribbon.  Publish to Visual C++, taking care to not overwrite an existing report.

**Tip:** But if you *do* need to edit an existing report:
1. Open it in the browser.
1. Select File > Download report.
1. Open the `.pbix` file in Power BI.
1. Publish the report, and overwrite while publishing.

### Automatic Updates
A published report automatically creates a Dataset.  Go to "Datasets", find the Dataset for your report, and click the ellipsis, selecting "Settings".  Expand the Scheduled refresh setting to select the automatic update frequency.
