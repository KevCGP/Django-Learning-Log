# Learning Log Web Application Project 
Purpose of this project was to create a fullstack web application. Used a learning log concept where you can create a journaling system to document information you learned on a particular subject. 

<img width="1438" alt="Home" src="https://github.com/user-attachments/assets/3fc322a7-3bc3-4ee6-9255-6ed3dafe758c">

<img width="1243" alt="Topics" src="https://github.com/user-attachments/assets/134a88b1-8b28-4aa4-a72f-9c266b55361f">




## Technologies Used
HTML, CSS, Javascript, Python, Django 

## Lessons Learned 
By utilizing Django as the framework, I learned about the importance of template inheritance. Using a base template that contained the repeated elements and having other pages inherit elements from this page helped with workflow. The most difficult part of this project was making sure users' entry posts belonged to them and only they could see and edit those posts. 

<img width="1243" alt="Entries" src="https://github.com/user-attachments/assets/21b0e67f-33dc-4c37-b2eb-edd498d7a30b">


This was done by restricting access to logged-in users by using decorators and then using foreign keys to tie data to specific users. This process ensures that user data is protected. For future attempts, I would like to make the app more stylized and interactive for users.
