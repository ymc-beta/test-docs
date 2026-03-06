<!-- Version: 1.0 -->
<!-- Status: 1st draft finished: Needs additional details adding (see comments). Ready for review -->

## Custom reports

> [!NOTE]
> This feature is only available to administrators.

### Create a custom report

1. Click the ***Settings*** button in the navigation bar
2. In the ***Inventory Overview*** section, click ***Reports***
3. Click the ***Create Report*** button to create a new report
4. Configure the report ***Columns*** section as required
5. Configure the report ***Settings*** section as required
6. Click the ***Create*** button to save the report

### Edit a report

When creating a new report, or editing an existing one, you have various configuration options available to produce your desired report:

#### Report columns

Use the ***Add Column*** button to choose which data fields to include in the report.

The **column order** can be changed by clicking and dragging the left part of the column element.

Click the **column settings icon** to change the appearance of the field in the report (title, font, column width).

Click the delete icon to remove that particular column.

#### Report settings

In the settings panel you can control the presentation of the report:

***Report Name***
Enter a descriptive name for the report

***Report Type***
Select the type of report:
<!-- To do: -->
<!-- What effect does the type have? Are they filters? -->

- ***Inventory Report***
  Current stock overview of all products
- ***Low Stock Report***
  Products with stock below warning or alarm thresholds
- ***Consumption Report***
  Product consumption over a selected time period
- ***Lent Products Report***
  A summary of the lendable products currently lent out
- ***Defective Products Report***
  A summary of the lendable products currently assigned with a defective status

***Paper Format***
Choose the paper size and orientation.

***Grouping***
The ***Group By*** options allow you to break the report into sections. Additionally you can select the option ***Separate groups*** to start each grouping on a new page (PDF) or worksheet (Excel).

***Sorting***
The primary sorting field can be specified with the ***Sort By*** option. You can specify a secondary sorting with the ***Then Sort By*** selection.

***Filtering***
You can use a filter to specifically only include certain data in the report. Select a field in the ***Filter By*** drop down, then enter the specific value you want to include in the ***Filter Value*** field.


### Delete a Report

<!-- To do: -->
<!-- Missing functionality? Delete not possible...-->

### Run a report

1. Click the ***Settings*** button in the navigation bar
2. In the ***Inventory Overview*** section, click ***Reports***
3. Select the desired report:
   The ***Report Overview*** screen is shown

The ***Report Overview*** presents an on-screen preview of the live data in your configured report. In addition, you have several further options to view your report:

Click the ***View PDF*** button to open the report in PDF format.

Click the ***Download PDF*** or ***Download Excel*** button to save the report in the corresponding file format at a file location of your choice.

The ***Print*** button provides a shortcut to immediately print a PDF of the report.

### Export reports to a network location

Reports can be exported over the network for integration with external systems. 

1. Click the ***Settings*** button in the navigation bar
2. In the ***Inventory Overview*** section, click ***Reports***
3. Click ***Network Export**
   The ***Network Export*** screen is shown

Here you can configure the export of reports to an SMB/CIFS network drive.

<!-- To do: -->
<!-- More info required here: How does it work? What does it look like when configured? Does it export all reports? When? -->