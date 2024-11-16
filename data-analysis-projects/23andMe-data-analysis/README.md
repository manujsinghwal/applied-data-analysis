# 23andMe Data Analysis
\
![image](https://github.com/manujsinghwal/23andMe-data-analysis/assets/40256851/1e03cb3b-3532-4524-8f2d-35c5a09232c0)
\
**Assignment:**
\
Please answer the questions below based on the data provided:

1. Plot daily sales for all 50 weeks.
2. It looks like there has been a sudden change in daily sales. What date did it occur?
3. Is the change in daily sales at the date you selected statistically significant? If so, what is the p-value?
4. Does the data suggest that the change in daily sales is due to a shift in the proportion of male-vs-female customers? Please use plots to support your answer (a rigorous statistical analysis is not necessary).
5. Assume a given day is divided into four dayparts:
\
a. night (12:00AM - 6:00AM),
\
b. morning (6:00AM - 12:00PM),
\
c. afternoon (12:00PM - 6:00PM),
\
d. evening (6:00PM - 12:00AM).
\
\
What is the percentage of sales in each daypart over all 50 weeks?

**Data Description:**
\
The datasets/ directory contains fifty CSV files (one per week) of timestamped sales data. Each row in a file has two columns:

1. `sale_time` - The timestamp on which the sale was made e.g. 2012-10-01 01:42:22
2. `purchaser_gender` - The gender of the person who purchased (male or female).
