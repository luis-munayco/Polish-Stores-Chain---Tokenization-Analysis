# Tokenization-Analysis
Polish Stores Chain - Tokenization Analysis

Analysis of occupied spaces of the beverages products categories in 711 stores in Phillipines. The aim of the project was determinated what would be the best distribution of products in all the stores to optimize the sales. For this purpuse, we analyzed data of millions of transactions (+ 10 GB) in all stores over the past 6 months. Data is stored in a Amazon Redshift Warehouse.

For our purpouse we are working with data of 5 beverages categories: Category 21: Juices and Teas/ Category 24: Softdrinks/ Category 27: Bottle Water/ Category 31: Dairy/ Category 32: Beer

Objectives and tasks:

Clean and standarize Dataset
Calculate key indicators: Daily Sales and Daily Sales/Width
Normalized Indicator in order to compare big stores with small stores
Create Exponential math model for the Daily Sales
Calculate optimized space by category by store
Software: 1- Python/ 2- PostgreSQL / 3- Power BI

The process begins with the data preparation. Transaction data is downloaded from an AWS Redshift data warehouse. For the analysis purpouse, six months of transaction data in the beverages categories are gathered and analyzed.


<img
  src="/Images/Matrix Correlation.JPG"
  alt="Matrix Correlation"
  title="Matrix Correlation"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
  
  <img
  src="/Images/Correlation Sales Beer.JPG"
  alt="Correlation Sales Beer"
  title="Correlation Sales Beern"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
