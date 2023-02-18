# Pizza Restaurant Insights with Tableau 🍕
This project explores data from a pizza restaurant using Tableau to uncover insights about customer behavior and pizza preferences. The visualizations in this project are available at this <a href="https://public.tableau.com/app/profile/pauclaret/viz/pizza_sales/dashboard?publish=yes">Tableau Public link</a> 🤗

<img src="https://www.foodandwine.com/thmb/Wd4lBRZz3X_8qBr69UOu2m7I2iw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/classic-cheese-pizza-FT-RECIPE0422-31a2c938fc2546c9a07b7011658cfd05.jpg" alt="Classic Cheese Pizza">

## Data 🔢
The data folder contains three elements:

- datamodel_pizzasales.xlsx: This is the original Excel file downloaded from Kaggle that contains raw data about orders made at the pizza restaurant. The data covers a period of one year and includes information about each order, such as the type of pizza ordered, the time of the order, and the price paid.
- pizza_sales.csv: This CSV file was created after cleaning the data using Pandas. It contains information about pizza orders, including the type of pizza ordered, the time of the order, and the price paid.
- ingredients.csv: This CSV file was created after cleaning the data using Pandas. It contains specific information about the ingredients used in the pizzas, such as the name, type, and category.

Both pizza_sales.csv and ingredients.csv were created from the original datamodel_pizzasales.xlsx file. The cleaned data in CSV format was used for the visualizations in this project using Tableau.

## Notebooks 📓
The notebooks folder contains one Jupyter Notebook:

- cleaning.ipynb: This notebook contains the code used to clean the datamodel_pizzasales.xlsx file. The cleaning process involved removing duplicates, handling missing values, and converting data types as needed. The result of the cleaning process was two CSV files: pizza_sales.csv, which contains information about pizza orders, and ingredients.csv, which contains information about the ingredients used in the pizzas. The cleaned data in CSV format was used for the visualizations in this project using Tableau.

## Visualizations 📊
Tableau was used to create the following visualizations:

- Sales by Months: This line chart shows the total sales by month, allowing us to see any seasonal trends and make informed decisions about menu offerings and promotions.
- Sales by Weekday: This bar chart shows the frequency of orders by weekday, allowing us to see the busiest days of the week for the restaurant and make informed decisions about staffing levels.
- Sales by Hours: This heatmap shows the frequency of orders by hour of the day and day of the week, allowing us to see the busiest times of the day and make informed decisions about staffing levels.
- Sales by Pizza Category: This donut chart shows the breakdown of orders by pizza category, allowing us to see the most popular categories and make informed decisions about menu offerings.
- Sales by Type of Pizza: This stacked bar chart shows the breakdown of orders by type of pizza, allowing us to see the most popular types of pizza and make informed decisions about menu offerings.
- Sales by Pizza Size: This bubble chart shows the breakdown of orders by pizza size and price, allowing us to see the most popular sizes and make informed decisions about pricing.
- Quantity Ordered vs Unit Price: This scatter plot shows the relationship between the quantity ordered and the unit price, allowing us to see any patterns in the data and make informed decisions about pricing and promotions.
- Top 10 Most Ordered Ingredients: This horizontal bar chart shows the top 10 most ordered ingredients, allowing us to see the most popular ingredients and make informed decisions about ingredient sourcing and menu offerings.
- Less 10 Ordered Ingredients: This horizontal bar chart shows the least 10 ordered ingredients, allowing us to see the least popular ingredients and make informed decisions about ingredient sourcing and menu offerings.

## Conclusion 🍕
The goal of this project is to provide the pizza restaurant with a better understanding of customer behavior and pizza preferences. By visualizing the data in an interactive dashboard, the restaurant can make informed decisions about menu offerings, staffing levels, and ingredient sourcing.

If you are interested in learning more about this project or using the visualizations for your own research, please feel free to contact me!