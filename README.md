# Netflix--Dataset--Analysis--Python

# Project Overview
This project involves a comprehensive analysis of the Netflix dataset, aiming to uncover insights into the types of shows, movies, and their performance on the platform. The analysis is conducted using Python, with a focus on data visualization and exploration to better understand content trends, ratings, and geographic distribution

# Key Features
**Data Cleaning**: Handling missing data and preparing the dataset for analysis.
**Exploratory Data Analysis (EDA)**: Visualizing trends using seaborn and matplotlib to explore content types, ratings, and their distribution across countries.
**Content Categorization:** Grouping content based on genres, countries, and release periods.
**Performance Metrics:** Analyzing the duration, ratings, and types of content (Movies vs. TV Shows) that dominate the platform.
# Tools and Libraries Used
Python
**Pandas** for data manipulation

**Seaborn** for data visualization

**Numpy** for numerical operations

**Matplotlib** for creating graphs and plots

# Results
Visual representations of content trends based on country, genre, and release dates.

Insights into the duration of popular content categories.

A breakdown of Netflix's global content distribution.
# Conclusion
This analysis offers valuable insights into Netflix's content offerings and trends, which can be useful for media analysts and content strategists.

**1-Top Directors by Number of Productions**

- **Insight** : Raúl Campos and Jan Suter are the top directors for Netflix, each contributing 18 productions, indicating their prolific involvement.

- **Source**: This was determined by counting the occurrences of director names in the dataset. 
 - **Number** : Raúl Campos and Jan Suter each directed 18 productions for Netflix.
    
**2-Year with the Highest Number of Releases** : 
- **Insight** : 2019 had the highest number of releases on Netflix, totaling 2136 movies and TV 
shows, showcasing a peak in content production.
- **Source** : This was found by counting the number of releases each year from the 'Date_N' 
column.
- **Number** : 2019 had 2136 releases, the highest in the dataset.
  
**3-Most Popular Genre by Count** : 
- **Insight** : 'International Movies' is the most prevalent genre on Netflix, with 2437 titles, 
highlighting its broad appeal.
- **Source** : This was identified by counting occurrences of each genre in the dataset.
- **Number** : There are 2437 'International Movies' on Netflix, making it the most common 
genre.

**4-Countries Producing the Most TV Shows** :
- **Insight** : The United States leads in TV show production for Netflix, with 705 shows, 
emphasizing its dominant role in content creation.
- **Source** : This was determined by filtering the dataset for TV shows and counting occurrences 
by country. 
- **Number** : The United States has produced 705 TV shows for Netflix.
  
**5-Distribution of Content Ratings**: 
- **Insight** : TV-MA is the most frequent content rating, applied to 2863 titles, indicating a 
preference for mature content.
- **Source** : This insight was derived from counting occurrences of each rating category.
-  **Number** : There are 2863 titles rated TV-MA on Netflix.
  
**6-Movies Released in 2020** :
- **Insight** : Netflix released 1312 movies in the year 2020, reflecting ongoing content 
production despite external challenges.
- **Source** : This was determined by filtering the dataset for movies released in 2020.
-  **Number** : 1312 movies were released on Netflix in the year 2020.
   
**7-TV Shows Released in India** :
- **Insight** : Netflix has released 71 TV shows specifically targeted at the Indian market, showing 
strategic localization efforts.
- **Source** : This was identified by filtering the dataset for TV shows released in India.
- **Number** : There are 71 TV shows released by Netflix in India.
 
**8-Longest Movie Duration** :
  - **Insight** : The longest movie on Netflix has a duration of 312 minutes, catering to viewers 
preferring longer-format content. 
- **Source** : This insight was found by identifying the maximum value in the 'Minutes' column.
-  **Number** : The longest movie on Netflix is 312 minutes.
  
**9-TV Shows with 'R' Rating after 2018** :
- **Insight** : There is only 1 TV show on Netflix with an 'R' rating released after 2018, indicating 
limited availability of mature TV content.
- **Source** : This was identified by filtering the dataset for TV shows with an 'R' rating after 2018.
- **Number** : There is 1 TV show on Netflix with an 'R' rating released after 2018.
