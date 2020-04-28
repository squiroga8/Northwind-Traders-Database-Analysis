
# Northwind Traders Database Analysis

## Project Set-Up

Contained in this repo are the following:

1. A **_Jupyter Notebook_** containing any code I've written for this project.
2. An **_"Executive Summary" PowerPoint Presentation_** that explains the hypothesis tests I ran, my findings, and their relevance to company stakeholders.
3. The **_Northwind SQL Database_** along with a visual schema of the databases included.
4. A **_py script for Welch's T-Test_** that I used in the analysis.

### Methodologies Used

- Hypothesis Testin
- Welch's T-Test
- Cohen's d
- ANOVA test
- Tukey's HSD Test

## Objective:

To conduct analysis using statistical analysis, hypothesis testing, and SQL on the Northwind Traders Database to identify areas for improved performance. This included targeted analysis of improvements to their discount system, employee performance monitoring, order processing time per shipping company, and understanding market demand for certain categories of goods.

### The Project

For this project, I worked with the Northwind database--a free, open-source dataset created by Microsoft containing data from a fictional company. Here's the schema for the Northwind database:

<img src='https://raw.githubusercontent.com/learn-co-curriculum/dsc-mod-3-project/master/Northwind_ERD_updated.png'>

At first, I set out to answer the following question: **_Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?_**  I then developed 3 other questions, along with corresponding null and alternative hypotheses per question.  


**_Findings_**
- With a discount, the average quantity ordered of a product is 27, compared to 22 without a discount.
- US employees manage an average order total of 121.2 orders, compared
to UK employees, who average 56 orders.
- Across the 3 Shipping Companies, United Package has the lengthiest processing time of 9.2 days on average, compared to Federal Shipping’s average of 7.5 days.
- There is no interaction between Category and Customer Region regarding Total Revenue per category.

