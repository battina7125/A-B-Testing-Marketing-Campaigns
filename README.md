📊 Project Overview: A/B Testing for Marketing Campaign Efficiency

📝 Background
As part of a marketing agency's strategic team, our primary goal is to maximize the return on investment (ROI) for our clients' advertising campaigns. This project seeks to identify the more effective advertising platform between Facebook and Google AdWords in terms of clicks, conversions, and overall cost-effectiveness. Understanding which platform offers better performance allows us to strategically allocate resources and optimize advertising strategies to enhance client outcomes.

🎯 Objective
To determine which advertising platform, Facebook or AdWords, results in higher conversions, better click-through rates, and greater cost-efficiency.

📊 Data Description

The analysis is based on data collected throughout the year 2019, encompassing daily performance metrics from both Facebook and Google AdWords campaigns. The dataset includes key features for each day:

📅 Date :Specific date from January 1st, 2019 to December 31st, 2019.

👀 Ad Views: Total number of ad impressions.

🖱 Ad Clicks : Total clicks on the ads.

🔄 Ad Conversions:Total conversions resulting from the ads.

💸 Cost perAd :Financial expenditure associated with each platform's ad for the day

🔗 Click-Through Rate (CTR) :  Proportion of ad views that result in clicks.

📈 Conversion Rate: Ratio of clicks that lead to conversions.

💵 Cost per Click (CPC): Average cost for each ad click.

In total, the dataset consists of 365 entries, each representing a day's performance metrics for the campaigns.

🔍 Methodology

Data Cleaning: Standardized data formatting and handled missing values to ensure data quality.

Exploratory Data Analysis: Visualized the distribution of clicks and conversions to understand data trends and patterns.

Statistical Analysis:

Conducted hypothesis testing using t-tests to compare performance metrics between the two platforms.

Performed correlation analysis to investigate the relationship between clicks and conversions.

Utilized cointegration tests to explore the long-term relationship between advertising spend and conversions.

Predictive Modeling:

Applied linear regression to predict conversions based on ad clicks.

Evaluated model performance using R² and Mean Squared Error (MSE).

📈 Key Findings

Platform Efficiency: Facebook showed significantly higher efficiency in converting clicks into actions, as indicated by both higher conversion rates and lower CPC.

Ad Spend Allocation: Data suggested reallocating budget to favor Facebook could enhance overall campaign effectiveness.

Temporal Insights: Conversion trends varied by time, suggesting specific months where ad spending could be optimized based on historical performance.

💻 Technologies Used

Python: Used for all data manipulation, analysis, and modeling tasks.

Pandas & NumPy: For data handling.

Matplotlib & Seaborn: For data visualization.

SciPy: For statistical tests.

Sklearn: For implementing and evaluating regression models.

