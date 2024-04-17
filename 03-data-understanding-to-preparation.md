## Data Understanding
#### Understanding the data
- Use of descriptive statistics to understand data
- Univariate statistics
- Statistics such as mean, median, min, max, stddev
- Pairwise correlations, indicative of relationships worth further study, adjustments for potential confounding variables
- Histograms, graph that shows the frequency of numerical data using rectangles

### Look at data quality
- Missing values
- Invalid values
- Duplicate values
- Formatting issues

### Run an iterative process
- Collect data and understand in multiple iterations

## Data Preparation
- Cleansing data,
- Takes most time ~70-90% in data science project
- Analogy: it takes more time to chop onions but to cook a recipe the onion needs to be chopped
- Data understanding: What does it mean to "prepare" and "clean" the data?
- Data preparation: What are ways in which data is prepared?
- Feature engineering is the use of domain knowledge and expertise to enable machine learning process
- Feature engineering works like a funnel to identify and filter the best candidate variables to use in ML
- Randomly groups data can be divided into training set and testing set

### Case Study
- Define the precise CHF, be very precise as there are many types of CHF
- Define the CHF readmission criteria and use clinical expertise
- Collect and aggregate all available transactions and records of each CHF patient
- Standardize the data so each patient shared the same columns
- Run literary review to ensure data quality and correctness of procedures
- Consolidate all data into single table
- Define the target, patient features and diagnosis flags such us existing illness
- Divide dataset into trainig and testing sets

## Correlation /= Causation
- Correlation is when two things are related
- Data dredging represents analysis of data to find problem to solve instead of the other way around
- Correlation should lead to discovery of causation (strong cause and effect relationship)
- https://www.youtube.com/watch?v=VMUQSMFGBDo
- https://www.youtube.com/watch?v=7bT17r_yIrw

> While there is a correlation between ice cream and weight gain, it does not equal causation. Think of it a different way. If a person ate 500 calories of ice cream each day and nothing else they would lose weight. Ice cream is not the cause, it is the restricted number of calories causing the weight loss. The reverse holds true for weight gain. - @DecisionSkills / YT Channel

## Summary
- Data understanding covers tasks such as building the dataset and ensuring fitness of it we are trying to answer
- Data understanding uses various analytic approach such as descriptive statistics, predicitive statistics or both
- Data understanding should make complete definition of the requirements

## References
- Data Preparation Time
https://typeset.io/papers/automating-data-preparation-can-we-should-we-must-we-5fs72p1cqd
https://typeset.io/papers/a-realistic-data-cleansing-and-preparation-project-1ucwmv5sl6
https://typeset.io/papers/an-efficient-approach-for-filling-incomplete-data-25wjcvyk2z
https://typeset.io/questions/how-long-does-data-preparation-take-in-a-data-science-hex597w1e6
https://www.techtarget.com/searchbusinessanalytics/definition/data-preparation

- Correlation
https://www.youtube.com/watch?v=dsyTQNUvqH0

