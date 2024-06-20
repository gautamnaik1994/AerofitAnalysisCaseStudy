# Aerofit Case Study

## Business Problem

To improve product recommendations for new customers, AeroFit's market research team aims to determine the unique characteristics of the target audience for each treadmill model. The team will investigate potential differences in customer demographics, preferences, and behaviours across various treadmill types to tailor recommendations more effectively.
Following is their product portfolio

* The KP281 is an entry-level treadmill that sells for $1,500.
* The KP481 is for mid-level runners that sell for $1,750.
* The KP781 treadmill has advanced features that sell for $2,500.

## Solution

To overcome challenges, Aerofit relies on skilled data analysts. Their data-driven approach involves analyzing historical data to gain actionable insights for decision-making. Through this analysis, they uncover patterns, trends, and viewer preferences, enabling Aerofit to determine suitable product recommendations for customers. Furthermore, data analysis enables the company to optimize its sales strategy based on customer type, fostering global business growth.
Utilizing Python, Pandas, Seaborn, and Matplotlib for data analysis and visualization, I conducted an in-depth analysis of the Aerofit data provided by Kaggle. The primary objective of this analysis was to gain insights into the following aspects:

* Identification of the most popular product among all users.
* Comparison of product preferences between single and married individuals.
* Exploration of product preferences based on gender (female and male users).
* Examination of the impact of factors such as education, income, fitness level, and age on product selection.

## Metric

We will use the count of users, probabilities, and conditional probabilities to evaluate the users.

## Data Description

The dataset consists of sales data for Aerofit products

<table>
  <tbody>
      <tr>
          <th>Attribute</th>
          <th>Details</th>
      </tr>
      <tr>
          <td>Product Purchased</td>
          <td>KP281, KP481, or KP781</td>
      </tr>
      <tr>
          <td>Age</td>
          <td>In years</td>
      </tr>
      <tr>
          <td>Gender</td>
          <td>Male/Female</td>
      </tr>
      <tr>
          <td>Education</td>
          <td>In years</td>
      </tr>
      <tr>
          <td>Marital Status</td>
          <td>Single or partnered</td>
      </tr>
      <tr>
          <td>Usage (per week)</td>
          <td>The average number of times the customer plans to use the treadmill each week</td>
      </tr>
      <tr>
          <td>Income ($)</td>
          <td>Annual income (in $)</td>
      </tr>
      <tr>
          <td>Fitness (1-5)</td>
          <td>Self-rated fitness on a 1-to-5 scale, where 1 is poor shape and 5 is excellent shape</td>
      </tr>
      <tr>
          <td>Miles (per week)</td>
          <td>The average number of miles the customer expects to walk/run each week</td>
      </tr>
  </tbody>
</table>

## Exploratory Data Analysis

I have conducted Exploratory Data Analysis (EDA) on each column in the dataset. This involved generating histograms, countplots, box plots, and line plots. Additionally, I used pair plots and correlation plots to examine relationships between columns. This EDA process gave me a deeper understanding of each column and the relationships between pairs of columns.

## My Recommendations For Aerofit

* Based on the data, KP481 (mid-level) and KP281 (entry-level) share a similar user base.
* To enhance the value proposition of KP481, certain features from KP781 (top-level) can be incorporated. This strategic move will entice users to opt for KP481, offering better value for a slightly higher price. Over time, as popularity grows, the price can be adjusted accordingly.
* To boost sales of KP781, female users can be targeted with exclusive discounts, making the product more appealing and accessible to this demographic.
