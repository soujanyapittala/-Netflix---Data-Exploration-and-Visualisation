📊 Netflix Content Analysis & Business Insights

📌 Project Overview

This project focuses on analyzing Netflix’s content dataset to understand patterns in content distribution, growth trends, and audience targeting.

The objective is to move beyond basic exploration and derive insights that can support content strategy and business decisions.

🎯 Objectives

Analyze the distribution of Movies and TV Shows

Identify trends in content addition over time

Understand country-wise content production

Explore genre and rating patterns

Derive insights relevant to Netflix’s business strategy

📂 Dataset Description

The dataset contains ~8800 titles available on Netflix, including both Movies and TV Shows.

Key features include:

Content type (Movie / TV Show)

Title, Director, Cast

Country of production

Release year and date added

Rating and duration

Genre categories

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

🔧 Data Preprocessing

Converted categorical variables for efficient analysis

Extracted year_added and month_added from date

Identified and assessed missing values

Split and expanded multi-value columns such as:

cast

director

country

This step was important to ensure accurate aggregation and analysis.

🔍 Exploratory Data Analysis
1. Content Distribution
Movies form the majority of the dataset
TV Shows, although fewer, show increasing presence
2. Trend Analysis
Significant growth in content addition observed after 2015
Peak additions occur between 2017–2020
3. Country-wise Analysis

Top contributing countries:

United States
India
United Kingdom

This indicates a mix of global dominance and regional expansion.

4. Genre Analysis

Frequently occurring genres:

Drama
Comedy
International content

These genres dominate across both Movies and TV Shows.

5. Rating Analysis
Most content falls under TV-MA and TV-14
Indicates a strong focus on adult and young adult audiences
6. Duration Analysis
Most movies are between 80–120 minutes
Outliers exist but represent valid long-form or short content

📈 Key Insights

Netflix’s content strategy shows a shift toward TV Shows, likely to improve user retention
Content expansion accelerated post-2015, aligning with global market growth
Heavy reliance on US content, with increasing investment in regional markets like India
Focus on mature and emotionally engaging genres such as Drama and Comedy
Standardization in movie duration suggests consistency in content format

💡 Business Recommendations

Increase investment in TV Shows and limited series formats
Expand localized content production in high-growth regions
Continue focusing on high-performing genres
Leverage data to test new content formats before scaling
Strengthen collaborations with consistently performing creators
