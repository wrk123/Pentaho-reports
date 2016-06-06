#Document on report genetation using Pentaho report designer -

Download Pentaho report designer 6.1 from  -  http://community.pentaho.com/projects/reporting/
Prequisite -    Download MySQL jar file version 5.1.5 jar file and place it in "report-designer/lib" folder.
	           RAM – 1.5 – 2 GB min for smooth operation


Steps to start with designing report using Pentaho -
------------------------------------------------------------------
Open the report designer by executing the command "report-designer.sh" for linux in the terminal.
Create a new report. A basic sample report page will be displaye. 
Now, make DB connection by clicking on Data -> Add Data Source -> JDBC datasource.
A  JDBC datasource window will pop  and click on green ‘+’ icon to add the datasource.
A database connection window will pop up, select MySQL from the list and fill the required details in the form on the right hand side (connection detail. Hostname, username,password, database name, etc)
Click on the test icon to test the connection. On successfull connection it will show OK.
Now you are done with setup of connection.
You need to add query in the right side in the JDBC datasource window. 
Select the datasource which you have created and then click on “Add query” on the right side.
Write MySQL query and then click on “Preview’ to view the query result and then select “OK”.
Now you will be placed back in “report Designer window”. 
Goto right side of the window and click on “Data”.
In the “Data Set” you can see your queried data results, having all the field names. 
Drag anddrop the names in the report at the required places and then click on ‘eye’ icon to preview the report result. The similar icon will be replaced with “pencil” icon in preview mode. 
Click on the pencil icon to revert back to edit mode.

Adding page numbers -
-----------------------------
For adding Page number in the  footerm, click on the function in the data tab.
From the pop up -> common -> Page of Pages.
You can see a function option coming up in Data. Drag and drop that into the page footer section.
And it is done.

Adding groups -
----------------------
You can add groups from the structure. 
Just right click on the Groups and select add groups . 
From the pop up select the group type and then click OK. 
The group will be created. Now drag and drop the label name fromthe top left corner and then rename the label as you want. Drag and drop the item to be displayed in the similar fashin as did earlier.
Align them properly and then click on Preview to view the report in preview mode.

One can export the review report to PDF  or Excel or other formats available.

Reference -
     http://wiki.pentaho.com/display/Reporting/01.+Creating+Your+First+Report
