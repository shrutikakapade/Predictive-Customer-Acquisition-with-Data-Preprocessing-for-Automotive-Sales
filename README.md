<h2>Title: Predictive Customer Acquisition with Data Preprocessing for Automotive Sales</h2>
<h3>Introduction: </h3>
This project focuses on building a machine learning model to predict customer whether a customer will buy their car or not, using extensive data preprocessing practices to enhance accuracy. the model identifies potential buyers, enabling the company to design targeted ad campaigns and personalized marketing. This approach optimizes marketing efforts, increases conversion rates, and reduces costs by concentrating on high-potential customers.
<h3>Data Preprocessing: </h3>
<h4>Dealing with Missing Data</h4>

<ol> 1. Data Removal : Remove the row which have missing data only when there are less rows which are missing from a large dataset <br><br>
2. Data Fill using Statistical Imputation: Fill the missing data by taking the mean or median of the available data points.<br><br>
3. Data Fill using Regression: Use regression analysis to find the most probable data point for filling in the dataset.</ol>
<h4>Go to browser and search ---> https://scikit-learn.org/stable/ --->Search for simpleimputer </h4>
<li>In the model we use simpleimputer it is a Univariate imputer for completing missing values with simple strategies.
<li>Replace missing values using a descriptive statistic (e.g. mean, median, or most frequent) along each column, or using a constant value.
<br>
<h3>Dealing with Categorical Data: </h3>
  <h4>Go to browser and search ---> https://scikit-learn.org/stable/ --->Search for One Hot Encoding  </h4>
<ol> 1. One Hot Encoding :Encode categorical features as a one-hot numeric array. 
India : 0001 ,Thailand : 0010 <br>
2. Binary Encoding : Yes : 1 , No : 0
