# Global YouTube Statistics (Cleaning + EDA + Visualization)

### Overview
This project analyzes global YouTube statistics by cleaning, exploring, and visualizing data related to YouTube channels. It includes data preprocessing, univariate, bivariate, and multivariate analysis, and insights into the correlation between subscribers, views, uploads, and earnings.

### Objectives
- Clean the dataset by handling missing values and irrelevant columns
- Explore data distribution and trends through visualizations
- Identify relationships and correlations between key metrics
- Provide insights into YouTube channel growth and monetization

## **Data Cleaning**
- Removed unnecessary columns such as demographic information
- Filled missing categorical values with 'N.A.'
- Filled missing numerical values with the mode
- Converted date columns to proper datetime format

## **Exploratory Data Analysis (EDA)**

### Univariate Analysis
- Category Distribution: Entertainment, Music, and People & Blogs dominate YouTube content.
- Top Countries by Activity: The United States and India lead in YouTube activity.
- Top Continents by Activity: North America and Asia have the highest number of active channels.
- Distribution of Subscribers, Video Views, Uploads, and Earnings: All distributions are right-skewed, indicating that most YouTubers have low values, while a few have extremely high numbers.

### Bivariate Analysis
- Subscribers vs. Uploads: No strong relationship was found.
- Uploads vs. Earnings: No strong relationship was observed.
- Subscribers vs. Earnings: No clear correlation.
- Subscribers vs. Video Views: Strong positive correlation (~0.75), indicating that higher subscribers lead to more views.

### Multivariate Analysis
- Relationship between Subscribers and Earnings Across Continents:
- Asia shows the strongest correlation between subscribers and earnings.
- Other continents display weaker relationships.

## Key Insights
- YouTube activity is highest in the United States and India, which reflects in North America and Asia leading in overall activity.
- Most numerical distributions are right-skewed, meaning only a few top YouTubers dominate the platform.
- Subscribers and video views have a strong positive correlation, but earnings do not strongly correlate with subscribers or uploads.
- Asia has the strongest correlation between earnings and subscribers, suggesting higher monetization efficiency in that region.
