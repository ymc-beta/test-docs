<!-- Version: 1.0 -->
<!-- Status: 1st draft finished: Needs additional details adding (see comments). Ready for review -->

## Manage products

This section describes the administrative functions for configuring products. These functions require **administrator** privileges.

### View products

Go to ***`Settings > Products`*** to view the ***Products*** screen - a searchable list of all products in the system.

Use the search field to find specific products by name, article number, or EAN code

<!-- To do: -->
<!-- Explain attributes -->
<!-- Explain Stock and Location (for single and multiple placements)  -->
<!-- Explain Table view/Grid view -->
<!-- Explain the category drop down (that appears when viewing a category) -->
<!-- Explain the Filter button: what it does (with examples, using combinations of attributes for screws), and when it is disabled. Refer to where to edit the attributes -->


### Edit a product

1. Go to ***`Settings > Products`***:
   The ***Manage Products*** screen is displayed
2. Find and select the product you want to edit, using the search and/or category filters:
   The ***Product Overview*** screen is displayed
3. Click the ***Edit Product*** button:
   The ***Edit Product*** screen is displayed
4. Modify the product's properties as required, then click ***Save Changes***

#### Product properties

The following properties of a product can be edited in the corresponding panels on the ***Edit Product*** screen:

##### Product Details

- ***Name***: Product display name
- ***Article Number***:  Unique article identifier
- ***EAN Code / RFID***:  Unique article identifier of corresponding RFID chip
- ***Product Category***:  The category of this product

##### Product Picture

- Click ***Select picture*** to open the ***Media Explorer*** to upload or select an image
- Click ***Remove picture*** to remove the assigned image from this product 

##### Product Files

- Click ***Add document*** to upload a PDF document
- Click ***Delete*** to delete an uploaded document

##### Custom Attributes

Enter the appropriate values for this product.

> [!NOTE]
> The custom attributes for a product are defined by the category it is assigned to.

##### Product Supply

Choose what type of product this is: ***Loanable*** (for lendable products), or ***Consumable*** (for quantity products). This choice shows the appropriate panels to specify further details:

###### Loanable (for lendable products)

***Service Check***:
- ***Next Check***: Date of the next service
- ***Warning Period (Days)***: How many days before the next check date the service warning should be sent
<!-- To do: -->
<!-- More details here about the process: What is sent, who controls it, how to change etc. -->
- ***Alarm Period (Days)***: How many days before the next check date the service alarm should be sent
<!-- To do: -->
<!-- More details here about the process: What is sent, who controls it, how to change etc. -->

***Limit Usage***:
- ***No***: 
- ***Yes***: 
<!-- To do: -->
<!-- Add details about Limit Usage. -->

***Limit by Time***
- ***No***: 
- ***Yes***: 
<!-- To do: -->
<!-- Add details about Limit by Time. -->


###### Consumable (for quantity products)

- ***Counting Unit***: Unit of measurement (pieces, litres, kg, etc.)
- ***Number Type***: Choose integer or decimal values for the counting unit
- ***Supplier***
- ***Order Number***
- ***Default Withdrawal Amount***: Default quantity for removals
- ***Default Order Amount***: Default quantity for orders



### Create a new product

1. Go to ***`Settings > Products`***:
   The ***Manage Products*** screen is displayed
2. Click the ***Add Product*** button
3. Enter the product details as required
   (Refer to the **Edit a product** section in the documentation for an explanation of each property)
4. Click **Create** to create the new product

> [!NOTE]
> The ***Product Files*** property is only visible after the new product has been saved.


### Delete a product

1. Go to ***`Settings > Products`***:
   The ***Manage Products*** screen is displayed
2. Find and select the product you want to delete, using the search and/or category filters:
   The ***Product Overview*** screen is displayed
3. Click the ***Delete Product*** button
4. Confirm the deletion in the dialog

> [!WARNING]
> Deleting a product removes it from all locations and cannot be undone.



### Import products

Products can be bulk-imported from Excel files.

<!-- To do: -->
<!-- Rewrite Claude's text  -->

<!-- 
### Import Process

1. Navigate to **Settings > Product Import**.
2. Select the import file (Excel format).
3. Choose the import mode:

| Mode | Description |
|------|-------------|
| **Fresh** | Remove all existing products and replace with imported data |
| **Update** | Update existing products and add new ones |
| **Dry Run** | Preview the import without making changes |

4. Click **Start Import**.
5. Review the import results:
   - Number of products created
   - Number of products updated
   - Number of products skipped
   - Any errors encountered

> **Note:** We recommend running a **Dry Run** first to verify the import data before applying changes.
 -->

### Export products

<!-- To do: -->