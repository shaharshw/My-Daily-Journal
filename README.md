This project is a part of the "The Complete 2023 Web Development Bootcamp" course offered on the Udemy platform.

# Daily Journal

Welcome to Daily Journal! This is a simple blogging web application built with Node.js and Express, and it utilizes MongoDB as the database to store all the blog posts and related data. It allows you to compose blog posts and view them on the home page. You can also view individual blog posts by clicking on the "Read More" link.

## Introduction

Daily Journal is a basic blogging platform that enables users to write and publish their thoughts, ideas, and experiences. It provides a simple and intuitive user interface for creating and managing blog posts. Users can access the home page to read the latest posts or click on a specific post to view it in detail.

## Features

- Home page displaying the latest blog posts
- Individual post pages with full content
- Compose page to create new blog posts
- Responsive design for optimal viewing on different devices
- Use of EJS templating for dynamic rendering of views
- Data saved in MongoDB Atlas for reliable and scalable storage

## Installation

To run Daily Journal locally on your machine, follow these steps:

1. Clone the repository
2. cd daily-journal
3. npm install
4. Set up a MongoDB Atlas account and create a new cluster to obtain the connection string.
5. Replace the placeholder <YOUR_MONGODB_ATLAS_CONNECTION_STRING> in the app.js file with your MongoDB Atlas connection string.
6. npm start
7. Open your web browser and visit http://localhost:3000 to access the application.

## Usage

Once you have the Daily Journal application up and running, you can perform the following actions:

View the home page to see the latest blog posts.
Click on a specific post to view its full content.
Create a new post by visiting the compose page and filling in the title and content fields.
