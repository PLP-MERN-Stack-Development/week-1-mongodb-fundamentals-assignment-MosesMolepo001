# PLP Bookstore - MongoDB Fundamentals Assignment

This repository contains the implementation of the MongoDB Fundamentals assignment as part of the PLP MERN Stack Development course.

---

## 📚 Project Overview

This project involves setting up a MongoDB database for a bookstore, performing CRUD operations, advanced queries, aggregation pipelines, and indexing to optimize performance.

---

## 🚀 Features Implemented

- Created a MongoDB database called `plp_bookstore` and a collection named `books`
- Inserted sample book documents with fields such as `title`, `author`, `genre`, `published_year`, `price`, `in_stock`, `pages`, and `publisher`
- Performed basic CRUD operations (find, update, delete)
- Executed advanced queries including filtering, projection, sorting, pagination
- Built aggregation pipelines to analyze data (average price by genre, author with most books, grouping by publication decade)
- Created indexes on key fields to optimize query performance

---

## 🛠️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/MosesMolepo001/week-1-mongodb-fundamentals-assignment.git

   cd week-1-mongodb-fundamentals-assignment

Install dependencies

bash
Copy
Edit
npm install
Set up MongoDB

Option 1: Use MongoDB Atlas (recommended for cloud)

Create a free cluster on MongoDB Atlas

Whitelist your IP address

Get your connection string and update it in insert_books.js

Option 2: Install MongoDB locally

Download and install MongoDB Community Server from MongoDB Download Center

Start your MongoDB server

Insert sample books data

bash
Copy
Edit
node insert_books.js
Run queries

Use MongoDB Shell (mongosh) or MongoDB Compass GUI

Connect to your database and run queries saved in queries.js

📁 Files in the Repository
insert_books.js - Script to insert sample book data into MongoDB

queries.js - MongoDB queries for CRUD operations, advanced queries, and aggregation pipelines

README.md - Project overview and setup instructions

Screenshot of MongoDB Compass/Atlas connection and sample data (for submission)

