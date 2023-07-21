# A4-InstacartGroceryBasketPythonAnalysis
Instacart, an online grocery store's stakeholders are most interested in the variety of customers in their database and their purchasing behaviors. This analysis will provide insights for a planned **targeted marketing strategy**, to ensure Instacart targets the right customer profiles with the appropriate product campaigns

## Objective
This analysis aims to perform an initial exploratory analysis of Instacart's historical data, uncover existing sales patterns to develop insights, and recommend strategies to the Instacart marketing team. This would help the better segmentation of customers by the marketing team to improve sales based on particular shopping behaviors

## Data
We were provided with open-source data sets that contain sales information from Instacart. Additional customer data was provided by Careerfoundry

- Orders
- Orders_products_prior
- Products
- departments
- Customers

**Source**: Full details of data are available [here]([www.instacart.com/datasets/grocery-shopping-2017](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis))

## Project folder 
The project folder has 5 subfolders
- **Project Management**: Contains the Project Brief
- **Data**: Stored both Original(dataframes before cleaning) and Prepared Data(data frames after cleaning and prepared for analysis). 
- **Scripts**: Contains all the Python codes written for the entire analysis
- **Analysis**: Contains the Visualizations from which insights were developed
- **Sent to client**: Stored the final report that was sent to the client

  ## Tools
- Language: Python
- Libraries: Pandas, Numpy, Seaborn, Matplotlib, and Scipy
- Software: Jupyter Notebooks and Excel

## Skills Demonstrated
- **Data Cleaning**: removed duplicates, found and resolved missing values, and addressed mixed or incorrect data types
  
- **Dataframes Merging**: selected and prepared dataframes for merging, merged, and exported the final merged dataframe in suitable formats
  
- **Exploratory analysis**: performed descriptive statistics (max/min, quartiles, mean, standard deviation) for each variable as well as using histograms, scatterplots, and bar and line charts to explore data distribution
  
- **Derived new variables**: grouped data by user, order, and department to allow exploration and analysis at each level; used aggregated data to create flags about user ordering habits (such as ‘new customer’, ‘loyal customer’, etc.). Used demographic info; confirmed the new data created via crosstabs and value counts

- **Visualizing data**: used Matplotlib and Seaborn to create histograms, line charts, pie charts, and bar charts (vertical/horizontal and stacked)

- **Reporting results**: prepared an Excel document that reported the analysis processes, and the answers to business questions from Instacart's sales/marketing department and recommendations
