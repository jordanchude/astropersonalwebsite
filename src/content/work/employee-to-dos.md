---
title: Employee To-Dos
publishDate: 2018-10-02 00:00:00
img: /assets/employee-to-dos.png
img_alt: Screenshot of app to with an interface to add employees to a list with their name, title, and photo.
description: |
  A full CRUD, full-stack to-do application, built with HTML, CSS, and Javascript that utilizes a MongoDB API to store and update to-dos.
tags:
  - Design
  - Frontend
  - Backend
  - Dev
---

**Website**: https://employee-to-dos.netlify.app/ <br>
**Frontend Code**: https://github.com/jordanchude/to-do-list-frontend <br>
**Backend Code**: https://github.com/jordanchude/to-do-list-backend

For my Unit 2 project in bootcamp, I designed and developed a to-do list tracker for a company and its employees. The project was divided into two parts: the frontend and the backend.

The frontend consisted of a responsive navigation bar, a static header/jumbotron, a section that displays each employee's photo, name, and to-dos, and a footer with a copyright notice. Users could scroll down to view each added employee and their corresponding to-do list to stay updated on any changes. The form under the header/jumbotron enabled users to add an employee card with their name, title, and photo for the top of their to-do list. After creating the employee, a link on the employee card could be used to add a to-do item. Users could press an edit button on each created card to edit the name, photo, and title of the specified employee, or press a delete button on each created card to remove a card when an employee is terminated.

The backend consisted of a server and a database to hold employee and to-do list data. Functionality to add, remove, and update employee cards in the database, as well as to add and remove employee to-do lists in the database, was implemented. The backend server automatically updated and served data to match the user frontend. The app was deployed to Heroku.

The project was created using HTML, CSS, JavaScript, Bootstrap, jQuery, Express, Mongoose, Dotenv, Morgan, and Nodemon. Various user stories and Google Sheets were incorporated to ensure that the project met the needs of the target audience. Overall, this project was a great opportunity for me to create a functional and aesthetically pleasing web application while learning important new programming concepts, such as database design and server configuration.
