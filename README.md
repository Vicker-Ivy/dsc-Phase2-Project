#  Film Industry Market Analysis for Business Diversification

## Introduction

In this section, I will use exploratory data analysis (EDA), the goal is to provide key  insights for a business stakeholder considering entry into the film industry. With the rise of major companies producing original video content, our company plans to launch a new movie studio but lacks industry knowledge. 
By identifying which types of films perform best, I will provide data-driven recommendations to guide leadership to make informed decisions on the genres, formats and strategies most likely to drive success in this new venture.

For a Tableau presentation, refer to this link [Tableau](https://public.tableau.com/views/Phase2_wb/Phase2-Project-Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

For a PDF presentation, refer to this link [pdf](https://powerpoint.cloud.microsoft/open/onedrive/?docId=D7717641FDD01CA8%21s702ab266a6fe4bc0886b5152e17fcffc&driveId=D7717641FDD01CA8)

## Business Understanding

The company's goal is to establish which  films are currently doing the best at the box office.Through data analysis I will  translate those findings into actionable insights that the head of your company's new movie studio can use to help decide what type of films to create.

I will do this by answering vital business questions, such as:
- How much production budget is required for certain films?
- Which investments are highly efficient?
- What are the trends in budgets vs worldwide gross over decades?
- Which genres have the highest profit ?

## Data understanding

Data has been sourced from multiple datasets. These sources are most relevant since they provide indepth information regarding films and the process that is involved in creating them. The datasets we are working with include:

- Box Office Mojo
- IMDB
- Rotten Tomatoes Movies
- Rotten Tomatoes Critic Reviews
- TheMovieDB
- The Numbers
- im.db (SQLite database)

The data provides information regarding genre, ratings, release time, revenue, and budget. Data limitations may include; missing data, 
time period bias and estimation inaccuracy.

Using the data above, I will conduct exploratory data analysis in Python. Data exploration helps us understand the structure, quality, and characteristics of the data we are working with. Popular Python libraries and modules like Pandas and SQL will be crucial in this analysis.

##  Exploratory Data Analysis

I will use two datasets namely;
1. bom.movies_gross.csv
2. tn.movies_budget_csv

## Data Visualization

Using simple and relevant visualization techniques, such as:
  * Bar Charts
  * Line Graph
  * Histograms

These will be able to help in the interpretation of data to come up with solid business recommendations, and answer 
business questions. 

## Recommendations

Using the business questions highlighted at the beginning of this notebook, I shall make the following recommendations:

1. *How much production budget is required for certain films?*
     * I would suggest the movie production budget range between 17 to 30 million US dollars. This is the most popular range of       values  within the music industry.

2. *Which investments are highly efficient?*
     *  It is clear that the film company should invest heavily in their domestic audience and cater to their entertainment needs while also considering their foreign audience. Most movies have high return on investments than profit, therefore it is important to invest in high ROI genres(e.g., Action).

3. *Which genres have the highest profit?*
     * In our visualization genres such as Action, Fantasy, Science Fiction, and Drama have received the highest profits so it would be best to focus on these genres.

4. *What are the trends in budgets vs worldwide gross over decades?*
     * Due to tough competition in the movie industry, a lot of high performing actors and technological devices used for filming movies have recently become more expensive. In order to receive the excpected revenue, the production budget used should be over 25 million US dollars.

## Conclusion
The movie industry is very risky. It requires high capital and consistency with the latest trends. Therefore I would urge that absolutely the best should be chosen for this task.
