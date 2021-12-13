# PM Kills: Kusto / Data Explorer

## Course - Kusto from Scratch

- Get access by visiting: http://aka.ms/getpluralsight
- Visit http://aka.ms/pluralsight to create an account (if needed) and activate your license using your corporate credentials to log in (if prompted)
- Course: **KQL from scratch**
- Some other resources you can play around with: [Kusto Quickstart: Learning to use Telemetry](https://dev.azure.com/devdiv/DevDiv/_wiki/wikis/DevDiv.wiki/2522/Kusto-Quickstart-Learning-to-use-Telemetry) and [Kusto / Azure Data Explorer ](https://aka.ms/kusto)

## Kusto Setup

You have two good options for running your KQL queries in the GitHub database.
 
### Option 1: Web Explorer - https://dataexplorer.azure.com/
 
- Click on "Add Cluster" in the top left corner'
- In the resultant dialog, input "1es.kusto.windows.net" in the URI field.
- Click the "Add" button
- You should have access to the GitHub database in the left coulmn.

![dataexplorer.PNG](/images/dataexplorer.png)

### Option 2: Kusto.Explorer Desktop UI - https://aka.ms/ke
 
- Download the web client from the link above
- Click on the "Connections" tab on the top and select "Add connection"
- In the resultant dialog, input "1es.kusto.windows.net" in the cluster connection field.
- Click the "OK" button
- You should have access to the GitHub database in the left column

![kustoexplorer.PNG](/images/kustoexplorer.png)