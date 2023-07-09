# Movie-Dataset-correlation-Project-using-Python

Data source: Kaggle - https://www.kaggle.com/datasets/danielgrijalvas/movies
Python environment: Written via Jupyter notebook
Libraries utilized: This project involved the use of libraries such as pandas, seaborn and matplotlib 
![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/4dc6edc8-801b-4a4c-94f4-500839ff04ca)

Below is a summary of the steps undertaken in this project:

#1 - Reading in the data 
The downloaded Kaggle dataset was read in as a dataframe 
![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/04b3812b-1a69-4eb2-9be8-95b71f987b14)

#2 - Checking for missing data 
This was accomplished using a for loop 

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/e0bf1762-2ecc-4fca-80ab-ee5527caeb92)

There are multiple approaches to handling missing data. In this situation, I opted to simply remove the data that was missing from the dataset. This method is straightforward, but it carries the potential of introducing bias into the results.

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/c6ba1bf7-8b74-4e5b-9d9b-d47634ed4b5c)

#3 - Modifying data types
Understanding the data types
![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/23bf9fad-c0e5-4c93-9a10-d10c4a782a1c)

Modifying numerical variables of interest - budget and gross revenue. Converting it to integers to eliminate the decimals 

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/5364f90d-124b-4573-bc52-4af1be157468)


#4 - Correlation analysis 
Investigating the correlations between budget, company, votes and gross revenue. Checking to see the relationship between each of the three 
aforementioned variables and the gross revenue.

#Relationship between a movie's budget and its gross revenue

A scatter plot was used to investigate this 

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/7d331eca-a1a1-4410-a877-471d6880edf7)

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/922a334a-8882-45c4-91fc-e8ebe1d8260c)

Including a line of best fit

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/0ac63f83-cfc5-4bb3-b340-a72b9021406d)

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/c1553a3b-9ec8-4b09-a447-f363f9274e71)

Creating a heatmap to obtain the correlation matrix for all numerical variables 

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/2887b59c-6821-4e09-8c43-94b3ca352844)

![image](https://github.com/OghaleAgbawhe/Movie-Dataset-correlation-Project-using-Python/assets/133532704/207ea744-9c2d-4a76-aa99-d7d09888a930)


