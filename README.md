# datafun-07-ml-predictive
## Laura Gagnon-Vos 09/27/23
### https://github.com/lauravos/datafun-07-ml-predictive 

## Assignment - Linear Regression

In this final module, you'll employ machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. We'll employ a type of supervised learning, simple linear regression, to train a model using all available data and use the resulting model (a best-fit straight line) to make predictions.

## Chapters
Work through the book and examples from Chapter 10 refreshing especially your work on 10.16 on Time Series and Simple Linear Regression.
Read through the book and examples from Chapter 15 on Machine Learning, focusing on 15.4 Simple Linear Regression and Predictions.

## Task 1 - Prepare Your Module Repository
GitHub
Create a new repository named datafun-07-ml-predictive on GitHub.
Initialize it with the default README.md.
Local Machine
In VS Code, clone your new repo into your Documents folder.
Repository Essentials
Add a .gitignore file from a previous Python project.
Add a requirements.txt file to hold external dependencies for Jupyter notebooks and others as you need them. 
Update README.md
Modify the README.md to include your name, the link to your repo, and the focus of this project repository. 
Include instructions with the exact commands to: 
Create and activate your virtual environment.
Install all required external dependencies.
Execute your Python files.
Create your local virtual environment (hint: use venv to create a .venv folder)
Activate your local virtual environment (hint: call a command in the .venv subfolder)
Install any external dependencies you need (hint: use requirements.txt and all the files needed for Jupyter notebooks, pandas, etc.)
Push to GitHub 
Add and commit all your changes with a commit message "Initialized repo"
Push your changes to GitHub
 

### Task 1 - Verify Repository
Take a screenshot of your GitHub project repository after you've pushed these changes to GitHub.
Display the screenshot as evidence of task completion.
 

## Task 2 - Work Through Chapter 10 
Read and work through Chapter 10 - Object-Oriented Programming - and understand the examples. 

10.1 Introduction
10.2 Custom Class Account
10.3 Controlling Access to Attributes
10.4 Properties for Data Access
10.5 Simulating “Private” Attributes
10.6 Case Study: Card Shuffling and Dealing Simulation
10.7 Inheritance: Base Classes and Subclasses
10.8 Building an Inheritance Hierarchy; Introducing Polymorphism
10.9 Duck Typing and Polymorphism
10.10 Operator Overloading
10.11 Exception Class Hierarchy and Custom Exceptions
10.12 Named Tuples
10.13 A Brief Intro to Python 3.7’s New Data Classes
10.14 Unit Testing with Docstrings and doctest
10.15 Namespaces and Scopes
10.16 ★ Intro to Data Science: Time Series and Simple Linear Regression
 

### Task 2 - Verify Ch 10
Take a screenshot of one of the Chapter 10 examples running in your VS Code environment on your machine.
Tell us why you chose that part of your work. 
 

## Task 3 - Work Through Chapter 15
Read and work through Chapter 15 - Machine Learning - and understand the examples. 

15.1 Introduction to Machine Learning
15.1.1 ★ Scikit-Learn
15.1.2 ★ Types of Machine Learning
15.1.3 Datasets Bundled with Scikit-Learn
15.1.4 Steps in a Typical Data Science Study
15.2 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 1
15.3 Case Study: Classification with k-Nearest Neighbors and the Digits Dataset, Part 2
15.4 ★ Case Study: Time Series and Simple Linear Regression
Suggestion: Specify data file paths as Python raw strings. See FAQ for more.

### Task 3 - Verify Ch 15
Take a screenshot of one of the Chapter 15 examples running in your VS Code environment on your machine.
Tell us why you chose that part of your work.
 

## Task 4 - Implement 10.16 and 15.4 
Add a notebook to your project repository and follow the process provided in the text. 

Use a notebook (rather than interactive mode). 
Create a new notebook in your repository with an appropriate file name and extension. 
Add all external dependencies to your requirements.txt and install them into your active virtual environment as needed using the command in your README.md. 
In a Markdown cell at the top of the notebook, add:
The Notebook Title
Your Name as Author
A Clickable Link to your Project Repository
### Part 1

Add a Markdown heading for Part 1 - Linear Regression.
Follow the instructions from 10.16 (starting page 414).
Use Markdown cells to create section headings as you work. 
Use pandas DataFrames to plot Celsius vs Fahrenheit 
Note: The data is for the average (daily) high temperature in January over many years.
For example, in 1895, the average high temperature in January was 34.2.
We only care about this one series of data: the "average high temp in Jan".
There's a lot of stats in the title, and it has confused students. Just think of each value as "the temperature" for that year.
We'll use all of the data available to build a best-fit line (supervised learning). 
We'll use the slope and intercept of the best-fit line to estimate a point out in the future.
Refresh your understanding of the equation for a line (y=mx +b)
Section 1 - Load: Follow the instructions to load NY City January high temperature from a csv file into a DataFrame.
Section 2 - View: Follow the instructions to view head and tail of the file. 
Section 3 - Clean: Follow the instructions to clean the data.
Section 4 - Describe: Use describe() to calculate basic descriptive statistics for the dataset. 
Section 5 - Calculate Line: Use the SciPy stats module linregress function to calculate slope and intercept for the best fit line through the data.
Section 6 - Predict: Use your results to predict the "average high temp in Jan" for the year 2026. 
Section 7 - Plot: Follow the instructions and use Seaborn to generate a scatter plot with a best fit line. Set the axes and y limit as instructed.
### Part 2

In the same notebook, add a Markdown heading for Part 2 - Machine Learning.
Continue with 15.4 (staring page 620). 
This time, we'll use scikit-learn estimator, and we'll practice splitting data for training (to build a model) and testing (testing our model against known values). 
Follow the instructions all the way though charting it again with the specified axes.
Add Section Headings as you work. 
At the end of your notebook, add a final section with some remarks comparing the two methods.
Excellent analytical skills need professional communication skills to be of maximum benefit. 

 

### Task 4 - Push to GitHub
Execute the completed notebook
Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
At the end, use a commit message like "Task 4 complete".
Verify your GitHub notebook appears complete and well-presented. 
 

### Task 4 - Verify
Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
Display the screenshot as evidence of task completion.
Optional Bonus
Practice more machine learning skills by working through 15.5 with the California Housing Dataset.
In the same notebook, add a Markdown heading for Part 3 - Bonus.
Follow the instructions all the way though loading the data, training and testing the data, visualizing the data, and choosing the best model from the 4 listed. 
Use appropriate Markdown Section headings to present your work. 
Customize your presentation and include helpful remarks to "tell a story with data".
 

## Optional Bonus - Push to GitHub
Execute the completed notebook
Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
At the end, use a commit message like "Part 3 Bonus complete".
Verify your GitHub notebook appears complete and well-presented. 
 

### Optional Bonus - Verify
Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
Disply the screenshot as evidence of task completion.
Reflection (on your own)
Learning the details of Python, some of modules from the standard library, and several of the key packages for data science was a lot for seven modules. 
What do you wish you'd known earlier? 
Feedback
This course is a graduate-level course for people with a Bachelor's degree, but not necessarily any experience in programming. It should be useful for both CS majors and non-majors.

Your feedback and unique perspective is key to helping us design courses to meet this challenge.  

Please complete the official course evaluation form. The mid-term survey is used by the instructor to improve the course experience. The course evaluation is used by NW and our school of CSIS. We want to ensure your NW degree is valuable and a good use of your time! 

## Submission Instructions
Project Submission Instructions
Non-clickable links and or other non-compliant (or incomplete) submissions are not eligible for credit.
No resubmissions after the deadline will be reviewed.
In Module 7, no late work is accepted (regardless of reason). 
Submit
Part 1 - Project 
Paste a clickable link to your public GitHub repo: 
About how long did you spend on class this module:
In general, how did it go:
What was the most difficult part:
What was most interesting:
Did you do the optional bonus (y/n). How did it go - or why not? 
Part 2 - Self Assessment

## From the Module 7: Overview, paste the numbered list of objectives and assess your ability on each as "Highly proficient", "Proficient", or "Not Proficient":

Part 3 - Screenshots

Display GitHub Repo After Task 1:

Display Task 2 Screenshot Ch 10 with remarks:

Display Task 3 Screenshot Ch 15 with remarks:

Display GitHub Repo After Task 4:

(Optional) Display GitHub Repo After Bonus: