# NewYork-Stock-Exchange-Analysis-Supervised-Unsupervised-Learning
This study explores the application of advanced analytics techniques to the New York Stock Exchange (NYSE) dataset, employing both descriptive and predictive methodologies. Descriptive analysis was conducted using Power BI dashboards to provide comprehensive insights into the historical performance and trends of stock market data. Predictive analytics utilized simple exponential smoothing to forecast future stock prices, enhancing decision-making capabilities. Additionally, unsupervised learning techniques such as clustering were employed to identify distinct groups within the dataset, revealing potential market segments or patterns.
# Research Questions About Descriptive Analysis
* How have stock prices of NYSE-listed companies changed over time? Are there any discernible trends or patterns in stock price movements?
* What are the historical trends in key fundamental metrics such as revenue, warnings, and profitability for companies listed on the NYSE?
* Is there a correlation between specific fundamental metrics (for example, earnings per share, debt-to- equity ratio) and stock price movements for NYSE-listed companies?
* Are There any seasonal patterns or anomalies in stock price movements or trading volumes for NYSE listed companies?
* Do certain sectors exhibit stronger seasonal trends compared to others?
# Research Questions About Predictive Analytics and Clustering
* Can we identify distinct groups or clusters of stocks based on their fundamental characteristics (e.g., growth vs. value stocks)?
* Using stock EPS data, can we cluster stocks based on their historical price movements to identify similar patterns or trends?
* Are there specific sectors or industries within the NYSE where companies exhibit similar fundamental characteristics or stock price behavior?
* Can we predict the best sector where investor can invest and will get better return for the next year?
# Statistical hypothesis test
* ANOVA Test : The ANOVA tests provide statistical evidence that the mean total revenue, gross profit & Net Income varies significantly across companies within each sector. The ANOVA results underscore the importance of recognizing and understanding the variability in revenue & profit performance within sectors. By acknowledging these differences and identifying their underlying drivers, businesses and investors can make more informed decisions to navigate the complexities of the market landscape and achieve sustainable growth and success.
* Chi2 Test : The Chi-squared test assesses the independence of categorical variables by comparing observed and expected frequencies, helping to determine if there's a significant association between them. In our statistical analysis, we have performed chi2 test on categorical variables sets ( GICS Sector and GICS Sub Industry), (Security and SEC filings). In a result we found that there are significant association between those categorical variables. So we keep either one for our analysis.  
# Database Merge Operation: Full Join of Fundamentals and Security Tables
I executed a full join operation to merge two tables, Fundamentals and Security, based on their shared primary key. This process combines all rows from both tables, retaining unmatched rows from either side where applicable. This unified dataset now incorporates comprehensive information from both Fundamentals and Security tables, facilitating comprehensive analysis.
# Libraries
* pandas
* Numpy
* scipy
* sklearn
* statsmodels
* seaborn
* matplotlib
* holt_Winters
# Techniques & Methods
* Exploratory Data Analysis (EDA) - Univarate Analysis, Multivariate Analysis.
* Outliers detection - IQR Method.
* Outliers prevention - Log Transformations
* Hypothesis testing - Chi 2 test, ANOVA Test.
* Data Exploration & distribution - Summary Statistics.
* Data normalization - Standard Scaler.
* To find an optimal number of cluster - Elbow method.
* To Find an Optimal value of Alpha - Hyperparameter Tuning GridSearchCV.
# Supervised Learning
* Predictive analytics - Simple Exponential Smoothing SES
# Unsupervised Learing 
* Clustering - KMeans Clustering
# Descriptive Analytics
* PowerBi Dashboards
* 




