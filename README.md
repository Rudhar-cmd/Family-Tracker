Family Tracker (Node.js + Express + PostgreSQL + EJS)
Technologies Used

Node.js – JavaScript runtime
Express.js – Web server framework
PostgreSQL – Database to store users and visited countries
body-parser – Middleware to parse form data
EJS – Template engine for dynamic HTML
HTML / CSS / JS – Frontend pages and styling

Project Summary

This project provides a family tracker system where multiple users can log the countries they have visited.
It connects to a PostgreSQL database, handles user switching, and dynamically displays visited countries on the front-end using EJS templates.

Features

Add new family members with name and color
Switch between users
Log visited countries for each user
Display total visited countries per user
Stores data persistently in PostgreSQL
Runs on port 3001

How to Use
Clone the Repository
git clone https://github.com/Rudhar-cmd/family-tracker.git

Navigate into the Project Folder
cd family-tracker

Install Dependencies
npm install

Set up PostgreSQL Database

Create the required tables: users, visited_country, country
