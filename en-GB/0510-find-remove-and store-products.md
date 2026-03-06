<!-- Version: 1.0 -->
<!-- Status: 1st draft finished: Needs additional details adding (see comments). Ready for review -->

## Find, remove and store products

This section describes the operations for finding, removing and storing products in the cabinet system.

> [!NOTE]
> There are 2 types of products:
> 
> 1. **Quantity products** are managed on a unit basis and can be **removed** and **stored**.
> 2. **Lendable products** are single items that can be **borrowed** and **returned**. Lendable products (typically tools) work differently from quantity products. Instead of counting items, the system tracks who has borrowed the tool and when.

### Find products

You can find the products you want in several ways:

1. Browse products in a list, organized by categories
2. Search for a product
3. Browse the storage locations (cabinets and drawers)
4. Scan a barcode or RFID chip assigned to a particular product

#### Find products by browsing a list

1. Click the ***Products*** button in the navigation bar:
   An overview of all product categories is displayed
2. Select the desired category:
   The products assigned to that category are listed
3. Select a product from the list:
   The ***Product Details*** screen is shown


> [!NOTE]
> If the selected product is available in different locations, you will be presented a list of options to choose from when you select the product.

#### Find products by searching

A search field is available at the top of the product list:

1. Enter a search term (e.g. product name, article number, or EAN code) in the search field
2. The list is filtered in real time to show matching products
3. Select a product from the list:
   The ***Product Details*** screen is shown



#### Find products by storage location (cabinets and drawers)

The ***Storage*** screen provides access to products by allowing you to navigate through the physical cabinet structure.

##### Browse cabinets

1. Click ***Storage*** in the navigation bar:
   The ***Storage*** screen appears, displaying an overview of all cabinets in the system
2. Click on the desired cabinet and drawer:
   The ***Product Details*** screen opens with your chosen drawer selected


#### Find products by barcode or RFID scan

The **Scan** screen provides direct product lookup by scanning a barcode or RFID tag.

##### Barcode scan

> [!NOTE]
> A barcode scanner must be connected and configured for automatic scanning.

1. Click ***Scan*** in the navigation bar:
   The ***Scan*** screen is displayed
2. Scan the barcode of the product using the connected barcode scanner
3. The system searches for the product and navigates directly to the ***Product Details*** screen.

> [!NOTE]
> A barcode scanner must be connected and configured for automatic scanning. Alternatively, you can type the barcode number manually using an external keyboard.

##### RFID chip scan

> [!NOTE]
> An RFID scanner must be connected and configured for automatic scanning.

1. Open the ***Scan*** screen
2. Hold the RFID tag against the reader
3. The system searches for the product associated with the RFID tag and navigates directly to the ***Product Details*** screen

### The Product Details screen

The ***Product Details*** screen shows the following 3 information panels:

- ***Cabinet Info***
- ***Drawer Info***
- ***Product Info***
#### Cabinet Info panel

The cabinet of a selected product is shown.
##### Navigate drawers

Within a cabinet, drawers are displayed visually showing their position in the cabinet: Click on a drawer to view its contents in the ***Drawer Info*** panel.

For cabinets with electronic locks:

- When you navigate to a drawer, it can be **automatically unlocked** if configured
- Lock status is shown visually on the drawer
- Manual lock/unlock buttons may be available depending on your access rights

<!-- To do: -->
<!-- Explanation of the coloured indicators on each drawer  -->
<!-- Explanation of the Map icon (cabinet location) -->
<!-- Explanation of the **“Hide front image” icon** -->
#### Drawer Info panel

A top-down representation of the drawer that contains the selected product. The compartment layout is shown with products displayed in their assigned positions.

Click on a product to see its details and perform actions (store/remove).

Each product displays:

- **Product name**
- For lendable products: Current **lending status**
- **Product image** thumbnail

<!-- To do: -->
<!-- zoom controls etc -->
<!-- link to drawer editing -->


#### Product Info panel

Here you can see relevant information about the selected product:

- **Product name** and article number
- **Stock level** for this placement location
- **Product image** (if available)
- **Storage locations** - which cabinet, drawer, and compartment the product is stored in
- **Product attributes** - custom product properties defined by the category

This panel also contains the functions necessary to store or remove the product(s).

##### Stock information

For each quantity product, the following information is visible:

- **Current stock**: Number of items currently in this compartment
- **Low stock warning level**: Threshold for yellow warning indicator
- **Low stock alarm level**: Threshold for red alarm indicator

> [!NOTE]
> Stock levels that fall below the warning or alarm thresholds are visually highlighted and can trigger email notifications if configured.


### Remove products

1. Navigate to the product via any of the methods available (***Products***, ***Storage***, or ***Scan***)
2. The product is shown in the ***Product Details*** screen
3. Adjust the quantity to be removed
4. Click ***Take Out*** to confirm the removal.

The quantity (stock level) is updated immediately and the action is recorded in the audit log.

<!-- To do: -->
<!-- Commission field -->
### Store products

1. Navigate to the product.
2. Adjust the quantity to be added.
3. Click ***Put Back*** to confirm the storage addition.

The quantity (stock level) is updated immediately and the action is recorded in the audit log.


### Borrow a lendable product

1. Navigate to the lendable product via any of the methods available (***Products***, ***Storage***, or ***Scan***).
2. The current status is displayed (***Available, Lent out, Out for Repair, Defective, Inspection required***).
3. Optional: Enter an ***Expected Return date***
4. Click ***Take Out*** to borrow the product, or ***Take out for repair*** to mark it as sent for repair

 As the borrower (the currently logged-in user), your name  is automatically recorded.

### Return a lendable product

1. Navigate to the lendable product via any of the methods available (***Products***, ***Storage***, or ***Scan***), or
   Navigate to the ***Lent Products*** screen via ***`Settings > Lent Products`***
2. The list of currently lent products is displayed with borrower information
3. Select the product to return
4. Optional: select ***Mark as defective***
5. Click ***Return*** to confirm the return

#### Product inspection

Some lendable products may require inspection approval before they can be returned to service. When applicable, an inspection workflow is triggered upon return.





### Favourite products

Products can be marked as favourites for quick access. When you have at least one favourite product, you will see a ***Favourites*** category in the list on the ***Products*** screen.

#### Save favourite products

- Click the **star icon** on any product to mark it as a favourite.
- Click again to remove it from favourites.
