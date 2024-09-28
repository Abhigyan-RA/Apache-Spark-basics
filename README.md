# Apache Spark Basics with Python

This repository contains various exercises and examples demonstrating the power of Apache Spark using Python. It is based on a course that teaches how to use PySpark for large-scale data analysis and machine learning tasks. The provided notebooks and datasets walk through real-world scenarios, from processing movie ratings to building machine learning models.

## Repository Structure

The repository is organized into multiple folders, each corresponding to a different concept or hands-on activity covered in the course. Here's a breakdown of the contents:

### `1-moverating`
Contains the MovieLens dataset used to analyze and compute statistics such as the most popular movie, movie ratings, and recommendations.
- **Files**:
  - `ml-100k/`: Contains the MovieLens dataset files (`u.data`, `u.item`, etc.)
  - `moverating.ipynb`: Jupyter notebook analyzing movie ratings.

### `2-FriendsByAge`
Contains the example dataset `fakefriends.csv` to demonstrate filtering and transformations on Resilient Distributed Datasets (RDDs).
- **Files**:
  - `fakefriends.csv`: The fake friends dataset.
  - `friends-by-age.py`: Python script for analyzing the data.
  - `notebook.ipynb`: Jupyter notebook implementation.

### `3-MinTemp`
Contains an example to demonstrate filtering RDDs, showing how to compute the minimum temperatures by location.
- **Files**:
  - `1800.csv`: Dataset for minimum temperature analysis.
  - `filteringRDD.ipynb`: Jupyter notebook for temperature analysis.

### `4-Book`
Demonstrates mapping and flat-mapping techniques on text data.
- **Files**:
  - `Book.txt`: Sample text file for word count operations.
  - `Map-flatmap.ipynb`: Notebook illustrating the differences between `map()` and `flatMap()` in Spark.

### `5-customer-analysis`
Analyzes customer orders to compute the total amount spent by each customer.
- **Files**:
  - `customer-orders.csv`: Dataset containing customer orders.
  - `analysis.ipynb`: Jupyter notebook for customer spending analysis.

### `6-SparkSQL`
Shows how to use SparkSQL for data processing with structured datasets.
- **Files**:
  - `1800.csv`, `fakefriends.csv`: Datasets used for SQL-style data analysis.
  - Notebooks for querying data using SparkSQL.

### `7-AdvanceExamplesOfSpark`
Advanced Spark examples including:
- Using broadcast variables.
- Computing the most popular superhero.
- Recommending movies based on similarity.
- **Files**:
  - `Marvel+Graph`, `Marvel+Names`: Datasets for the superhero analysis.
  - `notebooks`: Jupyter notebooks with advanced Spark implementations.

## How to Use This Repository
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Abhigyan-RA/Apache-Spark-basics.git
2. **Install the required dependencies**:  
   Ensure you have Python and Jupyter notebooks installed, along with Apache Spark. Install any other necessary libraries using `pip`:
   ```bash
   pip install -r requirements.txt
