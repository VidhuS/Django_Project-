# Django_Project- 
 
STEPS TO SET UP THE RIGHT ENVIRONEMNT AND RUN THE PROJECT 
 
1. After downloading the folder. Open PowerShell on Windows or terminal if you are 
using Mac.  
2. Cd to the project directory and type Scripts/activate if on Windows. (Note if you are 
using a Mac please use ‘bin/activate’). This will put you inside the virtual 
environment  
3. Cross check if you have Django version 2.0.7 in your virtual environment. You can 
check it using ‘pip freeze’ command. 
(Note-If your version is not the same type ‘pip install Django==2.0.7’)
4. Cd to src in order to enter the source file of the project. 
5. Once inside the source folder type ‘python manage.py runserver’.  
6. Now that your local server is running. Open your web browser and enter 
http://127.0.0.1:8000/ to run the website 


VALUE DERIVED 
1. The website is aimed at providing two essential information. 
a. Display the ranking of the companies based on frequency of their 
transactions with one another. 
b. Check whether a company name exists in our database or not 
  
![1](https://user-images.githubusercontent.com/43739144/133906619-5b2aa0de-6638-48f6-a57f-e7bc6bb722b0.PNG)


2. The first task is achieved on the home page itself where firstly user is greeted with general 
information about the companies and just below that a graphical and interactive graph. 
 
 ![2](https://user-images.githubusercontent.com/43739144/133906625-fa992184-39fb-4aac-854d-5d36123fc910.PNG)

 
3. Shows the ranking of the companies based on frequency of their transactions with 
one another. 
4. The second page allows the user to enter the name of their vendor or 3rd party 
company and see if the company is registered in our database or not.

![3](https://user-images.githubusercontent.com/43739144/133906631-98e23119-7c1b-44ba-b38f-7d4f2b0eed51.PNG)

