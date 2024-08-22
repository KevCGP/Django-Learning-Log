# Learning Log Web Application Project 
Purpose of this project was to create a fullstack web application. Used a learning log concept where you can create a journaling system to document information you learned on a particular subject. 


## Technologies Used
HTML, CSS, Javascript, Python, Django 

## Lessons Learned 
By utilizing Django as the framework, I learned about the importance of template inheritance. Using a base template that contained the repeated elements and having other pages inherit elements from this page helped with workflow. The most difficult part of this project was making sure users' entry posts belonged to them and only they could see and edit those posts. This was done by restricting access to logged-in users by using decorators and then using foreign keys to tie data to specific users. This process ensures that user data is protected. For future attempts, I would like to make the app more stylized and interactive for users.
