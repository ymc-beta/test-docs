<!-- Version: 1.0 -->
<!-- Status: 1st draft finished: Needs additional details adding (see comments). Ready for review -->

# Pick Lists

***Pick Lists*** allow you to group products together and process them in a batch - removing specified quantities one after another. A ***Pick-List*** can have different properties:

- ***One-Time List***: Automatically archived after processing
- ***Reusable***: Can be processed multiple times
- ***Fixed Order***: Products must be processed in the specified sequence
- No ***Fixed Order***: Products can be processed in any sequence

## View Pick-Lists

Go to ***`Settings > Pick-Lists`***

A list of all ***Pick-Lists*** is displayed with status information:

   - ***Active***: Ready to be processed
   - ***In Progress***: Currently being processed
   - ***Completed***: Processing finished
   - ***Archived***: Completed and archived



## Process Pick-Lists

### Start a Pick-List

1. Open the ***Pick-Lists*** screen (go to ***`Settings > Pick-Lists`***)
2. Select the ***Pick-List*** you want to process
3. Review the products and quantities listed
4. Click ***Start Pick-List*** to begin processing

The first product is displayed with its target quantity and storage location.

### Process items in the Pick-List

For each item in the ***Pick-List***:

1. The ***Product Details*** screen opens with the selected product at its location in the cabinet system, with the target removal quantity pre-filled
2. Remove the specified quantity of the product 
3. Confirm the removal by clicking the ***Take Out*** button:
   The confirmation screen is displayed, showing the name of the next listed item in the ***Pick-List***, and buttons ***Next item*** and ***Skip item***
4. Click ***Next item*** to go to the ***Product Details*** screen for that item, or click ***Skip item*** to skip it.

Repeat this process until you have reached the end of the ***Pick-List***.

### Complete a Pick-List
<!-- To do: -->
<!-- Review actual functionality and correct documentation if required. The Pick list function appears to have numerous bugs -->
After all items have been processed, a summary of the ***Pick-List*** is displayed showing:

   - Number of items completed
   - Any skipped items

To complete the ***Pick-List***, click the  ***Complete Pick-List*** button:

- The Pick-List status changes to **Completed**
- ***One-Time Lists*** are automatically archived

### Skip items in a Pick-List
<!-- To do: -->
<!-- Review actual functionality and correct documentation if required. The Pick list function appears to have numerous bugs -->
If a product is unavailable or should be skipped:

1. Click **Skip item** on the current item.
2. Enter a comment explaining the reason for skipping.
3. Confirm with **Skip**.

The skipped item is recorded with quantity "0" and the comment in the ***Pick-List*** report.

## Create a Pick-List

Administrators can create ***Pick-Lists*** directly in the application:

1. Go to ***`Settings > Pick-Lists > Create Pick-List`***
2. Enter the ***Pick-List*** details:
   - ***Name***: A descriptive name for the ***Pick-List***
   - ***Settings***: Set whether the list is  ***One-Time List***, ***Reusable***, or ***Fixed Order***
1. Add products and specify the required quantities.
2. Save the ***Pick-List***.

The ***Pick-List*** is now available for processing.


## Import Pick-Lists

***Pick-Lists*** can be imported from external files (e.g., from an ERP system).

1. Go to ***`Settings > Pick-Lists > Import Pick-List`***
2. Select the import file.
3. Review the import preview.
4. Confirm the import.

The imported ***Pick-List*** appears in the ***Pick-Lists*** overview and is ready for processing.

> **Note:** The import file format should follow the standard ***Pick-Lists*** template. Contact your administrator for the correct file format.
