# Movie Market Analysis: Guiding Microsoft's Movie Studio Strategy
![Logo](https://www.livemint.com/lm-img/img/2023/04/28/600x338/FILES-US-STOCKS-MARKETS-OPEN-0_1682684764176_1682684808221.jpg)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
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

├─ README.md

├─ student.ipynb

## Results
After analyzing various features, here are some visualization findings.
#### Number of movies released per year
![image](https://drive.google.com/uc?export=view&id=1pPq1TxeAFPtEkR9KERxrwsQ_ADdboXfo)

#### Genre Popularity
![image](https://drive.google.com/uc?export=view&id=1K6ZVMrZ0TX4zZFM5ANLXnulguzPCUU4s)
### Average Rating per Genre
![image](https://drive.google.com/uc?export=view&id=1w27-PiQh1L6f6OzxhqKHN3rVkqM4lRGI)
### Average Runtime Per Genre
![image](https://drive.google.com/uc?export=view&id=1yJRU788B9Pe8Labe4uEJeGRziJjOyQuA)

## Future Work
Collect any supplementary data, if accessible, to augment the analysis. This may encompass more recent film statistics, details about production expenses, or audience demographic information.
