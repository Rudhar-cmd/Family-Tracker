# Family Tracker (Node.js + Express + PostgreSQL + EJS)

This is a Node.js web application that allows users to track countries visited by family members. Users can switch between family members, add new users, and log visited countries. The app uses PostgreSQL for data storage and EJS for rendering dynamic pages.

-- ## Technologies Used

Node.js – JavaScript runtime

Express.js – Web server framework

PostgreSQL – Database to store users and visited countries

body-parser – Middleware to parse form data

EJS – Template engine for dynamic HTML

HTML / CSS / JS – Frontend pages and styling

-- ## Project Summary

This project provides a family tracker system where multiple users can log the countries they have visited. It connects to a PostgreSQL database, handles user switching, and dynamically displays visited countries on the front-end using EJS templates.

-- ## Features

Add new family members with name and color

Switch between users

Log visited countries for each user

Display total visited countries per user

Stores data persistently in PostgreSQL

Runs on port 3001

-- ## How to Use

Clone the repository:

git clone https://github.com/Rudhar-cmd/family-tracker.git


Navigate into the project folder:

cd family-tracker


Install dependencies:

npm install


Set up PostgreSQL database with the required tables (users, visited_country, coountry)

Start the server:

node index.js


Open your browser and visit:
http://localhost:3001

-- ## License

This project is open source and available under the MIT License.
