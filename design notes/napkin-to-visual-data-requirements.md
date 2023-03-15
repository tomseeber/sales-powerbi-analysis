# Napkin Drawing to Visualization Analysis



## Opening Page

![Opening Napkin Drawing Page](./napkin%20drawings/opening%20page.png)



### Visualizations on Napkin

#### Boxes on Side

#### Total Sales $$$ Card

Requires aggregate of all order details times amount and price data.  DAX field required.

#### Total Sales Volume Card

Requires aggregate of all count of orders.  DAX field required.

#### New Customers amount Callout Number

Requires aggregate count of customers where customers are in the latest month and year, but not the previous month and year.   Probably requires a DAX field.

#### Sales Person Slicer

Requires Data to be plugged in from the Employee table.

#### Last 12 months Bar and Line Trend total sales trend Graph

Requires all sum of the product cost, times amount, with the discount applied.  DAX field required.

#### Last 12 months Bar and Line Trend volumn trend Graph

Requires aggregate of all count of orders.  DAX field required.

#### New Customers amount Callout Number

Requires list where customers are in the latest month and year but not the previous month and year.   It probably requires a DAX field.

#### Regional Hot map of orders

Requires lat and longitude. ( we don't have that, but we do have addresses).  Will require API calls to get lat and longitude from the address.



## Customer Details Page

![Customer Details Page](./napkin%20drawings/customer%20detailpage.png)

### Visualizations on Napkin

#### Boxes on Side

No Really data needed.

#### Customer Information Card

This has all the information right there for the salesperson to make contact.  It comes from the Customer table.   

#### Slicer (indivudal customer)

List of customers from Customers.   Should apply intial slicer. 
Should apply no data or display from this back to intial.

#### Total Sales $$$ Card per customer

Requires aggregate of all order details times amount, and price data with discount applied.  DAX field required.

#### Total Sales Volume Card per customer

Requires aggregate of all count of orders.  DAX field required.


#### Commonly ordered items
REquires Top N filter for order details.   and Supplies amounts for those items


#### Last 12 months Bar and Line Trend total sales trend Graph

Requires all sum of the product cost, times amount, with the discount applied.  DAX field required.

#### Last 12 months Bar and Line Trend volumn trend Graph

Requires aggregate of all count of orders.  DAX field required

#### Orders from #mont
This requires the product id. amount, and price amount and category... (two tables)
This should have an added slicer with limeted interactions for this table.


#### Treemap of the categories

This treemap is a general visualization of the customer preferences as far as what they buy

## Regional Informal Details Page

![Regional Informal Details Page](./napkin%20drawings/Regional%20information.png)

### Visualizations on Napkin

#### Boxes on Side

No Really data needed.



#### Total Sales $$$ Card per Region ( aka State)

Requires aggregate of all order details times amount, and price data with discount applied.  DAX field required.

#### Total Sales Volume Card per Region ( aka State)

Requires aggregate of all count of orders.  DAX field required.

#### State Slicer

State/region slicer from shipping address.  Should include from the order region

#### Month Slicer

State/region slicer from shipping address.  Should include from the order month /year 

#### Sales Map

Orders in slicer month's that  is from the current salesman.  


#### Last 12 months Bar and Line Trend total sales trend Graph for the Region

Requires all sum of the product cost, times amount, with the discount applied.  DAX field required.

#### Last 12 months Bar and Line Trend volume trend Graph for the region

Requires aggregate of all count of orders.  DAX field required

#### Best Customers  ( Top n Table)

Should have customers' data for first and last name, address ( consolidated and put together) with text wrap,  phone, and total order amount (sum from the  Dax field)

#### Hot Items in Region ( top n Table)

This is a top N, most volume data, with some information on supplies amount, volume, and dollar amounts sold in the region. 

