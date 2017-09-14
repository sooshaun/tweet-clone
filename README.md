# README

# Database (DB)
## Entity Relationship Diagram (ERD)
![erd database](/doc/image.png)

# DB Tables

I made 3 tables for my app, User, Tweet and Profile. User stores the user information like passowrd etc. Tweet stores the information message that a user tweets and the Profile table stores information about the user.

Each user has one profile and many Tweets.
Tweet has one User.
Tweet belong to User.

## User Table
- id (integer)
- email (string)
- password (string)

## Profile
- id (integer)
- avatar  (string)
- first_name (string)
- last_name(string)
- user_id(belongs to) <== means many to one>

## Tweet
- id (integer)
- message (string)
- user_id(belongs to)  <== means many to one>

# Pages
## homepage
- tweets on page
- log in/log out

## Tweet show page
- see tweet
- edit tweet (if logged in)


## Profile Page
- first_name, last_name
- tweet count
- avatar
- country
- edit ability

#Figma(wireframe)
.....



==========================

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
