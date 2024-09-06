### Name: Priyanshu Kumar
### Company: CODTECH IT SOLUTIONS
### ID: CT08DS6396
### Domain: Data Analytics
### Duration:  August 2024 to September 2024
### Mentor: Muzammil Ahmed
#


# Mall Customers Dataset - Exploratory Data Analysis (EDA)

# Overview
This project involves an exploratory data analysis (EDA) of the Mall_Customers.csv dataset. The dataset contains information about mall customers, including their age, gender, annual income, and spending score. The goal of this analysis is to uncover patterns, relationships, and insights within the data using various data visualization and analysis techniques.

# Dataset Description
The dataset contains the following columns:

CustomerID: Unique identifier for each customer.
Genre: Gender of the customer (Male/Female).
Age: Age of the customer.
Annual_Income_(k$): Annual income of the customer in thousands of dollars.
Spending_Score: Spending score assigned to the customer, likely based on their purchasing behavior.



# EDA Summary
1. Data Overview
The dataset contains 200 records with no missing values.
The average age of customers is approximately 38.85 years.
The average annual income is $60.56k.
The spending score has an average of 50.2.
2. Distributions
Age: The age distribution is somewhat normal but slightly right-skewed, with most customers aged between 28 and 49 years.
Annual Income: The income distribution is fairly uniform, with a slight concentration around $40k to $80k.
Spending Score: The spending score distribution is spread out, indicating diverse spending behaviors among customers.
3. Visualizations
Histograms: Visualized the distribution of age, annual income, and spending score.
Scatter Plots: Examined the relationships between age vs. spending score and annual income vs. spending score, with gender as a hue.
Box Plots: Detected outliers in age, annual income, and spending score.
Pair Plot: Explored relationships between age, income, and spending score, categorized by gender.
Gender Distribution: Visualized the distribution of male and female customers.
Gender vs. Spending Score & Annual Income: Compared spending score and annual income between male and female customers.


# Technologies Used
#### Python: For data manipulation and analysis.
#### Pandas: For data manipulation and preprocessing.
#### Seaborn & Matplotlib: For data visualization.


# Key Insights
Customer Demographics:

Majority of customers are in the age group of 28-49 years.
Annual income is uniformly distributed with a slight concentration in the mid-range.
Spending Behavior:

Spending score does not show a strong correlation with age or annual income.
Both male and female customers exhibit diverse spending patterns, with no significant differences observed in spending score based on gender.
Outliers:

Some outliers were detected in the spending score and annual income, which could represent high-spending or low-spending customers.

## Visualizations

### Age, Annual Income, and Spending Score Distributions
![Age, Annual Income, and Spending Score Distributions](https://github.com/Priyanshu9528/CODTECH-Task1/blob/main/fig3.png)

### Distribution of Spending Score by Gender
![Spending Score by Gender](https://github.com/Priyanshu9528/CODTECH-Task1/blob/main/fig4.png)

### Pair Plot of Customer Data
![Pair Plot](https://github.com/Priyanshu9528/CODTECH-Task1/blob/main/pairplot.png)

### Annual Income Distribution
![Annual Income Distribution](https://github.com/Priyanshu9528/CODTECH-Task1/blob/main/Annual%20Income%20Dist%20plot%20.png)

# Conclusion
This EDA provides a comprehensive understanding of the mall customers' demographics and spending behaviors. The insights gained from this analysis can be leveraged for customer segmentation, targeted marketing strategies, and enhancing the shopping experience.
