# Exploring-Hacker-News-Posts
In this project, we'll work with a data set of submissions to popular technology site Hacker News. Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

You can find the data set here, but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

* id: The unique identifier from Hacker News for the post
* title: The title of the post
* url: The URL that the posts links to, if it the post has a URL
* num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
* num_comments: The number of comments that were made on the post
* author: The username of the person who submitted the post
* created_at: The date and time at which the post was submitted

We'll compare these two types of posts to determine the following:
* Do Ask HN or Show HN receive more comments on average?
* Do posts created at a certain time receive more comments on average?

## Conclusion:
Some of the findings that we found out during analyzing the dataset were:

1. Between "Ask HN" and "Show HN" post, ask Hn received more comments per post.
2. The peak time for more comments per post was during 3 p.m - 4p.m where was the least favourite time to receive more average comments per post was at 9 a.m to 10 a.m
