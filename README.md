# Animal Shelter Database Management and Analytics System

A database-driven web application for managing and analyzing animal shelter intake and outcome data using **MySQL, Node.js, Express, EJS, and Python**.

## Project Overview

This project was developed to design and implement a relational database system for animal shelter records and to provide a simple web interface for analytics and reporting. The system stores animal intake and outcome data, loads records from CSV datasets, and supports SQL-based analysis through a Node.js web application.

The project demonstrates:
- relational database design
- SQL query development
- CSV data loading with Python
- backend web development with Node.js and Express
- result presentation using EJS templates

## Features

- Designed a normalized MySQL database for animal shelter data
- Imported shelter datasets from CSV files using Python
- Built a web application using Node.js, Express, and EJS
- Performed analytical SQL queries on intake and outcome records
- Displayed query results through browser-based views

## Analytics Included

The project answers the following analysis questions:

1. **Average stay before adoption by animal type**
2. **Relationship between intake condition and outcome type**
3. **Monthly stray intake trends**

## Technologies Used

- **MySQL** — database design and querying
- **Node.js** — backend runtime
- **Express.js** — web framework
- **EJS** — templating engine
- **Python** — CSV data loading
- **Pandas** — data preprocessing for database import

## Project Structure

```text
Database/
├── aac_intakes.csv
├── aac_outcomes.csv
├── load_data.py
├── query1.sql
├── query2.sql
├── animal_shelter_app/
│   ├── server.js
│   ├── package.json
│   ├── views/
│   └── node_modules/   # should not be uploaded
