<h1>Cohort Analysis and Customer Segmentation</h1>

<h2>Table of Content</h2>

<ul>
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#statement">Problem Statment</a></li>
    <li><a href="#obj">Objectives</a></li>
    <li><a href="#metrics">Metrics Used</a></li>
    <li><a href="#tools">Tools Used</a></li>
    <li><a href="#details">Project details</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
</ul>

<a id="intro"></a>
<h2>Introduction</h2>

An e-commerce giant wants to improve its product offerings, customer relations and also maximize profit. To achieve this, the company wants to calculate the percentage of customers it's able to retain every month. The company also needs to segment its customers for target marketing and promotions.       
  
<a id="statement"></a>
<h2>Problem Statment</h2>

1. Calculate the percentage of customers the company is able to retain every month.
2. Segment the customers based on their behavior. The behavior under consideration includes customers' recent transactions with the company, the frequency of purchases, and how much each customer spends on the company products.
3. Analyze customer segments based on Recency, Frequency, and Monetary value.

<a id="obj"></a>
<h2>Objectives</h2>

The objectives of the project are:

1. To calculate customer retention rate.
2. To segment the customers based on their behaviour.
3. To analyze customer segments based on Recency, Frequency, and Monetary value with Power BI.

<a id="metrics"></a>
<h2>Metrics Used</h2>

<code>Recency (R)</code> refers to the days elapsed since the last purchase. It is calculated by deducting the date that the customer made the last purchase from the offset date (the assumed date when the analysis was carried out).

`Frequency (F)` refers to the total number of transactions a customer has made with the company. It represents how often a customer purchased a product/product from the company. It is calculated by counting the number of complete purchases a customer has made with the company.

`Monetary (M)` refers to the sum of a customer's monies on the company's products. It is calculated by multiplying the number of products by the unit price of products.

<a id="tools"></a>
<h2>Tools Used</h2>

The project was implemented using Python programming language and the following software and packages (libraries) were used:

<b>Softwares</b>

- Jupyter Notebook
- Power BI

<b>Libraries</b>

- Sickit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

<a id="details"></a>
<h2>Project Details</h2>

- __Cohort Analysis:__ Time-based cohort analysis was performed to calculate and visualize the retention rate for each cohort. This involves grouping the data frame by "CohortMonth" and "CohortIndex" columns, selecting the first column and storing it to cohort_sizes and then dividing the cohort count by cohort sizes along the rows.
- __Customer Segmentation:__ The customers were segmented based on their behaviour which includes recency, frequency, and monetary value. RFM analysis was performed to determine the customer segments. The data was visualized using a heatmap to show the relationship between recency, frequency, and monetary value. To determine each segment in terms of Platinum, Gold, Bronze, and Silver, the metric values were clustered and visualized using a snake plot.
- __[Power BI Customer Segmentation Analysis](https://app.powerbi.com/view?r=eyJrIjoiODVlOTFmZjYtYzRiNi00MTk0LWFhMDktOGJiMWEzNWJkYzNhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9):__ With the help of __Power BI__, the segmented customer base—`Platinum`, `Gold`, `Bronze`, and `Silver`—was further analyzed in order to gain a deeper understanding of the interactions between distinct clusters and the company through an interactive dashboard.

<a id="conclusion"></a>
<h2>Conclusion</h2>

The project has been successful in calculating customer retention rate, segmenting customers based on their behaviour, and analyzing customer segments based on Recency, Frequency, and Monetary value. The results obtained from the project can be used to make informed product decisions that will reduce churn and drastically increase revenue.
