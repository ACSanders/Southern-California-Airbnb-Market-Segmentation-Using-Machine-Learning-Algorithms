# Southern-California-Airbnb-Market-Segmentation-Using-Machine-Learning-Algorithms
This project leverages K-means clustering and Principal Component Analysis to perform market segmentation on Airbnb datasets.

# Author
Adam C. Sanders, Ph.D.

# Project Description
This project leverages machine learning algorithms to perform market segmentation based on several Airbnb datasets. First, I clean and process datasets containing information on Airbnb listings in the Los Angeles and San diego areas. Second, I perform initial exploratory data analysis. Third, I implement K-means clustering and Principal Component Analysis to identify several meaningful clusters of Airbnb listings. Finally, I create several advanced visualization using both geo-spatical data and the results of my analyses.

# Business Case
Airbnb wants to perform market segmentation on several rental properties located in the Southern California area. Specifically, the organization wants to segment the market of Airbnb listings in the Los Angeles and San Diego metropolitan areas. The goal is to segment the existing listings in these areas based on several shared features that might interest different groups of customers. These features include things like price, availability, and popularity.

Ideally, Airbnb would like to establish the following types of segments:

1. Budget-friendly listings
2. High-end listings
3. Popular listings
4. Extended stay listings
5. Accessible listings

Establishing these market segments has several benefits. By establishing the aforementioned segments, Airbnb can design marketing strategies, advertisements, and promotions that will effectively target specific groups of customers.

# Main Problem and Challenges
I need to surmount several challenges. First, I need to gather, clean, and process Airbnb datasets that contain information about the specific Airbnb listings in the San diego and Los Angeles areas. Second, I need to perform market segmentation based on the data. This requires exploratory data analysis and the implementation of several machine learning algorithms. To carry out this task, I will employ K-means clustering and Principal Component Analysis. Finally, I need to identify any meaningful segments that will help achieve the overall aim described in the business case.

# Strategy and Methodology
**Strategy:** 
I will employ an unsupervised machine learning algorithm called, "K-means clustering" to segment Airbnb properties into distinct groups with shared features. From those groups, I will attempt to identify the key segments mentioned in the Business Case section. Afterwards, I will apply dimensionality reduction by implementing the machine learning algorithm called, "Principal Component Analysis" (i.e., PCA). Finally, I will create several advanced visualizations that illuminate several important aspects in the data.

**Methodology:** 
I will utilize several data science tools, techniques, and methods to carry out the strategy and solve the business problem. This project will proceed as follows.

1. Import libraries and data.
2. Perform initial exploratory data analysis and create basic data visualizations.
3. Clean, merge, and process the data for the application of the K-means clustering algorithm.
4. Determine the optimal number of clusters using the elbow method.
5. Train and implement the K-means clustering algorithm.
6. Locate and identify the clusters that contain the groups of primary interest.
7. Implement the Principal Component Analysis algorithm to perform dimensionality reduction.
8. Create advanced visualizations using the clusters and geo-spatial data.
9. Summarize the project and the results.

# Dependancies, Libraries, and Modules
This project uses Python 3, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Folium.

# Acknowledgements
Special thanks to *Inside Airbnb* for providing the relevant datasets. The datasets for Los Angeles and San Diego Airbnb listings can be accessed here: http://insideairbnb.com/

**Note:** The datasets were accessed in November 2020.

# License
MIT
