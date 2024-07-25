# FTL_pair_coding_exercises


I- Python OOP 

1. Write a Python program to create a class representing a circle. Include 
methods to calculate its area and perimeter. 
2. Write a Python program to create a calculator class. Include methods for basic 
arithmetic operations. 
3. Write a Python program to create a person class. Include attributes such as 
name, country, and date of birth. Implement a method to determine the 
person's age. 

II- API Call With Python 

In this task, you will make an API call using Python. Api_key and the website address will be provided to 
you. api_key= '010858a3a88847f1a4154131242207' 
Web address= " http://api.weatherapi.com/v1/current.json" 

         Step 1: Import the request module 
         Step2: create a dictionary called ‘params’ with the following values. ‘api’=api_key and   ‘q’=city_name 
         Step 3: make an HTTP request to the web address. When you do the request, don’t forget to give              
params as the parameter. 
          Step 4: print the response content 

Congratulations! You made a successful API call. 
[optional]: create a python object to represent the incoming weather information. 

III- Web Scrapping with python 
In this task, you will scrape all the images on a website. Follow the following steps. 

Step 1: Search ‘Animals’ on your browser. 
Step 2: Click on images and you will see pictures. 
Step 3: copy and paste the link at the top of the browser and give it to your code. 
Step 4: use the request module to send an HTTP request to the link you copied. 
Step 5: use the Beautiful Soup Module to search for img tags in the resulting response content 
Step 6: pull out the link of the image from src of the image and make another HTTP request with 
the link. [ you may need error handling for any potential error]. 
 Step 7: write the content of the response to a file. 

  Congratulation! You have scrapped all the images on a page without manually saving them. 


IV- SQLite3 in Python: Managing a School Database 

1. Create the database: School 
Create a table called "students" with the following columns: 
•id: an integer primary key for each student 
•last_name: the student's last name 
•first_name: the student's first name 
•age: the student's age 
2. Insert records (data) 
3. Modify records 
4. Perform a query to select data from the created table 
