# __Schema (Personal Agenda)__
#### Video Demo:  

## __Definition__
 This project is an interactive shell providing the user with a platform to plan their schedule for the day or for future.

 Project structure :
 - project.py
 - test_project.py
 - README.md

## __Libraries__

__datetime__: The datetime module supplies classes for manipulating dates and times. [(Readmore)](https://docs.python.org/3/library/datetime.html)

__pytest__: It will automate the tests as long as you write the bsic test cases. [(Readmore)](https://docs.pytest.org/en/7.2.x/)

## **Installing Libraries**
Libraries can simply be installed by this pip command:

```pip install -r requirements.txt```

## __Usage__

```python project.py```
```
project/ $ python project.py
WELCOME TO YOUR PERSONAL TASK MANAGER
Are you new to this software?
Type 1 if new otherwise type 0 ::1
Please enter the username by which you want to access your account:
Please enter here:  Jasleen
Password should be 8 characters long
Enter a password:  12345678
Enter your name please: Jasleen
Address: Model Town
Age: 18

Please proceed towards log in
Please enter your username
Enter here: Jasleen
Enter the password: 12345678
1--View Data
2--Add Task
3--Update Task
4--View Task Status
2
Enter the no. of tasks you want to ADD:
1
Enter the task: CS50 problem sets
Enter the target: today
Press space bar to stop!
```

## __Functioning__

The project.py contains 8 functions including the main function. These functions are as follows:

### _user_information()_:
This function takes the user information for creating a new user id.

### _signup()_:
This function is used to sign in into the software using the id user just created.

### _login()_:
This function is used to sign in into the id user just created or into any previously created id.

### _view_data()_:
This function is used to view the data entries.

### _task_information()_:
This function is used to add new asks o your to-do list.

### _task_update()_:
Thia function is used to update or change previously enetered tasks.

### _task_update_viewer()_:
This function is used to view the updated task list.



### Author : Jasleen Kaur
