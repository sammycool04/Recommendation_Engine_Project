# Recommendation_Engine_Project
This is a project uses IBM Watson Studio dataset to create recommendation algorithm for users. There are four parts in this project

I. Exploratory Data Analysis

Find out the distribution of articles a user interacts within the dataset and provide a visual and descriptive statistics.

II. Rank Based Recommendations

Provide two functions to get n top articles names and n top articles ids.

III. User-User Based Collaborative Filtering Function create_user_item_matrix: reformat the df dataframe to be shaped with users as the rows and articles as the columns.

Each user should only appear in each row once.
Each article should only show up in one column.
If a user has interacted with an article, then place a 1 where the user-row meets for that article-column. It does not matter how many times a user has interacted with the article, all entries where a user has interacted with an article should be a 1.
If a user has not interacted with an item, then place a zero where the user-row meets for that article-column
V. Matrix Factorization Build use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform
