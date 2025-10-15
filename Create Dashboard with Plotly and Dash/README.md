# 📊 Automobile Sales Statistics Dashboard

This project is a dynamic, interactive dashboard built using **Dash** and **Plotly** to visualize and analyze historical automobile sales data, focusing on trends during and outside of recession periods.

-----

## 💡 Project Overview and Scenario

 The objective of this dashboard is to analyze the historical trends in automobile sales to provide insights into how the sales of **XYZAutomotives** were affected during times of recession[  28, 29].  The analysis covers the years **1980 to 2013**.

 The dashboard is structured to display two primary reports, controlled by an interactive dropdown menu: **Yearly Automobile Sales Statistics** and **Recession Period Statistics**

-----

## ✨ Features and Interactivity

The dashboard utilizes two main interactive components to allow users to explore the data:

1.  **Report Type Selection:** A dropdown allows the user to choose between the two main reports:
      * `Yearly Statistics`
      *  `Recession Period Statistics`
2.   **Year Selection:** A second dropdown is used to select a specific year.
      *  This dropdown is **enabled** when `Yearly Statistics` is selected.
      *  It is **disabled** when `Recession Period Statistics` is selected, as the recession report covers multiple years.

 Both reports display four distinct plots in a 2-row, 2-column layout.

-----

## 📈 Reports and Visualizations

The dashboard is capable of generating the following sets of four visualizations based on the user's selection:

### 1\. Yearly Automobile Sales Statistics (Filtered by Selected Year)

| Plot | Type | Description |
| :--- | :--- | :--- |
| **Yearly Automobile Sales** | Line Chart |  Average automobile sales for each year across the entire period (1980-2013). |
| **Total Monthly Automobile Sales** | Line Chart |  Total monthly automobile sales for the **selected year**. |
| **Average Vehicles Sold** | Bar Chart |  Average number of vehicles sold for each vehicle type in the **selected year**. |
| **Total Advertisement Expenditure** | Pie Chart |  Total advertising expenditure share for each vehicle type in the **selected year**. |

### 2\. Recession Period Statistics (Filtered where `Recession = 1`)

| Plot | Type | Description |
| :--- | :--- | :--- |
| **Sales Fluctuation** | Line Chart |  Average automobile sales for each year **during recession periods**. |
| **Vehicles Sold by Type** | Bar Chart |  Average number of vehicles sold for each vehicle type **during recession periods**. |
| **Total Expenditure Share** | Pie Chart |  Total advertising expenditure share by vehicle type **during recession periods**. |
| **Unemployment Effect on Sales** | Bar Chart |  Effect of unemployment rate on automobile sales by vehicle type **during recession periods**. |

-----

## 💾 Dataset Variables

 The analysis is based on a dataset that includes the following key variables:

| Variable Name | Description |
| :--- | :--- |
| `Date` |  The date of the observation. |
| `Recession` |  A binary variable (1 = recession period, 0 = normal period). |
| `Automobile Sales` |  The number of vehicles sold during the period. |
| `unemployment rate` |  The monthly unemployment rate. |
| `Advertising_Expenditure` |  The advertising expenditure of the company. |
| `Vehicle_Type` |  The type of vehicles sold (e.g., Supperminicar, Sports, Executivecar, etc.). |

-----

## ⚙️ Setup and Running the Application

### Prerequisites

To run this application, you must have **Python 3.8 or later** installed, along with the required libraries.

### Installation

Install the necessary Python packages using `pip`:

```bash
pip install setuptools packaging pandas dash more-itertools
```

### Running the App

1.  Navigate to the project directory in your terminal.

2.  Execute the Python script (assuming the file is named `DV0101EN-Final-Assign-Part-2-Questions.py`):

    ```bash
    python DV0101EN-Final-Assign-Part-2-Questions.py
    ```

3.  The terminal will display the local URL (e.g., `http://127.0.0.1:8050/`). Open this link in your web browser to view and interact with the dashboard.

### Running Dashboard :
![alt text](image.png)
![alt text](image-1.png)