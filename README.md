## Boat Sales Analysis
The objective of the project is to examine the website's traffic by analyzing customer visits, specifically those interested in viewing boats available for sale. The process involves employing machine learning techniques to explore and enhance the dataset. This includes data cleaning to create a refined dataset suitable for analysis, followed by the selection of a predictive model for forecasting future website views. Subsequently, the data is analyzed using Jupyter, and the findings are presented through an interactive dashboard. This dashboard visually highlights the outcomes of a sophisticated exploratory analysis conducted in Python. The dataset represents the sales information of used boats listed on a website. The website allows users to advertise their used boat for sales. This allows prospective buyers to have a ﬁrst impression about the boat, its manufacturing details, present conditions as well as listing price. The marketing has requested for the sales analysis in preparation of a weekly newsletter. Essentially, this analysis would help sellers by giving them insights on how they could get more engagement for listed boats, as well as stay on top of the market trends.  
## Data Sources  
The data for this project is an open source data downloaded from [boatsales](https://www.kaggle.com/datasets/karthikbhandary2/boat-sales/download?datasetVersionNumber=1)  

## Data Cleaning and Data Consistency Checks  
1.	Adjust the data type  
2.	Convert the prices to a single currency  
3.	Extract the country and city from the location  
4.	Check for missing data  
5.	Check for duplicate data  
6.	Check for mixed data type  

## Data Proﬁle. 
Number of rows and columns in the cleaned dataset: 6001 x 11 (original data is, 9888 x 10)  

## Ǫuestions to Explore. 
Characteristics of the most viewed boat listing in the last 7 days <br> 
What is the price of boat that get the most views?  <br>
Are there common features among the most viewed boats?<br>  
What is the location of the most viewed boat?  <br>

## Exploring Relationships  
- Conduct exploratory visual analysis using relevant Python libraries.  
- Use the questions defined in the previous task to guide your exploration.  
- If possible, define hypotheses to test.  

## Geographical Visualizations with Python  
- Obtain a shapefile containing location information aligned with the main project dataset's location data.
- Process, clean, and integrate data files in readiness for analysis.
- Perform a geospatial analysis by constructing a choropleth map using appropriate 
## Supervised Machine Learning: Regression  
- Formulate a hypothesis.
- Choose the pertinent variables.
- Organize the data for regression analysis.
- Divide the data into two subsets: a training set and a test set.
- Perform a linear regression on the data and assess the statistical indicators of the model's performance.  

## Unsupervised Machine Learning: Clustering  
- Organize the data for cluster analysis.
- Employ the elbow technique to identify the most suitable number of clusters.
- Execute the k-means algorithm.
- Append a new column to the dataframe indicating the assigned clusters.
- Generate diverse visualizations based on the clustered data.
- Compute descriptive statistics for the clusters using the groupby() function and elaborate on the findings, along with suggesting potential next steps. 


## Creating Data Dashboards in [Tableau](https://public.tableau.com/app/profile/hadeel.ghurab/viz/Boatsalesanalysis/Boatsales).  
- Define the use-case for the dashboard.  
- Outline dashboard contents based on curated results of analysis.  
- Create dashboard/storyboard in Tableau per the requirements in the project brief.  
- Publish a storyboard to Tableau Public.  

## Limitation and Ethics. 
-	The boat prices were presented in various currencies, creating challenges in comparing prices across different listings. 
-   The boat locations were specified with both the country and imprecise location details, which lacked consistency across all the listings.


