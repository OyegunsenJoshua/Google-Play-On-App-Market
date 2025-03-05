# Google-Play-On-App-Market
This Data Enhances Google Play store in offering various selection of Games, Apps, Music, Music to Users all around the World with Over a billion active Users. 

Table of Contents
1. # [Project Overview]
2. # [Key Areas of Analysis]
3. # [Landing Page]
4. # [Dashboard]
5. # [Tools]
6. # [Data Cleaning/Preparation]
7. # [Key Performance Indicator]
8. # [Insights]
9. # [Conclusion]

# Project Overview
This project utilize data analysis and visualization techniques to offer a deeper understanding of the dynamics within the Google Play Store, supporting developers in optimizing their applications for better performance and user engagement in the world.
  
# Key Areas of Analysis:
  Competitor Benchmarking
- Comparison with similar apps in the category
- Identifying gaps and opportunities
- Learning from high-performing app descriptions.

 Monetization & Business Model
- Clarity on pricing, subscriptions, or in-app purchases
- Highlighting value proposition for paid users

 App Title & Subtitle
- Keyword optimization for discoverability
- Clarity and relevance to app functionality.

 # Landing Page
This explains each column in the dataset as follows;

   - Apps: Contains different applications on the Android Market on Google Play WorldWide.
   - Category: Different Segments of how the apps were classified into which were: Apps and Design, Comics, Communication, Beauty, Auto and Vehicles and so forth.
   - Ratings: This is the percentage breakdown of how the apps were rated, such as between "4 and 5 stars".
   - Reviews: This provides valuable insights into user experience, app performance, and potential areas for improvement.
   - Size: Size is an important factor affecting downloads, user retention, and user performance, Such as: Games(100MB - 2GB), Finance and Banking Apps(20MB – 150MB).
   - Installs: Google Play groups installs into broad ranges:
   100+ (new apps)
   1K+ (small scale apps)
  10K+ (growing user base)
  100K+ (popular apps)
  1M+ (mainstream success)
 10M+ (highly successful apps)
 100M+ (Top tier apps)
 1B+ (Global leaders like WhatsApp, Facebook.)
  - Type: Either the apps are free to download or paid with a price ($).
  - Price: The amount at which several apps were Purchased.
  - Content Rating: Species of spectators utilizing such apps like; Adults Rated 18, Teen, Adult, Everyone, Unrated.
  - Last Updated: Frequent Updates and Improvements.
  - Android Version:The minimum Android version required for an app is essential for device compatibility, user reach, and performance, For instance; Version 4.5, Version 4.0.
  
# Dashboard
<img src= https://github.com/user-attachments/assets/3594ba90-d74d-42d2-9778-4bf111b76b92 width=”400” height=”250” alt=”Image”>


# Tools
The following tools helped in carrying out this survey successfully.

- Microsoft Excel - Data Cleaning
- Microsoft Excel/ SQL Server - Exploratory Data Analysis
- PowerBI Desktop - Creating Reports of the data Sets.

# Data Cleaning/Preparation
In the data Preparation Phase, the following tasks were perfromed:

- Removing Duplicates:There was no duplicates in the data set
- The "Category Column" was properly Rearranged
- There was blanks in the Rating column, Using the 'AVERAGEIF' Function was used to replace the blanks since the rating Column row cannot be left empty.(An app is surely rated)
- Used 'AVERAGEIF' to fill out zero values in price column, =AVERAGEIF(H:H, 0, "H:H")
- While exploring the data there was zero values in the installs column and it was filled with N/A(Not Available) since the Originator of the dat Set could not be Contacted.
- Size column missing values replaced with 'N/A'(Not available)
- In the review column the average was replaced with zero values using 'AVERAGEIF' to fill out zero values, =AVERAGEIF(D:D, 0, "D:D")
- Using IFISBLANK  statistical method with Excel Function to fill blank values in the Rating column; IF(ISBLANK(C2), (C2)).
  
- I used this data method to ensure consistency in my Data correction.
  


# Key Perfromance Indicators
✅ Total Sum of price – 137.78(K)Thousand US Dollars.
✅ Most Installs by Category – 'Medical Sector'
✅ App Store Ranking – Position with the highest rankings : 'Family'
✅ Average Rating of Apps – '4.17'

# Insights
   Key Insights and Analysis:
1. Average Rating Across All Apps:
   The average rating across all apps is approximately 4.17, indicating that most apps are rated positively by users, A rating above 4.0 is generally considered good, meaning that the majority of apps have favorable user experiences.
   
2. Distribution of Free and Paid Apps:89% of the apps are free (8,901 apps), while only 755 apps are paid. This suggests that the free apps is the dominant monetization strategy.
 - Paid apps are much less common, possibly due to competition from free alternatives.

3. Most Popular Categories:'Family' is the largest category with 1,831 apps, indicating a strong market for family-friendly applications.
- GAMES (959 apps) ranks second, showing the popularity of mobile gaming.
- TOOLS (827 apps) 
- BUSINESS (420 apps) 
- MEDICAL (395 apps) reflecting professional and healthcare-related app needs.

3. Top Installed Apps (Most Popular by Downloads)
The following apps have the highest number of installs (each exceeding 1 billion downloads):

- Google Play Books,
- Gmail.
  These are well-known apps by major tech companies like Google and Meta.
Messaging and communication apps (WhatsApp, Messenger) dominate, indicating high demand for social connectivity.
Essential productivity apps (Chrome).

4. Average Price of Paid Apps: The average price of paid apps is approximately '$14.06'. This suggests that while many apps are free, paid apps tend to have a relatively high price point.
Niche apps (e.g, medical, business, and professional tools) might drive up the average price.


# Conclusion
Most apps are free (89%), following the  description of the data model.
- The average app rating is 4.17, indicating generally positive user experiences.
- 'FAMILY' and GAME categories dominate, showing high demand for entertainment and educational apps.
- Google and Meta apps lead in installs (1billion Plus downloads each), particularly messaging and productivity apps.
-Paid apps have an average price of '$14.06', with business and specialized apps likely influencing their price.

