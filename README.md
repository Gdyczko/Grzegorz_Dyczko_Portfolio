# Grzegorz Dyczko Portfolio

My example data analyst projects

## [Project 1: Netflix-Movies-and-TV-Shows](https://github.com/Gdyczko/Netflix_Movies_and_TV_Shows/tree/main)

Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

**The dataset was analyzed in terms of:**
1. **How many movies and TV shows have been published on the Netflix platform?**
2. **Movies and TV shows with the most published directors?**
3. **From which countries are the most movies published?**
4. **Which production years have the most movies on the Netflix platform?**
5. **In which age group are the most movies and TV shows published?**
6. **What is the most common duration of movies published on the Netflix platform?**
7. **How many seasons do TV shows most frequently have?**
8. **Which category has the most movies on Netflix?**
9. **Which category has the most TV shows on Netflix?**

![](Image/Movies_vs_TV_Shows.png)
![](https://github.com/Gdyczko/Netflix_Movies_and_TV_Shows/blob/main/Top%2010%20Countries.png)
![](https://github.com/Gdyczko/Netflix_Movies_and_TV_Shows/blob/main/Top%2010%20Listed%20Geners%20for%20TV%20Shows.png)

## [Project 2: Stroke Data Analysis](https://github.com/Gdyczko/Stroke-Data_Analysis)
* The acquired dataset underwent analysis to determine whether there are any factors influencing the increased risk of stroke.
* Additionally, the BMI index among study participants was analyzed to check if the place of residence or type of work has an impact on this indicator.

![](https://github.com/Gdyczko/Stroke-Data_Analysis/blob/main/Corelation%20between%20all%20data.png)

## [Project 3: Create Cinema Database](https://github.com/Gdyczko/Create_Cinema_Database)

Description of the database:

The database has been created for the purpose of analyzing and efficiently managing the business of a cinema. It collects information about movies and their genres, directors, sold tickets, types of halls, as well as employees and their leaves. This enables us to possess and analyze various pieces of information, such as which type of movie (genre) is most frequently watched, whether the duration of the film matters in the selection process, whether the director's surname matters, which employee sells the most tickets, in which hall the most movies have been screened, etc. In general, with the help of this database, we are able to determine the level of cinema functioning, as well as better understand the needs of customers and adjust the services provided accordingly to their needs.
```sql
CREATE TABLE Movies (
    Movie_Id INT PRIMARY KEY,
    Title VARCHAR(50) NOT NULL,
    Duration TIME,
    Release_Date DATE,
    Screening_Start_Date DATE,
    Screening_End_Date DATE
)
```
