# IBM SkillsBuild Assignments
IBM SkillsBuild Assignments (Data Science)
[![FUNDAE](https://www.fundae.es/ResourcePackages/Fundae/assets/dist/images/logo_fundae.svg)](https://www.fundae.es/)

I am writing to express my sincere gratitude to [FUNDAE](https://www.fundae.es/) for the generous funding of my scholarship. Your support has made a significant impact on my educational journey, allowing me to pursue my studies with greater focus and determination.

I truly appreciate the opportunity that provided me, and I am committed to making the most of this chance. Thank you once again for your belief in my potential and for your invaluable support.

Truly thanks,

* To read this document in Spanish, please click on the link -> [LEAME_ESPAÑOL_CASTELLANO.md](LEAME.md)

## Introduction to data science 
- [Data Science Tools and Ecosystem](DataScienceEcosystem.ipynb)   
  An introduction to the uses and features of Jupyter Notebook

- [Project: House Sales in King County, USA](House_Sales_in_King_Count_USA-20231003-1696291200.jupyterlite.ipynb)   
  In this project, we highlight some of the most important modules used in data science within the Python ecosystem, including NumPy, Scikit-learn, Pandas, Matplotlib, and Seaborn. The commits for this project involved utilizing historical house pricing data to explore and fit the data to various models.

- [Project part I: Graphics Visualizations in Python ](DV0101EN-Final-Assignment-Part1-v2.ipynb)   
  We create and explore visualizations using Matplotib, Seaborn and Folium for mapping. 

- [Project part II: Graphics Visualizations in Python](DV0101EN-Final-Assign-Part-2-Questions_last.py)   
  In this section of the project, we create a dashboard using Dash and Plotly.

- [Project: Scrapping and Visualizing Stock Data](Final%20Assignment.ipynb)  
  This project consist in 2 parts:
  + We extract the stock price of Tesla, Inc. (TSLA) from Yahoo Finance using the yfinance module. Additionally, we utilize BeautifulSoup to scrape and refine the data extraction process.
  + Next, we performed various computations and transformations using Pandas to analyze and visualize stock prices, allowing for effective comparisons within the stock market.

- [Final Project: Classification with Python](ML0101EN_SkillUp_FinalAssignment.jupyterlite.ipynb)   
In this project, we implemented several fundamental machine learning algorithms for classification, including Linear Regression, K-Nearest Neighbors (KNN), Decision Trees, Logistic Regression, and Support Vector Machines (SVM).

- [Assignment: Notebook for Graded Assessment](mod5-final-project-v2.ipynb)   
The assignment involves socio-economic data from the city of Chicago. We load three datasets into separate tables within a SQLite database and execute SQL queries to address the questions posed in the assignment.

## Data Science Capstone (Space X Falcon 9 First Stage Landing Prediction)
In this capstone project, we aim to predict whether the Falcon 9 first stage will land successfully. SpaceX advertises its Falcon 9 rocket launches at a cost of $62 million, significantly lower than other providers, which charge upwards of $165 million per launch. A substantial portion of these savings is attributed to SpaceX's ability to reuse the first stage of the rocket. By accurately predicting the success of the first stage landing, we can gain insights into the overall cost-effectiveness of a launch.

- [Collecting the data](Data%20Science%20Capstone/01_SpaceX_Data_Collection_API.ipynb)   
In this lab, we perform a GET request to the SpaceX API, followed by essential data wrangling and formatting to prepare the data for analysis.

- [Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia](Data%20Science%20Capstone/02_SpaceX_Web_Scraping.ipynb)  
In this lab, we will conduct web scraping to gather historical launch records of the Falcon 9 from the Wikipedia page titled "List of Falcon 9 and Falcon Heavy Launches."
 
- [Data wrangling](Data%20Science%20Capstone/03_SpaceX_Data_Wrangling.ipynb)  
In this lab, we perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.  

- [Assignment: SQL Notebook for Peer Assignment](Data%20Science%20Capstone/04_SpaceX_EDA_SQL.ipynb)  
In this Python notebook we:
  + Understand the Spacex DataSet
  + Load the dataset into the corresponding table in a Db2 database
  + Execute SQL queries to answer assignment questions

- [Assignment: Exploring and Preparing Data](Data%20Science%20Capstone/05_SpaceX_EDA_Data_Visualization.ipynb)  
We conduct Exploratory Data Analysis (EDA) and Feature Engineering using Pandas and Matplotlib, focusing on the following key areas:
  + Exploratory Data Analysis (EDA): Analyzing and visualizing the data to uncover patterns and insights.
  + Data Preparation: Cleaning and organizing the data for analysis.
  + Feature Engineering: Creating and selecting relevant features to enhance model performance.

- [Launch Sites Locations Analysis with Folium](Data%20Science%20Capstone/06_SpaceX_Interactive_Visual_Analytics_Folium.ipynb)  
In the previous exploratory data analysis labs, you have visualized the SpaceX launch dataset using matplotlib and seaborn and discovered some preliminary correlations between the launch site and success rates. In this lab, you will be performing more interactive visual analytics using Folium.  

  This analysis contains the following tasks:
  + Mark all launch sites on a map
  + Mark the success/failed launches for each site on the map
  + Calculate the distances between a launch site to its proximities

-  [Making a interactive Visual dashboard](Data%20Science%20Capstone/07_SpaceX_Interactive_Visual_Analytics_Plotly.py)  
In our analysis of rocket launches, we utilize Plotly and Dash to create interactive visualizations that effectively illustrate the relationships between different launching features. Plotly, a powerful graphing library, allows us to generate a variety of dynamic charts and graphs, making it easy to visualize complex data. Dash, a web application framework built on top of Plotly, enables us to build interactive dashboards that allow users to explore the data in real-time. By integrating these tools, we can analyze key features such as launch dates, rocket types, payload capacities, and success rates. Users can interact with the visualizations, filtering data and adjusting parameters to gain insights into trends and patterns in rocket launches.

- [Assignment: Machine Learning Prediction](Data%20Science%20Capstone/08_SpaceX_Predictive_Analytics.ipynb)  
We perform exploratory Data Analysis and determine Training Labels by:
  * Creating a column data for the contructs a class or target
  * Standardize the data columns
  * Spliting training data and test data

- [Final Report with insigths and recomendation](Data%20Science%20Capstone/SpaceX_capstone-coursera_report_rfigueroa.pdf)  
Finally, we compile a comprehensive summary report that outlines the key insights and results from our analysis of X Space's rocket launches. This report highlights significant trends, performance metrics, and factors influencing launch success, providing a clear understanding of the operational effectiveness and strategic implications for future missions.

**(*)As a final note**: We encourage you to copy and experiment with the provided Python code in this repository. This hands-on approach will help you deepen your understanding of the concepts we've covered. Learning by example is an effective and ethical way to reinforce your knowledge and clarify any areas that may be less familiar. However, please ensure that you do not engage in plagiarism when seeking certification. Use this code as a learning tool to enhance your skills. Happy coding :muscle:!
