# Node API Postgres

A simple CRUD Express.js RESTful API that connects to and queries a PostgresSQL database.

## Features

- No frontend, purely an exercise to set up the skeleton of a full stack application.
- Accepts GET, PUT, DELETE and POST calls allowing you to query, update, delete and create new users.

## Getting Started

To use this application, you will need to first create a Postgres database on locally with some initial user data.

Follow the instructions on [this tutorial by LogRocket](https://blog.logrocket.com/crud-rest-api-node-js-express-postgresql/) regarding initial set up of the Postgres database. 

After making the database and running it as a non-superuser, clone this project and in the root directory install required dependancies:

```bash
npm install
```

Now run the development server (index.js) at project root.

```bash
node index.js
```

Then using [Postman](https://www.postman.com/downloads/) or similar, you can make the following kind of queries (see queries.js for full features), E.G:

http://localhost:3000/users (GET) - Query all users
http://localhost:3000/users (POST) - Create a new user with raw JSON with name and email fields

See the queries.js file for full details of the API functionality.