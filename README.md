# Coders of Delhi – Pure Python Data Analysis & Recommendation System

A mini data analysis project built using **Pure Python** (without Pandas or NumPy). This project simulates a social media platform where user data is loaded, cleaned, analyzed, and used to generate recommendations.

## Project Overview

The project demonstrates how raw JSON data can be processed using only Python's built-in libraries.

The workflow includes:

- Loading user data from JSON
- Cleaning and structuring the dataset
- Handling missing values
- Removing duplicate records
- Building a **People You May Know** recommendation system
- Building a **Pages You Might Like** recommendation system

## Features

### Data Loading

- Read JSON data
- Parse user and page information
- Display user connections and liked pages

### Data Cleaning

- Remove users with missing names
- Remove duplicate friend entries
- Remove inactive users
- Remove duplicate pages
- Save cleaned data into a new JSON file

### People You May Know

Recommends new friends based on mutual connections.

Example:

User A → Friends: B, C

User B → Friends: A, D

Recommendation:

User A → D

### Pages You Might Like

Recommends pages using a simple collaborative filtering approach.

If two users like similar pages, pages liked by one user are recommended to the other.

## Technologies Used

- Python
- JSON
- Jupyter Notebook
- Built-in Python Data Structures
  - Lists
  - Dictionaries
  - Sets
  - Functions

## Project Structure

```
Coders_Of_Delhi/
│
├── Introduction.ipynb
├── data_cleaning.ipynb
├── data.json
├── data1.json
├── cleaned_data1.json
├── README.md
└── .gitignore
```

## Learning Outcomes

Through this project, I learned how to:

- Work with JSON data
- Perform data cleaning using Python
- Manipulate lists, dictionaries, and sets
- Build recommendation logic
- Organize Python code into reusable functions
- Solve real-world data problems without external libraries

## Future Improvements

- Implement the same project using Pandas
- Add data visualization using Matplotlib
- Build a web interface using Flask or FastAPI
- Store data in SQL
- Improve recommendation algorithms

## Author

**Bhanu Charan Kalla**

Aspiring AI / Data Science Engineer
