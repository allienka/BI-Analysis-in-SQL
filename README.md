# BI-Analysis-with-SQL
aim of this project is to work with purchased data, build a derived table, and calculate KPIs<br>
based on the datasets provided


# Requirements
-is to create a query using SQL, that produces a table where we can see the profitability of each
purchase
-Calculate and visualize the following KPIs:<br>
    ● Top 10 venues with the highest margins, and plot the relationship between the margin<br>
      and average order size<br>
    ● Top 5 countries for each of the following metrics:<br>
        ○ average order size<br>
        ○ average order value<br>
        ○ order volume<br>
    ● Plot the monthly cumulative Woltwide (i.e. global) margin<br>
  
# PREREQUISITES<br>
- Install MySQLWorkbench or Xampp<br>
- Any Editor (Preferably VS Code or Sublime Text)<br>
- Anaconda<br>
- Jupyter Notebooks<br>
- Any web browser with the latest version<br>

Languages and Technologies used:<br>

- XAMPP or MySQL Workbench<br>
- Python 3<br>
- MySQL<br>
- Tableau public<br>

Steps to run the project on your machine<br>

- Download and install Python ([instructions here](https://www.geeksforgeeks.org/how-to-install-python-on-windows/))<br>
- Install the libraries needed (pandas, numpy, os.path, connection,sqlalchemy) in vscode download python get-pip.py and then pip run 'libraryname'<br>
- Download and install XAMPP or MYSQLWorkbench (XAMPP WORKBENCH)<br>
- Install Anaconda and launch Jupyter Notebook<br>

download the csv files in the same folder with my jupyter notebook file and run it.



# Fields in datasets<br>
purchase_data.csv<br>
● PURCHASE_ID: The unique identifier of the purchase<br>
● TIME_RECEIVED: The time when the customer made the order<br>
● TIME_DELIVERED: The time when the order was delivered to the customer<br>
● CURRENCY: Local currency the purchase was made in<br>
● COUNTRY: The country of the venue where the purchase was made<br>
● VENUE_ID: The unique identifier of the venue<br>

purchase_item_data.csv<br>
● PRODUCT_ID: Identifier for the item used at Wolt<br>
● PURCHASE_ID: The unique identifier of the purchase<br>
● COUNT: How many items of a certain type were purchased<br>
● VENUE_ID: The unique identifier of the venue<br>
● BASEPRICE: The price of an item in local currency including value-added tax (VAT)<br>
● VAT_PERCENTAGE: Value-added tax (VAT) percentage<br>

item_data.csv<br>
● VENUE_ID: The unique identifier of the venue<br>
● TIMESTAMP: Time when the item became available<br>
● BRAND: Name of the brand of a product<br>
● MANUFACTURER: Name of the manufacturer of a product<br>
● COST_PER_UNIT: Cost of single unit of item in local currency excluding value-added
tax (VAT)<br>
● COST_PER_UNIT_EUR: Cost of single unit of item in Euro excluding value-added tax
(VAT)<br>
● CURRENCY: Currency for the item price<br>
● APPLICABLE_TAX_PERC: Applicable tax percentage of the item<br>
● PRODUCT_ID: Identifier for the item used at Wolt<br>
● ITEM_IDENTIFIER: Global Trade Item Number (GTIN)<br>
● EXTERNAL_ID: External ID of the item used by the eternal vendor<br>

# VISUALIZATIONS<br>


![Screenshot_20230218_122444](https://user-images.githubusercontent.com/105230372/220627888-1061d177-ac3e-45bf-bc16-493180077690.png)
![Screenshot_20230218_123631](https://user-images.githubusercontent.com/105230372/220627893-dac3332a-1c7d-47d5-852d-55b5dbdc89b6.png)
![Screenshot_20230218_141003](https://user-images.githubusercontent.com/105230372/220627898-9079afe1-647a-4a0f-92dd-8b0fcff0e704.png)
