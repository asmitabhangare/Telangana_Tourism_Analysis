# Telangana_Tourism_Analysis
The aim of the Telangana Tourism Department Analysis is to provide insights into strategies for increasing revenue and achieving organizational goals. The objective is to monitor the number of visitors to tourist destinations in Telangana. Several reports have been created that offer information on various factors, which will help the organization identify the actions needed to boost revenue by attracting more visitors.

# Data Cleaning using Power Query
+ Import the data from the specified folder into Power Query.
- Create a custom column named Type in the Domestic Visitors table and assign the value Domestic to it.
* Create a custom column named Type in the Foreign Visitors table and assign the value Foreigner to it.
+ Append the Domestic Visitors table and the Foreign Visitors table into a single consolidated table.
- Replace any null values in the consolidated table with 0.
* Replace any incorrect district names with the correct ones using the Replace method.
+ Load the cleaned data into Power BI and apply the transformations.

# DAX 
Using DAX queries, we can efficiently manipulate and analyze data to generate insights for visualizations and identify improvement opportunities for the Tourism Department. By creating measures and columns with DAX functions like COUNT and SUM, we can explore the cleaned data to enhance dashboard KPIs in Power BI.

# Visualization using Power BI
+ Plan and structure the layout of the dashboard, organizing the placement of charts, slicers, and other visual elements for a clean and user-friendly experience.
- Create a dedicated measure table to aggregate and display key data using DAX functions, ensuring that the measures are well-organized for easy reference and use.
* Incorporate a variety of visualizations such as bar charts, column charts, cards, line charts, and donut charts to effectively present the data. Use filters to allow users to interact with and refine the dashboard view.
+ Include a Year column as a slicer to enable filtering by specific years. Add informative KPIs to highlight key metrics and trends.
- Use bar charts, column charts, cards, line charts, and donut charts to visualize different aspects of the data, ensuring each visualization serves a clear purpose.
* Add buttons for easy navigation within the dashboard, allowing users to move between different sections or views seamlessly.
