# Course Recommendation System

This project was cloned by me for my Final Year Project.
I originally cloned it from https://github.com/pratik9409/Course_recommendation.

In this project , it uses text mining for extracting the data what the user has entered and goes through several Machine Learning Algorithms and suggest the courses for the User.
It also redirects the page to Udemy course if you clik on the course which is suggested.

Steps for making this project run:

1. Reinstall the python from https://www.python.org/downloads/ (My Suggestion-easy method) OR Add the python path to Environmet Variables.
2. Make sure that you choose the option "add to path" while installing it.
3. Choose python interpreter in VScode and select GLOBAL which will be "~\AppData\Local\Python\Python312\python.exe"
4. Run the app.py file in python debugger
5. Then install packages like scikit-learn, neattext, pandas.(eg: type "pip install pandas" in command line interface to install that package.)
6. After installing the respected packages, run app.py again. the file will work fine then.
7. click on the link which they will provide or copy paste the link to a browser to get the output of your work.

The below documentation is given by pratik9409 who is the owner of this project

In this Project, I have a built a udemy course recommendation system. It will recommend similar courses for which the user is searching/looking.
In this project we used technilogies such as NLP, Machine Learning, Chart.js (for making interactive Dashboard).

https://user-images.githubusercontent.com/67755812/217238247-a2301023-697d-4476-90e0-b856b65019e1.mp4

Workflow:

1. Importing the dataset.
2. Perfomed Text Processing and EDA and generate insights, then convert text to numeric values.
3. After converting text to numeric values, will calculate the cosine similarity score.
4. Then will sort the values which have similar similarity score and recommend the course.
5. Integrate the Recommendation System with FLASK Framework.
