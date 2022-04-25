# MS Movie Studio Project 
by Brandon Menendez 


![microsoft_corporate.jpg](attachment:microsoft_corporate.jpg)


## Overview

For this project, I was tasked with addressing the following prompt: 

> Use exploratory data analysis to generate three actionable insights that the new head of “Microsoft Movie Studios” can use to decide what kinds of films to create.


## Business Understanding 
In order to make recommednations to the new head of MS Movie Studios, we first need to decide what success in this venture looks like. 

In the modern movie business, streaming is key. Over the last 5 years, we have seen most of the major movie studios distirubte their movies via streaming platforms including Universal, Paramount, 20th Century Fox and more. When it comes to being successful in streaming, movie studios need a copious amount of recognizable content in order to attract and retain viewership. Since Microsoft is an established public company, we will assume that making profit for shareholders is important. 

Using this background, we are going to establish two main business objectives when crafting recommendations for the studio head:

    1. Invest in projects that have low investment costs and high rates of return 

    2. Generate a lot of content quickly to grow streaming viewership



## Data Understanding and Analysis 

### Data Sources 

For this project, I utilized the following sources of data: 

    1. IMDB Data Base
         - From this database, I was able to extract a dataset containing 73.9K movies that came about between 2010 and 2020.
         - This data contains movie attributes like Title, Release Year, Genres, and Avg. Rating on IMDB
         - This is the main source of data being used to determine the popularity of movies and genres in this analysis
         
    2. The Numbers 
        - This dataset initially contained financial data for a sample of 5.8K movies between 1915 and 2020. 
        - In order to make sure economics are relevant to today, I filtered to movies that came out past 2000
        - The remaining dataset contained 2.8K movies.
 
 ### Data Analysis 
 
 #### Looking into low investment, high margin genres:
 
1. As mentioned above, the final dataset for assessing the financials of popular movies totaled 2.8K rows. In order to guage what is "low" investment costs and "high" margin, I first needed to assess the central tendency of the data. For investment costs, I found the mean investment cost to be $28M dollars per movie. For margin, we are targeting being close to or above the average margin% at 137%




From here, we can see that genres which most closely fit this criteria includes: Horror, Thriller, Family, Biography, Documentary, comedy and Drama. 



#### Looking into the financials of movies shown internationally.

1. An initial look at the data from The Number dataset, shows pretty clearly that movies tend to make good money internationally. In order to determine what the actual benefit of hitting the international market, I did an analysis of movie margins between 2010 and 2020, to understand what percentage of return comes from the international market. As you can see from the area chart below, is often 25% or less of total movie profits in a given year. 




However, in order to be successful overseas we need to ensure we know what movies the market demands. Analyzing a subset of the IMDB data, I found 10.2K movies which were shown both domestically and internationally since 2010. As you can see below, out of the most popular movie genres from this dataset, 4 out of the 5 contain eithe Action or Adventure. This seems to be a critical genre to produce in order to be succssful abroad. 




#### Looking into the financials of movie studios. 
A great way to generate content quickly, is by acquiring an existing studio and absorbing their existing catalog of movies. In order to make this recommendaiton, I took a look at the financials of movie studios included in the IMDB dataset. Similar to the genre criterias listed above, we want to find a studio that has below average investment costs movie ($28M) and above average returns per movie (137%). I analyzed the financials of 99 different studios listed in the dataset. 

While there are many good candidates, I ultimately found Screen Gems to be the most intriguing. They have average returns per movie of $28.9M (slightly above average) and average returns per movie of 247% (well above average). In addition to having the right financials, they also have great success internationally with more than 50% of margins coming from the international market per movie. They also have a catalog of well rated and recognizable movies for customers. 



## Summary of Recommendations

1. When chosing projects to invest in in-house, focus on producing movies in genres that typically require a lower than average investment cost per movie, while offering above average returns where possible. Based on the analysis done and investment/margin criteria established, I've identifed the following target genres for the studio: 
    - Horror/Thriller
    - Family
    - Biograpgy/Documentary
    - Drama
    - Comedy 
    
2. Since the analysis indicates that international margins are often significantly higher than domestic, penetrating that market will be essential. Being able to create movies that appeal to the international market appears to be a great way to protect initial movie investments. However, due to Action and Adventure being the most popular genres for movies abroad and not wanting to invest that much money per movie, I recommend we partner with internaitonal studios in order to produce and/or distribute popular Action/Adv movies overseas at a lower cost.

3. In order to get a lot of content quickly, I recoommend that MS Movie Studios looks into acquiring an existing movie studio. Looking at the studio financials, SGem is a great target due to lower than average investment costs per move and higher than average returns. They are also succesful internationally, which will further help us in that grow international presence. They have a number of popular titles as well, which will be important for attracting new customers to the MS Movie Studios streaming service. 










