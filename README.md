# HackerNews
Comparing Ask HN and Show HN posts from HackerNews site. This is guided analysis from the Data Analysis course by Dataquest.

##Hacker News Posts Analysis
In this project, I compared two types of posts (Ask HN and Show HN) from a popular site known as Hacker News for technology related stories.

Users submit Ask HN posts to ask the Hacker News community a specific question and Show HN posts to show the community a project, product, or just generally something interesting. I compared these two types of posts to determine the following:

Do Ask HN or Show HN receive more comments on average?
Do posts created at a certain time receive more comments on average?
I used the datetime module to access the date and time information of each posts using the datetime.strptime() constructor, datetime.strftime() method etc.,

This dataset was reduced by removing all submissions that did not receive any comments, and then randomly sampled from the remaining submissions.
