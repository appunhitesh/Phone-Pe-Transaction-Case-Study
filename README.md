# Phone-Pe-Transaction-Case-Study
Analyzed PhonePe Pulse digital payments data (Q1 2018 – Q2 2021) across 36 Indian states/UTs and ~730 districts using Python (pandas, matplotlib). Merged state, district, transaction-type and device-brand datasets to study growth in transactions, user adoption and payment behavior, and visualized the trends with bar, pie and line charts.

# Dataset

The data is organized into six sheets:

# Sheet	Contents
State_Txn and Users	Quarterly transaction count, amount (INR), average transaction value (ATV), registered users and app opens for each state
State_TxnSplit	Transactions split by category: recharge and bill payments, peer-to-peer, merchant payments, financial services, others
State_DeviceData	Registered users by phone brand (about 20 brands) with percentage share, by state and quarter
District_Txn and Users	The same transaction and user metrics at district level, with district codes
District Demographics	Population, area, density and headquarters for each district
Admin	Lookup and reference sheet that standardizes state names and codes
Objectives
Track growth in transaction volume and value. The platform's quarterly volume rose from roughly 134 million transactions (₹17,183 crore) in Q1 2018 to about 3.94 billion (₹7.48 lakh crore) in Q2 2021.
Compare states and districts to find high-adoption regions and under-penetrated ones.
Break down transaction categories to see how usage shifted, for example from P2P transfers toward merchant payments.
Study user engagement through registered users, app opens and ATV trends.
Link digital adoption to demographics by combining transaction data with district population and density to estimate per-capita penetration.
Analyze device and brand distribution among users, which could inform app optimization and marketing.
# Methodology
Data cleaning: standardize state and district names using the Admin and Demographics lookups, and handle missing or zero values (app opens, for instance, are 0 before 2019).
Data integration: join the state, district and demographic sheets on state, district and code keys.
Exploratory analysis: run time-series trends, state and district rankings, and category mix analysis.
Visualization: build a dashboard with charts, maps and filters by year, quarter and state, in Power BI, Tableau, Excel or Python (pandas, matplotlib, plotly).
# Insights: summarize the drivers of growth, regional gaps and recommendations.
Key Insights to Explore
The top states by value, such as Telangana, Maharashtra and Andhra Pradesh in Q2 2021.
Whether the post-2020 surge, the COVID period, changed the transaction mix.
Districts with high population but low transactions per capita, which are growth opportunities.
Whether a brand's market share correlates with transaction behavior.

# Tools & Technologies

Excel, SQL, Python (pandas, NumPy, matplotlib, seaborn).

Business Value

The analysis can help fintech, banking and policy stakeholders target regions for expansion, design products for underserved segments, and understand how UPI adoption grew in India.
