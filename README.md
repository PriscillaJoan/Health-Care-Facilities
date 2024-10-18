**Project Title:** _(Health Care Analysis)_

## Project Overview

The Health Care Solutions project leverages data science techniques to analyze and visualize healthcare data. The goal is to identify patterns, trends, and areas for improvement within healthcare facilities. The project includes an analysis of healthcare facilities, population data, and health-related metrics.

## Data Sources

The data used in this project comes from various sources:

- **ehealth-kenya.xls**: Contains detailed information about healthcare facilities in Kenya.
- **population.csv**: Contains population data used to provide context and insights into healthcare needs.

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository**:

   ```
   git clone https://github.com/PriscillaJoan/Health-Care-Facilities.git
   ```

2. **Navigate to the project directory**:

   ```
   cd Health-Care-Solutions
   ```

## Usage

To run the project and see the analysis:

1. **Open the Jupyter Notebook**:

   ```
   jupyter notebook
   ```

2. **Navigate to the `final workbook.ipynb` notebook** in the Jupyter interface and run the cells to execute the analysis and generate visualizations.

---

### Key Features:
- **SQL Database**: Contains health facility data in a structured format, with several tables for querying.
- **Jupyter Notebook**: Includes data analysis, visualizations, and queries for examining health facility characteristics.
- **Image Representation**: Visualizes the distribution of data in the database (e.g., bed capacities, IPD availability, types of hospitals).
- **Tableau Story**: Provides a detailed story about the different insights captured from the data.
- **Data Base Image**: Visualizes the different relationships between tables.

---
## Project Structure

This repository contains the following files:

1. **`final workbook.ipynb`**: Jupyter Notebook file with the data analysis, SQL queries, and visualizations.
2. **`database.sql`**: The SQL file containing the database schema and initial data setup.
3. **`data_distribution.png`**: Image showing the different relationships between tables.
4. **`table_story.txt`**: A link containing  the tableau story showing the different insights captured from the data.
5. **`Health Facilities Analysis.pptx`**: The power point presentation.

---

## Requirements

Before running the project, ensure you have the following installed:

- **Jupyter Notebook** (or any IDE that supports `.ipynb` files)
- **SQLite/MySQL/PostgreSQL** (depending on the database system you're using)
- **Pandas**, **Seaborn**, **Matplotlib** (for data visualization)

---

## Data Base Design Image

Here is a brief description of the tables in the database:

- **Table 1 (Health Facilities)**: Contains information about health facilities, including their names, types, and locations.
- **Table 2 (Services info)**: Lists the services provided by each facility, such as IPD, ART, and maternity services.
- **Table 3 (Staff Info)**: Has information about the staff.
- **Table 4 (Operations Info)**: Has information about the time of operations for the facilities

---

## Usage

To interact with the project, follow these steps:

- **SQL Queries**: Use the SQL queries in the Jupyter Notebook or directly query the database using your SQL tool (MySQL Workbench, SQLite Browser, etc.).
- **Visualizations**: The Jupyter Notebook includes several plots and graphs that visualize the distribution of data such as bed capacity,ownership and service availability.
- **Database Insights**: Read the `data base design.png` image to understand the structure and purpose of each table in the database.

---

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. We welcome any improvements or suggestions!

---
