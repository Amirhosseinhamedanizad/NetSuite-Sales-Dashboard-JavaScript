# NetSuite-Sales-Dashboard-JavaScript

NetSuite Sales Insights Dashboard using HTML and JS

## Overview

The "NetSuite Sales Insights Dashboard" is a web-based project that displays key sales data from a NetSuite account in an interactive and visually appealing dashboard. This project serves as a demonstration of how HTML, CSS, and JavaScript can be used to create a user-friendly interface for viewing sales insights.

## Features

- **Total Sales:** The dashboard provides an overview of the total sales, presenting the current financial status.
  
- **Number of Orders:** It displays the total number of orders, allowing users to gauge sales activity.
  
- **Average Order Value:** Users can see the average value of orders, which can provide insights into customer behavior.
  
- **Top-Selling Product:** The dashboard highlights the product that has generated the most sales.

## Usage

1. Clone this repository to your local environment.

2. Open the `index.html` file in a web browser.

3. The sales data will be fetched and displayed on the dashboard.

## Note

This project contains simulated data and does not directly connect to a real NetSuite instance. In a real-world scenario, it would require integration with NetSuite's API to retrieve and display up-to-date sales information. This project serves as a starting point for developing a more comprehensive sales analytics dashboard for your NetSuite account.

Feel free to customize and extend this project for your specific needs or as a learning resource.

1. **HTML Structure**: The HTML file establishes the structure of the web page. It includes a title, some basic styling using CSS, and a container for the sales dashboard.

2. **Styling**: The embedded CSS styles the webpage to make it visually appealing. It sets the background color, font, and container properties.

3. **Sales Dashboard Container**: Within the container, an `<h1>` element displays the title "NetSuite Sales Dashboard," and an empty `<div>` element with the `id="salesData"` is reserved for displaying sales data.

4. **JavaScript Logic**: The JavaScript code section begins with a function called `fetchSalesData`. This function is a simulated representation of an API call to NetSuite to fetch sales data.

5. **Simulated API Call**: Inside `fetchSalesData`, the script simulates an API response by creating a `salesData` object with example sales data such as total sales, the number of orders, average order value, and the top-selling product. In a real-world scenario, this is where an actual API call to NetSuite would occur.

6. **Display Data**: The fetched sales data is displayed on the dashboard by accessing the `salesData` object properties and injecting them into the `salesData` `<div>` element. This dynamically generates a sales overview with details like total sales, number of orders, average order value, and the top-selling product.

7. **Execution**: The `fetchSalesData` function is called at the end to execute the process, and it populates the dashboard with the simulated sales data when the page loads.

In summary, this project's HTML and JavaScript code create a visually appealing sales dashboard that simulates fetching data from NetSuite (although it doesn't directly connect to a real NetSuite instance). It demonstrates the process of displaying essential sales insights in a web-based dashboard using HTML, CSS, and JavaScript. In a real-world application, you would replace the simulated API call with actual integration to NetSuite to retrieve and display up-to-date sales data.