PROJECT TITLE
- Website Traffic and Conversion Analysis

PROJECT OVERVIEW
- This project is an Exploratory Data Analysis (EDA) of website traffic data to understand user behavior and conversion drivers. The dataset contains 2,000 records of user sessions, including metrics like page views, session duration, bounce rate, and traffic source. The goal is to identify which traffic sources yield the highest engagement and conversion rates, helping to optimize digital marketing strategies.

DATASET DESCRIPTION
The dataset ("website_wata.csv") contains 2,000 rows with the following key columns:
1. Traffic Source: The origin of the user (e.g., Organic, Social, Paid).
2. Page Views: Number of pages viewed during a session.
3. Session Duration: Total time spent on the site per session.
4. Bounce Rate: The percentage of visitors who leave after viewing only one page.
5. Time on Page: Average time spent on a specific page.
6. Previous Visits: Number of times the user has visited before.
7. Conversion Rate: The likelihood of a user completing a desired action (0 to 1 scale).

OBJECTIVES OF THE PROJECT
- To analyze the distribution of traffic sources (Organic, Social, Paid, etc.).
- To determine which traffic source drives the highest conversion rates.
- To investigate relationships between engagement metrics (Page Views, Time on Page) and Conversion Rate.
- To identify patterns in user retention (Previous Visits) and their impact on conversions.
- To detect outliers and understand the spread of key metrics like Bounce Rate.

STEPS PERFORMED
1. Data Loading: Loaded the dataset using Pandas and checked the shape and data types.
2. Data Cleaning:
   - Removed whitespace from column names.
   - Verified there were no missing values (dataset was clean).
   - Converted columns to numeric types where necessary to ensure accuracy.
3. Exploratory Data Analysis (EDA):
   - Generated descriptive statistics (mean, min, max) for all numerical columns.
   - Analyzed the distribution of key metrics using histograms.
4. Data Visualization:
   - Created count plots to show the popularity of different traffic sources.
   - Used bar charts to compare Page Views, Session Duration, and Conversion Rates across traffic sources.
   - Plotted scatter plots and heatmaps to visualize correlations between variables (e.g., Page Views vs. Session Duration).
   - Used boxplots to detect outliers in the data.
5. Insight Generation: Identified the "Best Traffic Source" based on the highest mean conversion rate.

TOOLS AND LIBRARIES USED
- Python
- Pandas (for data manipulation)
- NumPy (for numerical operations)
- Matplotlib (for static plotting)
- Seaborn (for advanced statistical visualizations)
- Jupyter Notebook

FILES INCLUDED
- Website.ipynb: The Jupyter Notebook containing the code and visualizations.
- website_wata.csv: The dataset used for the analysis.

HOW TO RUN THE PROJECT
1. Install the required libraries:
   pip install pandas numpy matplotlib seaborn
2. Download "Website.ipynb" and "website_wata.csv" to the same directory.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run the cells sequentially to reproduce the analysis and view the charts.

KEY INSIGHTS
- Traffic Source Impact: Different traffic sources show varying levels of engagement. The analysis identifies which source leads to the highest conversion rate.
- Engagement vs. Conversion: There is a correlation between the time spent on the page/session duration and the likelihood of conversion.
- Bounce Rate Analysis: The project analyzes how bounce rates vary by traffic source, indicating the quality of traffic from each channel.
- User Behavior: Descriptive statistics reveal the average user behavior, such as typical session lengths and page views per visit.

CONCLUSION
- This analysis provides a clear view of website performance metrics. By identifying the top-performing traffic sources and understanding user engagement patterns, businesses can allocate marketing budgets more effectively to maximize conversions. The project demonstrates proficiency in data cleaning, visualization, and statistical analysis using Python.

AUTHOR
- Rishan Menezes
