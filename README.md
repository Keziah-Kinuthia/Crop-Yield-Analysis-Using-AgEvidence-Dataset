# Crop Yield Analysis Using AgEvidence Dataset
### Project Overview
This project focuses on analyzing the impact of intercropping compared to monocropping on crop yields in Kenya using the AgEvidence dataset. The dataset provides insights into environmental and agronomic outcomes of regenerative agricultural practices, specifically emphasizing reduced tillage, continuous plant cover, and nutrient management. Data is sourced from peer-reviewed literature, ensuring reliability and relevance to agricultural practices in Kenya.

### Data Sources
AgEvidence Dataset

### Tools
Programming Language: Python
[Download here]()

### Data Cleaning and Preparation
The Data Cleaning and Preparation phase aims to ensure that the AgEvidence dataset is ready for analysis. This includes handling missing data, removing duplicates, and transforming data into a suitable format for statistical analysis.

#### Steps Taken
1. Data Loading: The primary dataset, ContinuousCover_Kenya_Results.csv, was loaded into a Pandas DataFrame for initial inspection.
2. Handling Missing Data: Identified and handled missing values by either imputing with appropriate measures
3. Data Formatting: Ensured all columns were correctly typed (e.g., numeric columns for quantitative data, categorical columns as appropriate).
4. Removing Duplicates: Checked for and removed any duplicate entries in the dataset to maintain data integrity.
5. Data Filtering: Filtered the dataset based on relevant variables (e.g., group_level1 = Crop Yields, group_level2 = Yields) to focus specifically on crop yield data.

6. ### Questions that Guided the Exploratory Data Analysis (EDA) helps you understand the dataset and discover patterns, trends, and relationships within the data.
7. 1.  What is the structure of the dataset?
     - How many rows and columns are there?
    -  What are the data types of each column?
  
   2. Are there missing values?
      - Which columns have missing values?
      - What percentage of values is missing in each column?
     
  3. What crops are used in monocropping and intercropping?
4. How do crop yields for monocropping and intercropping compare?

### Results and Findings

#### Independent T-test was used to test if there was a statistically significant difference between the mean of the two groups. On the other hand, The Levene test was used to test the Homogeneity of Variance between the two groups
The p-value of 0.7965 is greater than the significance level of 0.05, indicating no statistically significant difference in mean crop yields between intercropping and monocropping. The Levene test also shows that variances between the two groups are equal, further supporting these findings. Therefore, yield means and variances do not significantly differ between the two farming methods in the analysed dataset.

### Conclusion

Statistical Analysis: The comparison of crop yields between intercropping and monocropping methods yielded a non-significant p-value of 0.7965 (α = 0.05). This suggests that there is no statistically significant difference in mean crop yields between the two methods.

Visual Analysis: Visual examination of the data indicates that intercropping tends to result in more variable outcomes compared to monocropping. This variability suggests potential for both higher yields and higher risks under different conditions.

Conclusion: Based on both statistical and visual analyses, it is concluded that while intercropping does not show a statistically significant advantage in mean crop yields over monocropping, its potential benefits, such as increased yield variability, should be weighed against higher management complexity and associated risks. Effective implementation of intercropping may require tailored management strategies to optimize outcomes under varying agricultural conditions



  

  

