# 🥑 Avocado Price Prediction Using Linear Regression

## Project Overview
<p>This project focuses on predicting avocado prices using linear regression. The analysis explores the relationships between avocado price, sales volume, revenue, and other factors across different regions and time periods.</p>

## Dataset
<p>The dataset includes historical data on avocado prices and sales, with features such as <code>AveragePrice</code>, <code>Total Volume</code>, <code>type</code>, <code>region</code>, <code>year</code>, <code>month</code>, and <code>Revenue</code>.</p>

## Data Preprocessing
<ul>
    <li><strong>Encoding:</strong> Categorical variables were encoded.</li>
    <li><strong>Scaling:</strong> Numerical features were scaled using Min-Max scaling.</li>
    <li><strong>Feature Engineering:</strong> Additional features like <code>Revenue</code> were created.</li>
</ul>

## Exploratory Data Analysis (EDA)
<p>Performed to identify trends, seasonal patterns, and correlations within the data.</p>

## Model Development
<p>A linear regression model was built and trained on the processed data to predict avocado prices.</p>

## Model Evaluation
<ul>
    <li><strong>MSE:</strong> <code>7.83 × 10<sup>−12</sup></code></li>
    <li><strong>R-squared:</strong> <code>0.9999999999512731</code></li>
    <li><strong>Cross-Validation:</strong> Achieved a mean MSE of <code>1.53 × 10<sup>−11</sup></code> with a small standard deviation, confirming model robustness.</li>
</ul>

## Insights
<ul>
    <li><strong>Price vs. Volume:</strong> An inverse relationship was identified.</li>
    <li><strong>Seasonality:</strong> Prices peak towards the end of the year, while volumes decrease.</li>
    <li><strong>Type Comparison:</strong> Organic avocados consistently command higher prices.</li>
</ul>

## Technologies Used
<ul>
    <li><strong>Python:</strong> For data processing and model development.</li>
    <li><strong>Pandas, NumPy:</strong> For data manipulation and numerical computations.</li>
    <li><strong>Matplotlib, Seaborn:</strong> For data visualization.</li>
    <li><strong>scikit-learn:</strong> For machine learning model development.</li>
</ul>

## How to Run
<ol>
    <li>Clone the repository.</li>
    <li>Install required packages.</li>
    <li>Run the scripts or Jupyter notebooks.</li>
</ol>


