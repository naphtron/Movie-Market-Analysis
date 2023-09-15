
# Movie Market Analysis: Guiding Microsoft's Studio Strategy
![Logo](https://www.livemint.com/lm-img/img/2023/04/28/600x338/FILES-US-STOCKS-MARKETS-OPEN-0_1682684764176_1682684808221.jpg)
## Overview
This project involves the creation of a new Microsoft-backed movie studio. Our goal is to analyze current box office trends to help guide the studio's film production decisions, ensuring we invest in genres and themes that resonate with audiences and maximize success.
## Installation and Setup
### Code and Resources Used
 - Editor: Google Colab (https://colab.research.google.com/)
-  Python version: Python 3.9
### Python Packages Used
- Data Manipulation: Pandas, Numpy
- Data Visualization: Matplotlib, Seaborn
## Data
### Source Data
- Movie Database from IMDB (https://drive.google.com/file/d/1H1igb4JsvSqtIg7BmSFPON0DEsB_S4nd/view?usp=drive_link)
### Data Acquisition
- Information relevant for analysis was extracted from two tables. 
- movie_basics
![image](https://drive.google.com/uc?export=view&id=1ws9LVxOW28pwuB7RgLqE6h7nK9yezL7v)

- movie_ratings
![image](https://drive.google.com/uc?export=view&id=1-kbXkxVu852nJszu6DyYnAHmAMQpQaLL)

This data was merged into one table using pandas for effective analysis.
![image](https://drive.google.com/uc?export=view&id=1JhboJ5egxIFCdGPvSRAKGJHnluVvkzX3)
### Data Preprocessing
No duplicates existed in the data.
Found null values in two columns (genres and runtime_minutes)
Filled the null values in the runtime_minutes column with the median value.
Dropped the rows with null values in the genres column. They were less than 0.5% of the data.

## Code Structure




