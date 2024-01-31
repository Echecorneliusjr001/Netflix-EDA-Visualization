# Netflix-EDA & Visualization
An analysis of Netflix shows based on viewer's  and country's perspectives.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

- ### Project Overview
  ---

The "Netflix Shows Analysis (2011-2017)" project is a comprehensive exploration of Netflix's content during a pivotal period. With the advent of streaming services, Netflix began reshaping the entertainment industry. This project delves into the shows that were part of this transformation from 2011 to 2017.
This data analysis project aims to explore and gain insights into Netflix shows released between 2011 and 2017. Using Python libraries like Pandas, Matplotlib, and Seaborn in a Jupyter Notebook, we will examine various factors, including the distribution of content over the years, show types, country-wise content, top genres, and show ratings. The findings will provide a comprehensive view of Netflix's content during this critical period.


  ### Data Sources
  Data Sources:
The primary data source is a dataset containing information about Netflix shows from 2011 to 2017. The dataset includes details such as titles, release years, show types, countries of production, ratings, genres, and more.

  

  ### Tools
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn


  ### Data loading, cleaning & Preparation
  
Load the dataset into the Jupyter Notebook using Pandas.
Perform data cleaning and preprocessing, which may involve handling missing values, standardizing formats, and removing duplicates.

  ### Data Analysis
  
  Include some interesting code/features worked with
  
  ---
       
    
#value_counts method shows the count of different categories in a given country

df5.type.value_counts()

output result:

Movie      3678

TV Show      96

  ---
  
  ### Exploratory Data Analysis (EDA)

  Here's an exploratory data analysis with some questions to answer, the analysis includes the following key aspects:

- Identify the year with the highest count of shows.
- Categorize shows by type (e.g., movie, TV show) and analyze the count of each type.
- Determine which type is the most prevalent on Netflix.
- Explore the production countries of Netflix shows.
- Identify the country with the highest contribution to Netflix's content.
- Identify the top 10 countries with the most TV shows and movies on Netflix.
- Determine which country leads in each category.
- Analyze the distribution of show ratings.
- Identify the rating category with the highest count.
- Determine the top five genres of Netflix shows.
- Identify the genre with the highest count.


  

  ### Results/Findings
  
  Here are the findings for the questions;
  **1. 2017 was the year with the highest count of shows.**
  
  ![Highest count of shows](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/fa643e36-29fa-422f-81ae-6aaef890c1bb)

 **2. More movies were shown on Netflix than on TV shows.**
 
  ![Movies VS TV shows](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/909ea3d5-2ec8-4c40-901b-50e16a654c31)

  **3. Movies are the most prevalent on Netflix.**
  
  **4. The United States of America has the highest contribution to Netflix content.**
  
  **5. The United States of America leads in all categories.**
  ![Top 10 countries](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/44acf179-ba7e-4e09-b145-2c17e9609bb0)

  **6. TV-MA has the highest rating category with the highest count.**
  ![Ratings](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/d7bcc424-8f26-485c-8b2a-8b3f1f08390d)

  **7. Documentaries are the genre with the highest count.**
  ![Top 5 genre](https://github.com/Echecorneliusjr001/Netflix-EDA-Visualization/assets/149030759/e82f2c47-041b-4d95-8b7a-9853b4815fc5)

    
    
### Recommendations
  

Based on the insights gathered from the analysis of Netflix content between 2011 and 2017, the following recommendations can be made:

- Diversify TV Shows: While movies are prevalent on Netflix, there is an opportunity to diversify and expand the library of TV shows. Consider investing in original and engaging TV series to attract a wider audience, especially viewers who prefer episodic content.

- Global Partnerships: Given the significant contribution of the United States to Netflix content, continue collaborating with U.S.-based production companies and creators. Additionally, explore partnerships and content acquisition from other countries to further diversify the platform.

- Content Ratings: Recognizing that TV-MA is the highest-rated category with the highest count, focus on producing content that caters to mature audiences while ensuring content in other rating categories is also available to meet various age group preferences.

- Documentaries: Given the popularity of documentaries, consider producing more high-quality documentary content that covers a wide range of topics. This genre has a broad appeal and can attract a diverse audience.



### Contributions
In line with the insights gained, Netflix could collaborate with content creators, production companies, and filmmakers to achieve the following:

- Content Diversity: Collaborate with global filmmakers and production companies to create diverse content, including TV shows, to cater to a wider international audience.

- Original Series: Collaborate with creative talents to produce unique and engaging TV series that can capture the attention of viewers who prefer serialized storytelling.

- Quality Documentaries: Partner with documentary filmmakers and researchers to develop high-quality documentaries on a variety of topics, ensuring that this popular genre continues to thrive on the platform.

- Viewer-Driven Content: Collaborate with content creators to produce shows and movies that align with viewer preferences and demographic data to maintain and expand Netflix's global reach.

By following these recommendations and engaging in strategic collaborations, Netflix can continue to provide an extensive and diverse content library that meets the evolving demands and interests of its subscribers. 📺🤝 #Netflix #ContentStrategy #Contributions

### Limitations
Using Seaborn to obtain the visualization was a lot, so I decided to run a few of the visualizations with Matplotlib libraries for me to get the visualizations 
ready to go with the kind of data I had in my dataset.


### References
 Seaborn cheatography by Sanjeev95
 
 Netflix dataset (Website)
