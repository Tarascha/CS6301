# CS6301
On going project for CS6301  
A pomodoro time trcker application    
Pomodoro Time Tracker (PTT)    
User Stories   
1.As an administrator, I want to be able to create users for PTT. To create a user, I need to specify their first name, last name, and email address; this email address will be used as the login name for the user.  
2.As an administrator, I want to be able to edit a user’s information. For now, I only want to be able to modify a user’s first and last name.  
3.As an administrator, I want to be able to delete a user. If the user has projects associated with it , the system should let me know and ask me for confirmation.  
4.As a user, I want to create and save projects, so that I can associate time worked (i.e., Pomodoros) to specific projects.  
5.As a user, I want to delete existing projects. If the project has time already logged to it, the system should let me know and ask me for confirmation.  
6.As a user, when I start a Pomodoro, the system should ask me if I want to associate it to a project. If so, the system will create the association, log the starting time, and initialize a counter of the number of (contiguous) Pomodoros completed. Otherwise, the Pomodoro would not be associated to any project (imagine a one-time activity, for instance).  
7.As a user, when I complete a Pomodoro associated to a project, including the break time, the system should increment the counter of the number of Pomodoros completed and ask me if I want to start another one. If so, the system should start a new Pomodoro. Otherwise, the system should log to the project (1) the starting time of the first Pomodoro I completed in this session, (2) the number of Pomodoros completed, and (3) the end time of the last Pomodoro completed.  
8.Similarly, as a user, if I stop a Pomodoro associated to a project, the system should ask me if I want to log the partial Pomodoro time to the corresponding project. If so, the system should log to the project (1) the starting time of the first Pomodoro in this session, (2) the number of Pomodoros completed, and (3) the time at which I stopped the last Pomodoro. Otherwise, and if I completed at least a Pomodoro, the system should log to the project (1) the starting time of the first Pomodoro I completed in this session, (2) the number of Pomodoros completed, and (3) the end time of the last Pomodoro completed.    
9.As a user, I want to select a project, a timeframe, and some options and generate a corresponding report on screen. The report should show, for each session logged for the selected project and timeframe, (1) starting and ending times and (2) time worked. Optionally, the report should also show the number of Pomodoros completed in the timeframe and the total number of hours worked on the project.   
