# Google Play Store Analytics
## Overview
Comprehensive analysis of 10,841 Google Play Store apps exploring ratings, reviews, installs, categories, and pricing strategies. Delivered actionable insights for app developers and marketers to optimize app performance and user engagement.

## Dataset Overview
- **Size**: 10,841 unique apps spanning 34 categories with 13 features including app metadata, performance metrics, and user engagement data.
- **Key Metrics**: Average rating of 4.19, predominantly free apps (92.6%), most popular category is FAMILY (1,972 apps), followed by GAME and TOOLS.
- **Features**: App name, category, rating (1-5 scale), reviews count, size (MB), installs range, type (Free/Paid), price, content rating, genres, last updated date, current version, and minimum Android version.
- **Install Distribution**: Ranges from 0-100 downloads to 1 billion+ installs, with 1 million+ being the most common install bracket (1,579 apps).
- **Pricing**: 10,040 free apps, 801 paid apps with prices ranging from $0.99 to $400, most paid apps under $5.
- **Content Ratings**: Majority rated "Everyone" (8,714 apps), followed by Teen (1,146), Mature 17+ (447), and Everyone 10+ (376).
- **Data Quality**: Contains missing values in ratings (1,474 nulls), some size and version fields marked as "Varies with device" requiring cleanup.

## Analysis Performed

- **Average Rating Analysis**: Calculated the overall average rating of apps in the dataset to understand general user satisfaction
- **Category Distribution**: Identified and counted unique app categories to examine the diversity of applications on the Play Store
- **App Size Distribution**: Analyzed the distribution of app sizes to understand storage requirements across applications
- **Free vs Paid Apps**: Compared the count of free versus paid applications to assess monetization strategies
- **Content Rating Distribution**: Examined the most common content ratings to understand target audience demographics
- **Top Installed Apps**: Identified the top 5 most installed applications to determine popular apps on the platform
- **High-Rated Apps Analysis**: Counted apps with ratings of 4.0 and above to assess overall quality standards
- **Reviews by App Type**: Compared average number of reviews between free and paid apps to analyze user engagement patterns
- **Category-wise Size Analysis**: Calculated average app size for each category to identify resource-intensive app types
- **Update Frequency Patterns**: Analyzed app update timestamps to identify temporal trends and seasonal patterns in app maintenance
- **Correlation Analysis**: Examined relationships between installs and ratings, price and ratings, and app size and installs to identify key success factors
- **Genre Performance**: Evaluated genres with over 1 million installs and their average ratings to identify high-performing categories
- **Content Rating Distribution**: Analyzed how content ratings differ between free and paid apps across different user segments
- **Rating Trends by Installs**: Created binned analysis to understand how average ratings change with increasing install counts

- **Visualizations**:  
  - Created bar charts showing category-wise ratings, with EDUCATION (4.37) and ART_AND_DESIGN (4.37) leading, while DATING (4.01) and MAPS_AND_NAVIGATION (4.06) lag behind.
  - Built install range analysis revealing higher install brackets correlate with better ratings, peaking at 4.37 for 50M-1B install apps.
  - Visualized top reviewed apps including Facebook (78M reviews), WhatsApp (69M reviews), and Instagram (66M reviews), all with 1 billion+ installs.

## How to Use

- Typical libraries include pandas, numpy, seaborn, matplotlib for analysis and visualization.
- Open `google-play-store-analytics.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
- Run cells from top to bottom to load data, perform cleaning, generate visualizations, and extract insights.
- Original Kaggle notebook:  
[google-play-store-analytics](https://www.kaggle.com/code/kshitijsaini121/google-play-store-analysis)
- Customize the analysis:  
- Filter by specific categories or content ratings to focus on target markets.
- Add sentiment analysis on review text data if available to understand user satisfaction drivers.
- Compare app performance over time by analyzing update frequency versus rating trends.
- Create predictive models to estimate potential installs based on category, size, and pricing strategy.
- Use insights to inform app development decisions around category selection, pricing models, size optimization, and update schedules.

## Author & Contact
- Name: `Kshitij Saini`  
- LinkedIn: [https://www.linkedin.com/in/kshitijsaini](https://www.linkedin.com/in/kshitij-saini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)
