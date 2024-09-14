# ShowMyBooks - Book Recommendation System

![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Overview

This project presents a Book Recommendation System, namely ShowMyBooks, which leverages machine learning to deliver personalized book suggestions to users based on their unique preferences and reading habits. This is measured using a dataset where users(readers) have rated various books, and the ratings as well as the votes are used to recommend books accordingly.

## Key Features

- **Personalized Book Recommendations**: Harnesses collaborative filtering and content-based filtering algorithms to generate accurate book suggestions.
- **Comprehensive Dataset**: Utilizes a large dataset from Kaggle, containing book information, users and their ratings.
- **Full-Stack Development**: Built using Flask for server-side logic, HTML, CSS, and JavaScript for the user interface, and Python libraries for data analysis and machine learning.
- **Scalable Deployment**: Successfully deployed on Render, ensuring high availability and scalability.

## Technical Details

### Data Ingestion

- Imported dataset from Kaggle, comprising CSV files containing book information, user deatils and their ratings.
- Performed data preprocessing and feature engineering using Pandas, NumPy, and Scikit-learn

### Recommendation Engine

- **Collaborative Filtering**: Combines the power of likeminded users to discover patterns in their ratings and pick books that users like you have voted for.

- **Content-Based Filtering**: Studies characteristics of books (genre, author, etc) to make recommandations on books very alike to the ones user has liked or interacted with.

### End-to-End Solution

- Developed a seamless and scalable web application by combining:
  - Flask's powerful backend capabilities for server-side logic
  - HTML, CSS, and JavaScript for creating an engaging and user-friendly interface

### Deployment

- **Render**: Successfully deployed the web application on Render using GitHub Actions, resulting in a 30% reduction in deployment tim

## Showcase

This project showcases my expertise in:

- Machine Learning
- Data Analysis
- Full-Stack Development
- Deployment of live applications that drive user engagement

## Repository Contents

- `(app.py)`: Flask application code
- `data`: Dataset and data processing scripts
- `models`: Machine learning model implementations
- `templates`: HTML templates for the user interface
- `static`: CSS and JavaScript files for the user interface

## Getting Started

1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run the application using `python (flask run)`
4. Access the application at https://showmybooks.onrender.com/
