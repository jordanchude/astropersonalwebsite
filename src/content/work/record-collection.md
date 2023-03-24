---
title: Record Collection
publishDate: 2021-12-01 00:00:00
img: /assets/record-collection.jpg
img_alt: A horizontally stacked record collection
description: |
  A full CRUD record collection app that allows users to manage artists and records using Node.js and MongoDB, built entirely with a community on Twitch.
tags:
  - Dev
  - Backend
---

**Code**: https://github.com/jordanchude/record-collection

Record Collection is a full CRUD record collection application, created using JavaScript (Node.js) and MongoDB. As a dedicated developer and avid music enthusiast, I built this project live on my Twitch channel, fostering a creative and collaborative environment with my viewers.

The core functionality of this application allows users to manage a collection of artists (including their names, birthdays, photos, and records) and their corresponding records (specifying each record's artist, name, release date, and link). By leveraging Postman, users can perform Create, Read, Update, and Delete operations on both artists and records. Furthermore, a many-to-many relationship is established between artists and records to enable smooth data management.

To provide an overview of the project structure, the MVP comprises a series of components, including server configuration, schema and model definition for artists and records, route handlers, endpoint testing, and debugging. Throughout the development process, I encountered and resolved various issues, including a buffering timeout error in Postman. This issue taught me a valuable lesson about the importance of examining external factors, such as MongoDB settings, in addition to scrutinizing the code itself.

While the project's minimum viable product (MVP) focuses on CRUD operations and data relationships, my plans for future enhancements include designing a mock-up user interface, implementing additional security features, and creating an interactive front-end for database management. If you are interested in building upon this project, please note that you will need to connect to your own MongoDB database, as only my IP address and login credentials grant access to my specific data.