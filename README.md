
<h2>Title: Predictive Customer Acquisition with Data Preprocessing for Automotive Sales</h2>

<h3>Introduction: </h3>
<div>This project focuses on building a machine learning model to predict customer whether a customer will buy their car or not, using extensive data preprocessing practices to enhance accuracy. the model identifies potential buyers, enabling the company to design targeted ad campaigns and personalized marketing. This approach optimizes marketing efforts, increases conversion rates, and reduces costs by concentrating on high-potential customers.</div>
<h3>Data Preprocessing: </h3>
<h4>1. Dealing with Missing Data</h4>

<div><ol> 1. Data Removal : Remove the row which have missing data only when there are less rows which are missing from a large dataset <br><br>
2. Data Fill using Statistical Imputation: Fill the missing data by taking the mean or median of the available data points.<br><br>
3. Data Fill using Regression: Use regression analysis to find the most probable data point for filling in the dataset.</ol></div>
<h4>Go to browser and search ---> https://scikit-learn.org/stable/ --->Search for simpleimputer </h4>
<div><li>In the model we use simpleimputer it is a Univariate imputer for completing missing values with simple strategies.
<li>Replace missing values using a descriptive statistic (e.g. mean, median, or most frequent) along each column, or using a constant value.
<br> </div>
<h4>2. Dealing with Categorical Data: </h4>
  <h4>Go to browser and search ---> https://scikit-learn.org/stable/ --->Search for OneHot Encoding  </h4>
<ol> 1. OneHot Encoding :Encode categorical features as a one-hot numeric array. 
India : 0001 ,Thailand : 0010 <br>
2. Binary Encoding : Yes : 1 , No : 0 </ol>
<h4>3. Feature Scaling: </h4>
In feature scaling we try to find the patterns in data 
 
![Screenshot 2024-11-06 181457](https://github.com/user-attachments/assets/1ea6dd93-6202-4388-8caf-372a0902b3d1)

<br>
<div><h3><li>Understanding Normalization and Standardization in Data Preprocessing :</h3>
Normalization and standardization are two common data preprocessing techniques used in machine learning to transform features, making them easier to process by models. 
<br>

![Screenshot 2024-10-24 173025](https://github.com/user-attachments/assets/ea8a88b0-7718-49dd-a503-1a0ec421de5c)
<br>
1.The table on the left shows:
<li>Three people’s data, with attributes Age and Salary.
<li>Age is measured in years, while Salary is in currency units.
  <br><br>
2.The green and blue arrows highlight how values differ between individuals. The values next to the arrows represent the differences in each attribute:
<li>Age decreases by 1 or 3 years as we move from Person 1 to Person 3.
<li>Salary decreases by 7,000 and 3,000 units respectively.
  <br>
<h3>Normalization: </h3>
<h4>Purpose:</h4> Scales the data to a range of 0 to 1, useful when features have different ranges.
<h4>How It Works:</h4> Subtracts the minimum value of a feature (like Age or Salary) from each value, then divides by the range (difference between max and min). This ensures all values lie within the [0, 1] range.
<br>
<h3>Standardization: </h3>
<h4>Purpose:</h4> Centers data around a mean of 0 and a standard deviation of 1, useful when features have different scales but need to be compared directly.
<h4>How It Works:</h4> Subtracts the mean (μ) of the feature from each value, then divides by the standard deviation (σ). This rescales the data so that it has a mean of 0 and a standard deviation of 1.
<h3>Result after applying Feature Scaling: </h3></din>
   <br>

        
![Screenshot 2024-11-06 181652](https://github.com/user-attachments/assets/9ed87ea3-fef3-4b57-8899-2200854d6be2)
