# Recommendation_Engine_Project
This is a project uses IBM Watson Studio dataset to create recommendation algorithm for users. There are four parts in this project

### I. Exploratory Data Analysis

* Provide some insight into the descriptive statistics of the data

### II. Rank Based Recommendations

* The popularity of an article can be based on how often an article was interacted with.

### III. User-User Based Collaborative Filtering Function create_user_item_matrix: reformat the df dataframe to be shaped with users as the rows and articles as the columns.

* Each user should only appear in each row once.
* Each article should only show up in one column.
* If a user has interacted with an article, then place a 1 where the user-row meets for that article-column. It does not matter how many times a user has interacted with the article, all entries where a user has interacted with an article should be a 1.
* If a user has not interacted with an item, then place a zero where the user-row meets for that article-column

### V. Use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform

### VI. Conclusion

