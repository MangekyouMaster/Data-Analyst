# 📊 Automobile Sales Statistics Dashboard

This project is a dynamic, interactive dashboard built using **Dash** and **Plotly** to visualize and analyze historical automobile sales data, focusing on trends during and outside of recession periods.

-----

## 💡 Project Overview and Scenario

[cite\_start]The objective of this dashboard is to analyze the historical trends in automobile sales to provide insights into how the sales of **XYZAutomotives** were affected during times of recession[cite: 28, 29]. [cite\_start]The analysis covers the years **1980 to 2013**[cite: 40].

[cite\_start]The dashboard is structured to display two primary reports, controlled by an interactive dropdown menu: **Yearly Automobile Sales Statistics** and **Recession Period Statistics**[cite: 37].

-----

## ✨ Features and Interactivity

The dashboard utilizes two main interactive components to allow users to explore the data:

1.  **Report Type Selection:** A dropdown allows the user to choose between the two main reports:
      * `Yearly Statistics`
      * [cite\_start]`Recession Period Statistics` [cite: 79]
2.  [cite\_start]**Year Selection:** A second dropdown is used to select a specific year[cite: 80].
      * [cite\_start]This dropdown is **enabled** when `Yearly Statistics` is selected[cite: 89].
      * [cite\_start]It is **disabled** when `Recession Period Statistics` is selected, as the recession report covers multiple years[cite: 90].

[cite\_start]Both reports display four distinct plots in a 2-row, 2-column layout[cite: 96].

-----

## 📈 Reports and Visualizations

The dashboard is capable of generating the following sets of four visualizations based on the user's selection:

### 1\. Yearly Automobile Sales Statistics (Filtered by Selected Year)

| Plot | Type | Description |
| :--- | :--- | :--- |
| **Yearly Automobile Sales** | Line Chart | [cite\_start]Average automobile sales for each year across the entire period (1980-2013)[cite: 44]. |
| **Total Monthly Automobile Sales** | Line Chart | [cite\_start]Total monthly automobile sales for the **selected year**[cite: 45]. |
| **Average Vehicles Sold** | Bar Chart | [cite\_start]Average number of vehicles sold for each vehicle type in the **selected year**[cite: 46]. |
| **Total Advertisement Expenditure** | Pie Chart | [cite\_start]Total advertising expenditure share for each vehicle type in the **selected year**[cite: 47, 48]. |

### 2\. Recession Period Statistics (Filtered where `Recession = 1`)

| Plot | Type | Description |
| :--- | :--- | :--- |
| **Sales Fluctuation** | Line Chart | [cite\_start]Average automobile sales for each year **during recession periods**[cite: 50]. |
| **Vehicles Sold by Type** | Bar Chart | [cite\_start]Average number of vehicles sold for each vehicle type **during recession periods**[cite: 51]. |
| **Total Expenditure Share** | Pie Chart | [cite\_start]Total advertising expenditure share by vehicle type **during recession periods**[cite: 52]. |
| **Unemployment Effect on Sales** | Bar Chart | [cite\_start]Effect of unemployment rate on automobile sales by vehicle type **during recession periods**[cite: 53]. |

-----

## 💾 Dataset Variables

[cite\_start]The analysis is based on a dataset that includes the following key variables[cite: 57]:

| Variable Name | Description |
| :--- | :--- |
| `Date` | [cite\_start]The date of the observation[cite: 59]. |
| `Recession` | [cite\_start]A binary variable (1 = recession period, 0 = normal period)[cite: 60]. |
| `Automobile Sales` | [cite\_start]The number of vehicles sold during the period[cite: 64]. |
| `unemployment rate` | [cite\_start]The monthly unemployment rate[cite: 66]. |
| `Advertising_Expenditure` | [cite\_start]The advertising expenditure of the company[cite: 71]. |
| `Vehicle_Type` | [cite\_start]The type of vehicles sold (e.g., Supperminicar, Sports, Executivecar, etc.)[cite: 72]. |

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