# Retail Sales Data Analysis

## Project Overview

This project analyses historical retail sales data to identify trends, patterns and differences in sales performance. The analysis uses Python and data analytics techniques to clean, explore and visualise the data and produce insights that can support business decision-making.

## Aim

The aim of this project is to analyse retail sales data and identify trends and patterns that can help a retail business understand sales performance and make better-informed decisions.

## Business Requirements

The analysis focuses on the following business requirements:

* Identify trends in weekly sales over time.
* Compare sales performance across different stores and departments.
* Investigate differences between holiday and non-holiday sales.
* Explore patterns and variations in retail sales performance.
* Use appropriate visualisations to communicate the findings clearly.
* Provide recommendations based on the results of the analysis.

## Dataset Content

The project uses the Retail Data Analytics dataset obtained from Kaggle.

The dataset consists of three main files:

* **Sales data-set.csv** – contains weekly sales information for stores and departments, including dates and holiday indicators.
* **Stores data-set.csv** – contains information about individual stores, including store type and store size.
* **Features data set.csv** – contains additional information such as holidays, markdown data, CPI and unemployment.

The sales dataset contains **421,570 records** and includes the following main variables:

* Store
* Dept
* Date
* Weekly_Sales
* IsHoliday

## Data Cleaning and Preparation

The datasets were inspected and prepared before carrying out the analysis.

The data preparation process included:

* Inspecting the structure and dimensions of the data.
* Checking column names and data types.
* Converting the Date column to datetime format.
* Checking for missing values.
* Investigating negative weekly sales values.
* Checking for duplicate records.
* Reviewing the data for potential inconsistencies.
* Preparing the data for analysis and visualisation.

The sales data contained **1,285 records with negative Weekly_Sales values**. These records were investigated as part of the data-quality assessment because negative values may represent returns or other adjustments rather than normal sales.

## Data Analysis

Exploratory data analysis was carried out using Python and Pandas.

The analysis included:

* Descriptive statistics.
* Grouping and aggregation.
* Analysis of sales over time.
* Comparison of store performance.
* Comparison of holiday and non-holiday sales.
* Investigation of negative sales records.
* Examination of patterns and differences in weekly sales.

The analysis was guided by the business requirements and user story developed for the project.

## Data Visualisation

Visualisations were created to communicate important patterns and findings from the dataset.

The project uses charts to help examine:

* Sales trends over time.
* Differences in sales performance between stores.
* Sales distributions and variations.
* Holiday and non-holiday sales performance.
* Other relationships identified during the analysis.

The visualisations were selected to make the results easier to understand and to support evidence-based business decisions.

## Key Findings

The analysis identified differences in weekly sales performance across stores and over time.

The investigation also showed that sales performance varies between holiday and non-holiday periods. Store-level analysis highlighted differences in average weekly sales, demonstrating that sales performance is not consistent across all stores.

The analysis of negative sales values also highlighted the importance of checking unusual records during the data-cleaning stage before drawing conclusions from the data.

## Recommendations

Based on the analysis, the following recommendations are suggested:

* Monitor weekly sales trends regularly to identify changes in performance.
* Compare individual store performance to identify stronger and weaker-performing locations.
* Consider holiday periods when planning stock, staffing and sales activities.
* Use historical sales patterns to support future planning and decision-making.
* Continue analysing promotional and economic factors to better understand changes in sales performance.

## Limitations

There are some limitations to the analysis.

The dataset represents historical retail sales, so the findings describe previous sales behaviour and cannot guarantee future performance.

Some variables in the Features dataset contain missing values, which limits the analysis that can be carried out using those variables.

Negative sales values also require careful interpretation because they may represent returns or adjustments rather than conventional sales.

Further analysis using additional business information could provide a more complete understanding of the factors affecting sales.

## Testing

The notebook was tested by running the cells in sequence and checking that the expected outputs were produced.

Data-quality checks were carried out during the cleaning process, including:

* Checking dataset dimensions.
* Checking data types.
* Checking missing values.
* Investigating negative sales values.
* Checking for duplicate records.
* Reviewing the outputs of calculations and visualisations.

The analysis and visualisations were reviewed to ensure that they addressed the project requirements.

## Unfixed Bugs

No known unfixed bugs remain in the completed project.

## Future Improvements

Possible future improvements include:

* Carrying out more detailed analysis of markdown and promotional activity.
* Investigating the effects of economic factors such as CPI and unemployment.
* Applying more advanced statistical techniques.
* Developing predictive models to forecast future sales.
* Creating an interactive dashboard to make the findings easier for business users to explore.

## AI Assistance

Generative AI was used as an assistance tool during the development of this project.

ChatGPT was used to support understanding of Python and data analytics concepts, troubleshoot coding issues, discuss analytical approaches and improve the clarity of project documentation.

AI assistance was used as a support tool rather than as a replacement for the analysis. The code, outputs and findings were reviewed and checked against the project data

QuillBot was also used to support paraphrasing and improve the clarity and readability of some written content.

## Technologies and Libraries

The project was developed using:

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib

## Conclusion

This project demonstrates how data analytics can be used to explore retail sales performance and identify useful trends and patterns.

The analysis provided insights into differences in sales performance across stores, changes in weekly sales and the relationship between sales and holiday periods. The findings can help support more informed retail planning and decision-making.

Further analysis, including predictive modelling and more detailed investigation of promotional and economic factors, could provide additional insight into future sales performance.

## References

* **Kaggle – Retail Data Analytics dataset**: The main dataset used for the project.https://www.kaggle.com/datasets/manjeetsingh/retaildatase
* **Code Institute**: Course learning materials and project guidance.https://codeinstitute.net
* Code Institute LMS — Learning materials, exercises and project guidance used throughout the course. https://lms.codeinstitute.net/site/not_logged_im
* **Code Institute Trainer/Facilitator** — Emma Lamont— Guidance, feedback and support provided throughout the project.



* **OpenAI ChatGPT**: Used as an AI assistance tool during the development of the project, for understanding concepts, troubleshooting Python code, reviewing analysis approaches and improving project documentation. https://chatgpt.com
* **QuillBot**: Used to support paraphrasing and improve the readability of written content. https://quillbot.com**
* Scribbor: support with proofreading/academic writing and referencing, if that's how you used it. https://www.scribbr.com
* 
