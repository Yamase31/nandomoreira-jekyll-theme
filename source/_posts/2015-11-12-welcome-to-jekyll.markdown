---
layout: post
title:  "Blog Post #7"
date: 2015-11-12 16:08:24
categories: jekyll update
keywords: "welcome"
categories:
- welcome
tags:
- welcome
- hello-world
---

James Lawson
Monday, April 25th, 2016
Blog Post #7
Topic: Active Record Associations


Active Records Associations is a very important tool in the web developing world. Active Record is an interface between the database and your application. Active Records Associations let you structure your data models for users, comments, blog posts, followers, etc. in a logical and nearly plain-English way. If the framework for your database is overly complicated or inefficient, it may suffice at first, but if your website expands and there is more data in it, then your CPU will not be able to handle the data and you website will run slowly and you will lose users. ORM or Object-Relational-Mapping takes care of everything having to do with databases. ORM take the data that comes in and stores it into rows and columns. Here is a quick example of why Active Records Associations is better than SQL. If you want to get all the users in a database in SQL you would have to type: SELECT * FROM users. In Active Records Associations, all you have to type is: User.all. It is so much more intuitive, easier, and simplier. If you have a one to one relationship, matching up users and posts are easy because each user and post will have its own ID. More likely in a blog though, a single user will have many blog posts. This is where rails comes in handy because it makes this association very easy. If we are trying to get all of a users posts, we just query the posts table to look for and find all of that posts that are connected to that user's ID. This is a "has many / belongs to" association. There is another common relationship called a has_and_belongs_to_many relationship. An example of this would be taking a sports team and a player on the team would have many favorite coaches and the coaches would have many favorite players. This requires to create a join table to connect the ID’s of the two. Overall, Active Records Associations makes the process and interface of databases and applications so much easier that it was before and allows queries to be made using simple english in a easy to understand and simplistic way.

Word Count: 410

Sources:

http://guides.rubyonrails.org/association_basics.html
http://www.theodinproject.com/ruby-on-rails/active-record-basics
http://www.theodinproject.com/ruby-on-rails/active-record-associations
http://www.tutorialspoint.com/ruby-on-rails/rails-models.htm
http://culttt.com/2015/10/21/understanding-active-record-associations/
