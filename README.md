# 👋 Welcome to My Data Science Portfolio

Hi, I’m **Nachiket Talwar** — this portfolio showcases real-world data science projects built across Python, R, SQL, and GIS environments. Each project demonstrates practical solutions to complex problems using domain-specific data, statistical modeling, spatial analytics, and interactive dashboards.

### 🔍 What You’ll Find Here:

* **Public Health Analytics**:
  An interactive R Shiny dashboard analyzing chronic disease risk factors like diabetes and heart disease using PCA, clustering, and comparative plots.

* **Property Investment Automation**:
  A Python-based CLI tool that streamlines property investment decisions with suburb summaries, currency conversion, and price distribution analysis.

* **Car Purchase Advisory System**:
  A simulated console program for car recommendations and retailer ordering, with business-hour logic and local file integration.

* **Transport Accessibility Mapping**:
  A spatial SQL and QGIS project comparing public transport coverage in two Melbourne suburbs using GTFS data, route clipping, and buffer-based accessibility zones.

### 💼 Tools & Skills Highlighted:

* Python (OOP, pandas, matplotlib, NumPy)
* R & R Shiny (ggplot2, plotly, clustering)
* SQL & PostGIS (spatial queries, buffers, intersections)
* QGIS (visual mapping)

Feel free to browse the repos or [connect with me on LinkedIn](https://www.linkedin.com/in/nachiket-tal/) to chat about data roles, projects, or collaboration.



## Automation of Property Investment (Python)

A Python-based, menu-driven console application designed to automate administrative tasks for a property investment company using real estate sales data from Melbourne. Built with object-oriented design principles, the program simplifies data analysis and investor decision-making.
Core Functionalities:
  * Data Import & Cleaning: Loads property data and prepares it for analysis.
  
  * Currency Conversion: Converts property prices to international currencies using dynamic exchange rates.
  
  * Suburb Summaries: Generates statistical summaries (mean, median, standard deviation, etc.) of property features by suburb.

  * Land Size Analysis: Computes average land size by suburb, handling unit variations and missing data.

  * Value Distribution: Visualizes property prices across suburbs using histograms (multi-currency support).

  * Sales Trend Visualization: Plots annual property sales trends via line charts.

  * Price Search Tool: Implements reverse insertion sort and recursive binary search to locate properties by price within a suburb.

This project showcases robust Python programming skills, data manipulation using pandas and NumPy, and visualization with matplotlib. The system demonstrates error handling, user input validation, and compliance with PEP 8 standards.


## Car Purchase Advisor System

A Python-based interactive command-line application that simulates a car dealership advisory and ordering system with built-in test data generation. 
Key features include:
* Automated Data Generation: On startup, randomized car stock data is created and stored in `stock.txt`, then loaded into program memory.

* Interactive Menu: 
      Users can:
        * Find the nearest car retailer based on postcode proximity.
        * Receive tailored car purchase advice from selected retailers.
        * Place car orders (validated against retailer business hours).
        * Exit the program.

* Retailer Search & Advice Options:   
    Includes:
      * Recommending a random car from stock.
      * Viewing all cars or filtering by type (e.g., “AWD”, “RWD”).
      * Displaying cars suitable for probationary licence holders.

* Order Processing: Validates input and operating hours before writing confirmed orders to `order.txt`.

This system showcases structured file handling, input validation, randomness, conditional logic, and menu-driven interaction.


## Chronic Diseases Risk Factor Dashboard (R Shiny)
![image](https://github.com/user-attachments/assets/86ab2460-a004-471d-abda-3af154b6c2f1)


An interactive R Shiny dashboard that visualizes key risk factors contributing to heart disease and diabetes. Designed for healthcare professionals and policymakers, the dashboard integrates choropleth maps, violin plots, pair plots, stacked area charts, and clustering analyses (PCA and K-means) to enable data-driven exploration and insight generation.
Key Features:
  * Exploratory Tabs: Heart Disease, Diabetes, and Comparative Analysis tabs, each featuring interactive charts and filters.
  
  * Visual Techniques: Uses ggplot2, Plotly, Leaflet, and DT to deliver dynamic visual narratives (e.g., gender-based comparisons, age distributions, symptom correlations).
  
  * Advanced Analytics: PCA and K-means clustering to uncover hidden patterns and similarities across diseases.
  
  * User-Centric Design: Built using Munzner’s What-Why-How framework and Gestalt principles for clarity and interactivity.

This project demonstrates end-to-end skills in data wrangling, interactive visualization design, statistical insight generation, and user-oriented dashboard development using the R ecosystem.

### Dashboard Visuals
![image](https://github.com/user-attachments/assets/299b2d3f-6357-491e-96ef-7d91cd5f565f)

![image](https://github.com/user-attachments/assets/910ace00-42fd-4046-8e97-61ee0d6f2c79)

![image](https://github.com/user-attachments/assets/3bd22080-7f57-49da-89cc-190feaf24695)

![image](https://github.com/user-attachments/assets/6f1042f4-81de-4e97-9acc-15665ee6513e)

![image](https://github.com/user-attachments/assets/3de943e9-0350-4c48-85fc-08148e9895ac)

![image](https://github.com/user-attachments/assets/237eb4c1-85a2-463a-b967-165eec348856)
![image](https://github.com/user-attachments/assets/dfcd594a-3851-4d39-ac43-5bfb0bc947db)


![image](https://github.com/user-attachments/assets/de15749e-4566-4947-8aa4-8b3da87625ea)
![image](https://github.com/user-attachments/assets/45b8173a-2943-41cd-a779-b01d987499c4)



## Route and Accessibility Analysis and Comparison (PostGIS + QGIS)

A spatial analytics project evaluating public transport accessibility in Burwood and Clayton South suburbs of Melbourne using SQL-based spatial queries and QGIS visualizations. 
The goal was to identify underserved zones and analyze differences between a university-centered suburb (Burwood) and a less transit-focused one (Clayton South).

Key Features:
  * Spatial Data Integration: Loaded and processed GTFS data and Australian suburb boundaries into PostgreSQL/PostGIS using `ogr2ogr`.
  
  * Transport Mode Analysis: Mapped tram, bus, and train routes within suburb boundaries using spatial clipping (`ST_Within`, `ST_Intersection`).
  
  * Accessibility Buffering: Created 500m buffer zones around stops/routes to determine walkable coverage areas.
  
  * Gap Identification: Calculated non-accessible regions using `ST_Difference`, highlighting transit service disparities.
  
  * Visualization: Developed thematic maps in QGIS for accessible vs. non-accessible zones and transport mode overlays.

The project demonstrates expertise in spatial SQL, geospatial data processing, and transport equity analysis using open-source tools and real-world datasets.

### Geospatial Analysis Visuals
![image](https://github.com/user-attachments/assets/91580c39-6f13-4dc6-8367-271362e0dc3d)

![image](https://github.com/user-attachments/assets/5b6b08a5-73df-41cc-8843-45b75ec75be4)

![image](https://github.com/user-attachments/assets/0ac20037-63e5-4226-b01b-c6db30c4e4f8)

![image](https://github.com/user-attachments/assets/37b409d7-4726-4851-afd5-8eeee68774eb)
