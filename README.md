# OTT Platform Content Strategy Analysis 

## Overview
This project aims to analyze the content strategy of a leading OTT platform, focusing on the types of shows and movies available, audience preferences, and potential market expansion opportunities. By leveraging data analysis techniques, the insights derived can inform strategic decisions regarding content production and acquisitions.

## Problem Statement
The objective of this analysis is to generate actionable insights that assist the OTT platform in making informed decisions about content production and business expansion across various markets. The analysis investigates patterns and preferences in the content library to enhance future acquisitions and productions.

## Dataset Overview
The dataset provides a comprehensive listing of movies and TV shows available on the OTT platform, including attributes such as:
- **Show ID**: Unique identifier for each movie or TV show.
- **Type**: Differentiates between movies and TV shows.
- **Title**: Name of the content.
- **Director**: Director(s) of the content.
- **Cast**: Actors involved.
- **Country**: Production country.
- **Date Added**: Date the content was added to the platform.
- **Release Year**: Year of release.
- **Rating**: TV rating.
- **Duration**: Length in minutes (for movies) or seasons (for TV shows).
- **Listed In**: Genre(s).
- **Description**: Summary of the content.

## Analysis Objectives
The analysis is directed towards answering critical questions that can guide the content strategy, including:
- What types of content are popular across different regions?
- Trends in the release of movies and TV shows over the years.
- Comparative analysis of TV shows versus movies.
- Optimal timing for releasing new content.
- Influence of cast and directors on content popularity.
- Content availability across geographical markets.

## Methodology
1. **Data Cleaning**: Preparing the dataset for analysis by handling missing values and standardizing formats.
2. **Exploratory Data Analysis (EDA)**: Visualizing trends, distributions, and relationships within the data.
3. **Statistical Analysis**: Applying relevant statistical methods to understand the impact of various factors on content performance.
4. **Visualization**: Utilizing data visualization tools to present findings effectively.

## Insights
- Analysis revealed trends in content consumption across different demographics, indicating preferences for specific genres in various regions.
- A significant increase in the number of original productions was noted, with a growing preference for TV shows over movies in recent years.
- The influence of popular actors and directors on content engagement metrics was quantified, highlighting key factors that drive viewer interest.

## Recommendations
Based on the analysis, the following recommendations are proposed:
1. The most popular Genres across the countries and in both TV Shows and Movies are Drama, Comedy and International TV Shows/Movies, so content aligning to that is recommended.
2. Add TV Shows in July/August and Movies in last week of the year/first month of the next year.
3. For USA audience 80-120 mins is the recommended length for movies and Kids TV Shows are also popular along with the genres in first point, hence recommended.
4. For UK audience, recommended length for movies is same as that of USA (80-120 mins)
5. The target audience in USA and India is recommended to be 14+ and above ratings while for UK, its recommended to be completely Mature/R content .
6. Add movies for Indian Audience, it has been declining since 2018.
7. Anime Genre for Japan and Romantic Genre in TV Shows for South Korean audiences is recommended.
8. While creating content, take into consideration the popular actors/directors for that country. Also take into account the director-actor combination which is highly recommended.

## Technologies Used
- **Python**: For data analysis and visualization.
- **Libraries**: pandas, NumPy, Matplotlib, Seaborn.

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
2. Open the Jupyter notebook (`OTT_Analysis_by_ankit.ipynb`) to explore the analysis and insights derived from the dataset.
3. Review the dataset file (`data.csv`) for a detailed view of the content features used in the analysis.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

