# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Retail Sales Data Analysis

## A. Aim

The aim of this project is to analyse historical Walmart retail sales data to identify sales patterns, understand differences in store and department performance, and provide practical business recommendations.

## Project Overview             

This project analyses historical Walmart retail sales data to identify sales patterns and provide useful business insights. The analysis focuses on sales performance across stores, departments, months, years, holidays and store types.

The project uses Python and data analytics techniques to clean, process, analyse and visualise the data. The findings are used to support recommendations relating to stock planning, resource allocation, seasonal demand and store performance.

## Project Objectives

The main objectives of this project are to:

- Analyse sales performance across stores and departments.
- Identify sales trends across months and years.
- Compare sales during holiday and non-holiday periods.
- Examine differences in sales performance between store types.
- Investigate unusual values, including negative `Weekly_Sales`.
- Explore the relationship between store size and `Weekly_Sales`.
- Use the findings to provide practical business recommendations.

## Project Purpose and Target Audience

The purpose of this project is to turn historical sales data into useful information that can support business planning and decision-making. The target audience includes retail managers, store managers and business analysts who need to understand sales performance and plan stock, staffing and resources.

## Dataset

The project uses a public Walmart retail sales dataset containing weekly sales information for different stores and departments.

The main datasets used are:

* **Sales data** – contains weekly sales, store, department, date and holiday information.
* **Features data** – contains additional information such as temperature, fuel price, markdowns, CPI and unemployment.
* **Stores data** – contains store type and store size information.

The datasets were combined using matching Store and Date information to create a dataset suitable for analysis.

## Tools and Technologies

The following tools and technologies were used in this project:

- **Python** – used for data cleaning, processing, analysis and visualisation.
- **Pandas** – used to load, clean, transform and analyse the datasets.
- **Matplotlib** – used to create charts and visualisations.
- **Seaborn** – used to create statistical visualisations.
- **Jupyter Notebook** – used to develop and document the analysis.
- **Tableau** – used to create an interactive sales dashboard.
- **Generative AI** – used to support understanding, troubleshoot code, explore analysis approaches and improve project documentation.

## Data Preparation and Methodology

The data was prepared in several stages before the analysis was carried out.

First, the sales, features and stores datasets were loaded into Pandas DataFrames. The data was checked for its structure, data types, missing values and duplicate records.

The Date column was converted to a datetime format so that sales could be analysed by month and year. Missing values in the Features dataset were also reviewed and appropriate methods were used to handle them. Markdown values were replaced with zero where no markdown was recorded, while missing CPI and Unemployment values were replaced using the median.

The datasets were then combined using Store and Date information where required. Negative Weekly_Sales values were investigated rather than automatically removed because they may represent returns, refunds or adjustments.

The Interquartile Range (IQR) method was also used to identify possible outliers in Weekly_Sales. These values were reviewed rather than automatically deleted because some unusual sales values may represent genuine business activity.

After cleaning and processing, the combined dataset was saved as a cleaned CSV file for further analysis and visualisation.

## Data Analysis

The cleaned dataset was analysed using Pandas to identify patterns and differences in Weekly_Sales.

The analysis compared total and average sales across stores, departments, months, years, holidays and store types. I also examined negative sales values and possible outliers to understand unusual records in the dataset.

Correlation was used to explore relationships between Weekly_Sales and selected variables such as Store Size, Fuel Price, CPI, Unemployment and markdown values. These results were interpreted carefully because correlation shows a relationship between variables but does not prove that one variable caused another.

Matplotlib and Seaborn were used to create charts that made the results easier to understand. The visualisations included bar charts, line charts, histograms, box plots and scatter plots.

The findings from the analysis were used to identify sales patterns and develop practical business recommendations relating to stock planning, seasonal demand, resources and store performance.

## C. Application of Data Analytics

I applied data analytics techniques to prepare, explore and interpret the Walmart retail sales data. I used Pandas to group sales by stores, departments, months, years and holiday periods, calculate totals and averages, and investigate unusual values.

I used descriptive statistics to understand the distribution of sales and the IQR method to identify potential outliers. I also used correlation analysis to explore relationships between Weekly_Sales and selected variables.

Matplotlib and Seaborn helped me present the results through charts, making sales patterns and differences easier to identify. These techniques supported my interpretation of the data and helped me develop business recommendations.

## D. Data Analytics and AI Opportunity

Data analytics can help retailers understand sales performance, recognise seasonal patterns and make better-informed decisions about stock, staffing and resources.

AI could further support retail analysis by helping forecast future sales, identify unusual sales patterns and estimate demand during busy periods. These opportunities could help retailers plan resources more effectively.

However, AI-generated predictions would need to be tested against reliable data and evaluated before being used to make business decisions. In this project, the analysis focused on historical sales patterns rather than implementing an AI forecasting model.

## E. Use of Generative AI

I used Generative AI tools, including ChatGPT, to support my understanding of data analytics concepts, troubleshoot Python code, explore possible analysis approaches and improve the clarity of my project documentation. I also used QuillBot to support paraphrasing and readability.

I reviewed the suggestions and used my understanding of the project to decide what was appropriate. The tools supported my learning and documentation, while I remained responsible for the analysis, interpretation of the results and final project content.

## F. Generative AI for Data Storytelling

Generative AI can support data storytelling by helping organise findings, explain analysis results in plain English and communicate insights clearly.

In this project, I used ChatGPT to help improve the explanations of my Walmart sales analysis and present findings more clearly. This helped me communicate the purpose of my analysis, explain the meaning of the results and develop recommendations based on the findings. I reviewed the suggested wording to ensure it remained consistent with my actual analysis and results. The data analysis, interpretation and final recommendations remained my responsibility.

## Key Findings

The analysis identified several important sales patterns:

* **Yearly sales:** 2011 recorded the highest total Weekly_Sales among the three years analysed.
* **Monthly sales:** December recorded particularly high average Weekly_Sales.
* **Store performance:** Store 20 recorded the highest average Weekly_Sales, while Store 5 recorded the lowest among the stores analysed.
* **Department performance:** Department 92 recorded the highest total Weekly_Sales, followed by Departments 95 and 38.
* **Holiday sales:** Average Weekly_Sales were higher during holiday weeks than during non-holiday weeks.
* **Store type:** Type A stores recorded the highest average Weekly_Sales, while Type C stores recorded the lowest.
* **Store size:** Store Size had a weak positive correlation of approximately 0.24 with Weekly_Sales.
* **Negative sales:** 1,285 records contained negative Weekly_Sales values and were investigated rather than automatically removed.

These findings were used to support the business recommendations in the project.

## Business Recommendations

Based on the findings, the following recommendations were developed:

1. **Improve performance across lower-performing store types** by reviewing their operations, product mix, promotions and customer demand, and comparing them with higher-performing stores.

2. **Strengthen holiday sales planning** by using previous holiday sales patterns to plan stock and staffing levels before major holiday periods.

3. **Prepare for seasonal demand** by reviewing historical monthly sales and increasing stock and staffing preparation before periods of expected higher demand.

4. **Investigate negative Weekly_Sales records** to determine whether they relate to returns, refunds, adjustments or data-quality issues.

5. **Monitor store and department performance** through regular sales reports and investigate significant changes in performance.

6. **Use sales data to support future planning** by regularly updating reports and using sales patterns to support decisions about stock, staffing and resources.

## Visualisations and Dashboards

Visualisations were created using Python, Matplotlib and Seaborn to make the analysis easier to understand. The charts were used to compare sales performance, identify trends and explore relationships between different variables.

The project also includes interactive dashboards created using **Power BI** and **Tableau**. These dashboards provide a visual summary of the sales data and allow users to explore key sales patterns and performance.

The visualisations and dashboards support the findings presented in the project and help communicate the results clearly to readers with different levels of data analytics knowledge. 

## Tableau Dashboard
I created an interactive dashboard in Tableau to present the key findings from my Walmart retail sales analysis. The dashboard allows users to explore sales performance across stores and departments and understand sales patterns over time.
View the Tableau dashboard  https://public.tableau.com/app/profile/yetunde.okunlade/viz/WalmartRetailSalesDashboard_17894884888020/Dashboard1

## Project Structure

The project is organised into separate folders for the main project files:

* **Data/** – contains the original datasets and the cleaned dataset used for analysis.
* **jupyter_notebooks/** – contains the Jupyter Notebook used for data preparation, analysis and visualisation.
* **README.md** – provides an overview of the project, methodology, findings and recommendations.

The original datasets are kept separate from the cleaned dataset so that the original data remains unchanged. This makes the analysis easier to reproduce and helps keep the project organised.

## Limitations

There are several limitations to consider when interpreting the findings:

* The dataset covers a specific historical period, so the findings may not fully represent current or future sales patterns.
* The dataset contains 1,285 records with negative Weekly_Sales. These may represent returns, refunds, adjustments or data-quality issues, but their exact causes could not be confirmed.
* The relationship between Store Size and Weekly_Sales was weak, with a correlation of approximately 0.24. This means Store Size alone does not strongly explain differences in sales.
* The dataset does not contain detailed customer-level information, which limits the analysis of individual customer behaviour and preferences.
* External factors such as local competition, marketing campaigns and changes in consumer behaviour may also have affected sales but were not fully examined.
* Correlation results show relationships between variables but do not prove that one variable caused another.

These limitations should be considered when using the findings to support business decisions.

## Effectiveness of Techniques

Pandas was effective for loading, cleaning, grouping and analysing the Walmart sales data. It helped me compare sales across stores, departments, months, years and holiday periods. The dataset provided historical sales information for these comparisons, although it did not include every factor that could influence sales.

Data cleaning helped me identify data quality issues, including negative weekly sales values and potential outliers. Examining these issues before analysis helped me understand the data more clearly. However, negative sales values and potential outliers are not necessarily errors and need to be interpreted carefully.

Organising the data into DataFrames made it easier to process, group and analyse the information. Keeping the project files organised also supported access to the data and reuse during the analysis.

Matplotlib and Seaborn helped me explore the results using bar charts, line charts, histograms, box plots and scatter plots. These visualisations made sales patterns, differences and unusual values easier to identify. The IQR method helped identify potential outliers, while correlation analysis helped me explore relationships between sales and selected variables. However, correlation does not prove causation.

Tableau provided an interactive way to present key findings and explore differences in sales across stores, store types and time periods. Overall, combining data preparation, statistical analysis and visualisation was useful for identifying sales patterns and developing practical recommendations. The findings remain limited by the historical period covered by the dataset and factors not included in the available data.

## Conclusion

This project analysed historical Walmart retail sales data to identify patterns in Weekly_Sales across stores, departments, months, years, holiday periods and store types.

The analysis showed differences in sales performance between stores and departments, as well as changes in sales across different months and holiday periods. Type A stores recorded the highest average Weekly_Sales, while Store Size had only a weak positive correlation with Weekly_Sales.

The analysis also identified 1,285 records with negative Weekly_Sales, which should be investigated further to understand their causes.

Overall, the project demonstrates how data preparation, analysis and visualisation can be used to identify useful sales patterns and support business decisions relating to stock planning, seasonal demand, resource allocation and store performance.

## References

1. **Kaggle – Retail Data Analytics dataset.** Used as the primary dataset for this project. Available at: [https://www.kaggle.com/datasets/manjeetsingh/retaildataset](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)

2. **Kaggle – Walmart Recruiting: Store Sales Forecasting.** Original Walmart sales forecasting competition and dataset source. Available at: [https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting)

3. **Code Institute – Data Analytics with AI course materials.** Course materials, exercises and Capstone Project guidance used throughout the project. Available at: [Code Institute LMS](https://lms.codeinstitute.net/)

4. **Code Institute.** Programme information and learning resources. Available at: [https://codeinstitute.net/](https://codeinstitute.net/)

5. **pandas documentation.** Reference materials used to support data loading, cleaning, processing and analysis. Available at: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)

6. **Matplotlib documentation.** Reference materials used to support the creation of charts and data visualisations. Available at: [https://matplotlib.org/stable/](https://matplotlib.org/stable/)

7. **Seaborn documentation.** Reference materials used to support statistical data visualisation. Available at: [https://seaborn.pydata.org/](https://seaborn.pydata.org/)

8. **OpenAI ChatGPT.** Used to support understanding of data analytics concepts, troubleshooting Python code, exploring analysis approaches and improving project documentation. Available at: [https://chatgpt.com/](https://chatgpt.com/)

9. **QuillBot.** Used to support paraphrasing and improve the clarity and readability of written content. Available at: [https://quillbot.com/](https://quillbot.com/)

10. **Tableau – Retail Store Performance and Insights dashboard.** Interactive dashboard created to present and explore key findings from the Walmart retail sales analysis. Available at: [View the Tableau dashboard](https://public.tableau.com/app/profile/yetunde.okunlade/viz/WalmartRetailSalesDashboard_17894884888020/Dashboard1)

## Acknowledgements

I would like to sincerely acknowledge my Learning Facilitator, Emma Lamont, for her guidance, encouragement and support throughout my Data Analytics with AI learning journey. Her teaching, feedback and willingness to provide support have helped me develop my understanding of data analytics and build confidence in applying my skills.

I would also like to acknowledge my Code Institute trainers and tutors for their teaching, guidance and project support throughout the course.

A special thank you to my husband and children for their patience, encouragement and support throughout my learning journey. Their understanding and support, especially during the time spent studying, practising and completing this project, have meant a great deal to me.

Finally, I am grateful to everyone who has encouraged and supported me throughout this journey. Their support has helped me remain committed to developing my skills in data analytics.


