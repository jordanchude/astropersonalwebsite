---
title: Anythink
publishDate: 2023-03-02 00:00:00
img: /assets/anythink.png
img_alt: A home page with a search box and "Anythink" company logo above it
description: |
  Anythink, a fictional product and organization created by Wilco, a web development practice platform, where I implemented a product search feature and effectively managed code repositories to enhance development skills in real-world development scenarios.
tags:
  - Design
  - Dev
---

Anythink Market is built with React, Node.js, MongoDB, and Elasticsearch. It has features like user authentication, product listing, image uploading, and search functionality. All contributions were organized in the forms of ['quests'](https://www.trywilco.com/catalog) from [Wilco](https://www.trywilco.com/). 

Here is a rundown of the quests I've done and their contributions to the Anythink codebase:

- **Gitting Started**: I set up the initial repository on GitHub and configured the .gitignore file. I also created a README.md file with instructions on how to run the project locally and deploy it to Heroku. 
  - **Pull Request**: https://github.com/ObelusFamily/Anythink-Market-9veys/pull/1/commits
- **Setup**: I installed all the dependencies for both the front-end and back-end using npm. I also created a .env file to store environment variables like database URL, API keys, and secret keys. 
  - **Pull Request**: https://github.com/ObelusFamily/Anythink-Market-9veys/pull/2/commits
- **Dataseeding**: I wrote a script to seed the database with dummy data using Faker.js. I created models for users, products, orders, and reviews using Mongoose schemas and validations. I also added indexes to improve query performance. 
  - **Pull Request**: https://github.com/ObelusFamily/Anythink-Market-9veys/pull/3/commits
- **Search Party**: I implemented a dynamic filtering system for the products in the Anythink Market project using React hooks and regex. I also fixed some bugs and improved the performance of the search algorithm. The regex matches partial or fuzzy titles and limits the query results to 1. The React hooks manage the state of the search value and the suggestions array. Depending on whether there are any suggestions or not, different content is displayed.
  - **Pull Requests**:
    - https://github.com/ObelusFamily/Anythink-Market-9veys/pull/4/commits
    - https://github.com/ObelusFamily/Anythink-Market-9veys/pull/5/commits
    - https://github.com/ObelusFamily/Anythink-Market-9veys/pull/6/commits
- **Let It Sink (current)**: I implemented a new verification program for top sellers based on a predefined list by adding a boolean field to the User model and API. 
  - **Pull Request**: https://github.com/ObelusFamily/Anythink-Market-9veys/pull/7
