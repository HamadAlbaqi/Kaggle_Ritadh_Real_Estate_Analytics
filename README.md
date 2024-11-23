## 💡 Introdruon
- Riyadh's real estate market is dynamic and rapidly evolving. This project seeks to provide valuable insights into market trends, property prices, and key factors influencing Riyadh's real estate landscape. By leveraging Python's data analysis capabilities and Plotly's interactive visualization tools, we aim to uncover notable patterns and relationships within the data.

<div style="text-align: center;">
  <img src="https://storage.googleapis.com/kaggle-datasets-images/2623149/4482894/1dfb26becf747a0b196a41d51e031964/dataset-cover.jpg?t=2023-08-17-09-58-06" alt="Dataset Cover">
</div>

## 📊 Dataset Overview and Source:
- URL link : https://www.kaggle.com/datasets/reemamuhammed/riyadh-villas-aqar, Riyadh Villas Dataset is web scraped from Aqar.sa by **Reema Abuthnain**
- About the Dataset : This dataset contains over 50k villas located in Riyadh, Saudi Arabia. Each villa contains information such as the location, neighborhood, number of bedrooms, number of bathrooms, the space of the villa, and many more!
  
| Column Name    | Definition                                                                                           | Data Type      |
|----------------|------------------------------------------------------------------------------------------------------|----------------|
| front          | Orientation of the property's front side, indicating which direction it faces relative to the street.| object         |
| rooms          | Total count of bedrooms or main living spaces within the property.                                   | int64          |
| lounges        | Number of lounge or relaxation areas available in the property.                                      | object         |
| bathrooms      | Total count of bathrooms included in the property.                                                   | object         |
| streetWidth    | Measurement of the width of the street adjacent to the property.                                     | float64        |
| stairs         | Specifies if the property has staircases and their type, if present.                                 | float64        |
| driverRoom     | Indicates if there is a dedicated room available for drivers.                                        | float64        |
| SunLightRoom   | Presence of a room designed for ample natural sunlight.                                              | float64        |
| kitchen        | Total count of kitchens provided within the property.                                                | float64        |
| outdoorRoom    | Availability of outdoor or open-air spaces connected to the property.                                | float64        |
| garage         | Indicates whether a garage is available for vehicle parking.                                         | float64        |
| duplex         | Specifies if the property structure is a duplex with two separate units.                             | float64        |
| Area           | Total area or size of the property, measured in square units.                                        | int64          |
| apartments     | Number of individual apartment units or living spaces in the property.                               | object         |
| StaffRoom      | Presence of a designated room for staff or household workers.                                        | float64        |
| elevator       | Indicates if an elevator is present within the property.                                             | float64        |
| furnished      | Specifies if the property is offered as fully furnished.                                             | float64        |
| pool           | Indicates the availability of a swimming pool on the property.                                       | float64        |
| basement       | Specifies whether there is a basement or cellar space in the property.                               | float64        |
| neighbourhood  | General description of the surrounding area and neighborhood of the property.                        | object         |
| location       | More detailed information about the specific address or location of the property.                    | object         |
| price          | Listed cost or asking price for purchasing or renting the property.                                  | float64        |
| square_price   | Price per square unit of the property, providing a basis for comparison with other properties.       | float64        |


## 🌊 Data Flow and Steps:
1. **📚Import Software Libraries:**
    - Load necessary libraries such as pandas, numpy, matplotlib, seaborn, and Plotly for analysis and visualization.
2. **📂Read Dataset**
    - Import the dataset (e.g., CSV, Excel) into a pandas DataFrame for further processing.
3. **🔍Data Exploration (EDA)**
    - Explore the data by checking the first few rows, understanding data types, checking for missing values, and generating summary statistics.
4. **🧹Data Cleaning and Preprocessing**
    - Handle missing values, duplicate entries, outliers, and correct any inconsistencies in the data.
5. **📊Data Visualization**
    - Use visual techniques (e.g., histograms, scatter plots, box plots) to understand patterns, trends, and distributions in the data.
6. **🔄Change the Data Types**
    - Convert columns to appropriate data types (e.g., converting strings to datetime, categorical data to category type) for better analysis.
7. **✏️Rename Columns**
    - Rename columns for clarity, readability, or to match the required format for analysis or visualization.
8. **📈Data Analysis & Insights Finding**
    - Perform statistical and analytical techniques (e.g., correlation analysis, groupby operations) to extract meaningful insights.
9. **🚀Build and Run the Dashboard using Plotly-Dash**
    - Create an interactive dashboard using Plotly-Dash to visualize and present the results of your analysis dynamically.
10. **🌐Deploy the Dashboard on Render**
    - Deploy the Plotly-Dash app to Render, to make the interactive dashboard accessible and ready to use online.
