Backend Development with Express.js and MongoDB

## Blog Api's

About the Assignment
** Backend development using Express.js and MongoDB created a simple RESTful API that performs CRUD (Create, Read, Update, Delete) operations on a collection in a MongoDB database. **

Built with
Node.js
Express.js
Java Script
Mongo Db
Mongoose
Getting Started
To get a local copy up and running, please follow these simple steps.

Prerequisites
Here is what you need to be able to run this assignment.

- Node.js
- MongoDb
- Npm
  Development
  Setup
  1 Clone the repo into a public GitHub repository with this link

       https://github.com/SubhamGaikwad/blog_Api.git

  2 Go to the project folder

       cd server

  3 Install packages with npm

      npm install

  4 Set up your .env file

_ Duplicate .env.example to .env
_ Use MONGO_URL as your mongo db url
Quick start with nodemon index
nodemon index
For testing the API's
1 For Registration Use API's
http://localhost:5000/api/auth/register

2 For Login Use API's
http://localhost:4000/api/auth/login

## User

3 For update Users U can use APi's
http://localhost:4000/api/users/id

4 For update Users U can use DELETE API
http://localhost:4000/api/users/id

5 Getting specified user with GET API
http://localhost:4000/api/id

## Post

1 U can post the blog post using the Url
http://localhost:4000/api/posts/

2 u can update the posts using the Url
http://localhost:4000/api/posts/id

3 U can delete the post using the url
http://localhost:4000/api/users/id

4 U can get the post by category wise and username wise
http://localhost:4000/api/users/username
http://localhost:4000/api/users/catName

## Category

1 u can add category by using the url
http://localhost:4000/api/categories

2 u can get the category by using the url
http://localhost:4000/api/category
