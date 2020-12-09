---
permalink: /architecture/
title: "System Architecture"
---

## API service

### MongoDB
[Mongodb](https://www.mongodb.com/) is a general purpose, document-based, NoSQL, distributed database built for modern application developers.  
Utilizing a MongoDB Atlas free-tire cluster in our production environment.  
MongoDB Atlas is multi-cloud database service that automatically manages our database.

### Python-Flask 
[Python-Flask](https://flask.palletsprojects.com/en/1.1.x/) is a web application framework that handles API requests, processes those requests by fetching data from the database or modifying data in the database, then returns a response to the caller of the API request.

### JSON Web Tokens
[JSON Web Tokens](https://jwt.io/) are an open, industry standard method for representing claims securely between two parties. We are using JWT's for user authorization. e.g. when an admin logs into the application, their browser receives a JWT and uses it on subsequent API calls that require authorization. 

## Frontend Service

### React Native on Typescript
[React Native](https://reactnative.dev/) is an open-source mobile application framework for building user interfaces

### React Native Paper

### Redux
