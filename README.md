# NoSQL_Challenge
# UK Food Standards Database Analysis

This project involves analyzing food hygiene ratings data provided by the UK Food Standards Agency. The analysis is aimed at helping the editors of the food magazine **Eat Safe, Love** evaluate and explore establishments across the United Kingdom.

## Project Overview

The project is divided into three main parts:

1. **Database Setup**:
   - Import the provided `establishments.json` file into MongoDB.
   - Set up a Jupyter Notebook to confirm the database and collection are properly loaded.

2. **Database Updates**:
   - Add new restaurant data to the collection.
   - Update and clean the data to ensure consistency, including converting data types.
   - Remove unwanted records, such as establishments in specific locations.

3. **Exploratory Analysis**:
   - Answer key questions to help guide future articles for the magazine, such as identifying establishments with high ratings or poor hygiene.

## Files in This Repository

- **`NoSQL_setup_starter.ipynb`**: Jupyter Notebook for database setup and updates.
- **`NoSQL_analysis_starter.ipynb`**: Jupyter Notebook for data exploration and analysis.
- **`establishments.json`**: The dataset containing food hygiene ratings for establishments across the UK.
- **`README.md`**: Project documentation.

## Technologies Used

- **Python**: Data manipulation and analysis.
- **MongoDB**: NoSQL database to store and query establishments data.
- **PyMongo**: Python library for interacting with MongoDB.
- **Pandas**: Data analysis and conversion of query results into DataFrames.
- **Jupyter Notebook**: Interactive coding environment.

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/uk-food-standards-analysis.git
   cd uk-food-standards-analysis
Import the dataset into MongoDB:

bash
Copy code
mongoimport --db uk_food --collection establishments --file establishments.json --jsonArray
Open the Jupyter Notebooks:

Use NoSQL_setup_starter.ipynb to set up and update the database.
Use NoSQL_analysis_starter.ipynb to perform the exploratory analysis.
## Key Analysis Questions
Which establishments have a hygiene score of 20?
What are the establishments in London with a RatingValue greater than or equal to 4?
What are the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, near the new restaurant "Penang Flavours"?
Which Local Authority areas have the most establishments with a hygiene score of 0?
Results and Insights
## The results of the analysis are aimed at helping Eat Safe, Love identify:

High-rated establishments to recommend.
Areas or establishments with poor hygiene to highlight for improvement.
Regions with the most establishments requiring attention.
