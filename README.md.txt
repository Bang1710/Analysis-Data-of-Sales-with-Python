## Analysis Data of Sales with Python
### I. About the Dataset
#### The dataset consists of 11 columns, each column representing an attribute of purchase on a product
- Order ID: A unique ID for each order placed on a product
- Product: Item that is purchased
- Quantity Ordered: Describes how many of that products are ordered
- Price Each: Price of a unit of that product
- Order Date: Date on which the order is placed
- Purchase Address: Address to where the order is shipped
- Month, Sales, City, Hour: Extra attributes formed from the above.

### II. Background Information
#### We start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime..)

#### Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data.
- What is the most ordered product in the store ?
- What is the relationship between the average selling price of products and the quantity of orders placed ?
- What are the top 5 cities with the highest number of orders placed ?
- What is the number of products ordered per hour ?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product ?
- What is the total sales revenue of the store for each month ?
- Which product is the best-selling ?
- What is the highest selling price for a product ?
- Is there a correlation between the price of a product and the quantity of orders placed ?
- How is the distribution of prices among products in the store ? Is there a significant difference in prices among different product types ?
- What are the top 5 cities with the highest online order rate ?