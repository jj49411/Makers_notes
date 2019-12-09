# Week 4

[Weekly Goals](#weekly-goals) | [Daily Goals](#daily-goals) | [Weekly Challenge](#weekly-challenge) | [Weekend Challenge](#weekend-challenge) | [Workshops](#workshops)



## Weekly Goals

1. Build a simple web app with a database
2. Follow an effective debugging process for database applications
3. Explain the basics of how databases work (e.g. tables, SQL, basic relationships)

** Use SQL in a controller to read a bookmark record from a database.

## Daily Goals
### Day 1
- GOAL: Review other's weekend challenge. ** Check out the difference between class method and instance method 
- REFLECTION: Made a diagram for my rsp-app. Refactored my code and added more features
> I was flying solo for the afternoon challenge, so I had some time to look at the settings for database and psql. Also Built the feature, including controller, model, and database code
```
- use PG to let us write SQL in Ruby code
- psql interactive shall- to deal with data, matipulate the table...
```

### Day 2
- GOAL: Understand the basics of how databasese work. Work on practicals
- REFLECTION: Have done the SQLZoo practical(SELECT basics/SELECT from world/). Had a better understanding on how to use SQL in my ruby code
> Learned how to use SQL at psql interface, setting up 'pg' in Ruby file to connect to SQK database
evening: finish week3.md/ my post!!

### Day 3
- GOAL: Create databases/tables, using psql interface to manipulate the data. Domain modelling using CRC cards(class/ responsibilities/table)
- REFLECTION: Setting up for testing environment and TablePlus
> Nice teamwork exploring ENV, truncate/drop table. During the workshop, learned to generat user stories from requirements and implement a one-to-many relationship

### Day 4
- GOAL: Keep on SQL practice(SLECT from name) and draw out the diagrams based on user stories. Work on practicals, try to fill the gaps of the weekly challenge
- REFLECTION: Knew how to attach a database to a web application
> Followed the debugging process to add the function on the model/ call the method on the controller, using SQL to interact with databases and store the user's input in the data

### Day 5
- GOAL: Using CRC cards and diagrams to draw out the project, looking at the MVC relationships
-REFLECTION: understood the idea of wrapping the data in Ruby objects and did some practices


## Weekly Challenge
- **Bookmark-Manager**: A web application with a database that enables the user to view and store bookmarks. Following an effective debugging process to test drive the controller using feature tests/ the model using unit tests. Installed `pg` gem for inserting `SQL` code in Ruby. Repo [here](https://github.com/jj49411/bookmark_manager_thu)


## Weekend Challenge
- **Chitter**: wrote a Twitter clone that allows the user to sign up and post messages to a public stream. First individual web app with a database. Would add more features to sign in/ interact with other users' posts in the future.
Repo [here](https://github.com/jj49411/chitter-challenge)


## Weekly reflection

This week we moved on to building up a web app that uses a database. We were introduced to PostgreSQL, SQL, PG and psql and learned how to connect to a database in our Ruby code. It is basically another extra concept adding on building a web page. Last week we used MVC cycle to create web apps, whereas in this week we are able to store the user input in the database and manipulate it by calling commands.

