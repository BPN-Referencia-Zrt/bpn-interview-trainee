# Competency test

These tests are meant to **assess your competencies**. It is important for both of us to have a clear understanding of your current competencies when faced with problems similar to what you would encounter while working with us. The solutions will be discussed afterwards so make sure you are prepared to explain them.

## How to solve the test

First of all read the whole readme file and make sure you understand what is expected from you. If in doubt collect your questions and send it to your assessor (you will receive the assessor's contact information in a separate e-mail).

## Environment creation

Follow this guide (step 1. and 2.) to create a Fabric Data Warehouse:
https://learn.microsoft.com/en-us/fabric/data-warehouse/tutorial-introduction

Create test data in your warehouse by opening a new SQL query in the warehouse and running the contents of the create_test_data.sql file provided in this repository.

## Handing in your solution

Create a **private repository** in GitHub.
Create a new branch in your repository called feature_solutions.
Create a folder named Solution. All files that are part of you solution shall be put in this folder in a hierarchy of your choosing.
Make sure the solutions you submit is in line with how you would handle your daily tasks. Comment the code, format it etc.
We expect all text and code in your submission to be in English. 
If you are ready to submit your solution, add your assessor's GitHub username to your project.

To do this, follow these steps:
1. Go to project settings (https://github.com/<Reponame>/settings)
2. Collaborators and teams
3. Manage Access
4. Add people
5. Add the provided github users with "Triage" permissions
6. Create a pull request (feature_solutions -> main branch) and add the assessors as reviewers.
    1. Make sure you explain your solutions in the pull request!

## Tasks

Write SQL queries to solve the following tasks. Each task should be in its own file in the Solution folder. The files should be named according to the task, e.g. task1.sql, task2.sql, etc.

### Task 1: 

Find tasks that were due in the past 2 weeks.

### Task 2: 

Identify employees with multiple tasks. Display their name and how many tasks they have.

### Task 3: 

Write a query that shows the order tasks should be done for each project (assuming the most important tasks are the ones where the due date is the latest).

### Task 4:

Write a query that finds the best employee.

### Task 5: 

Answer the question: Employee, Project, Task. Which table(s) could be considered fact table(s) and which table(s) could be considered dimension table(s)?