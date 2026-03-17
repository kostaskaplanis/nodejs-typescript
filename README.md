# Node.js TypeScript Todo API

This project is a small REST API built with Node.js, Express, and TypeScript.

In this project, I practiced:

- setting up an Express server with TypeScript
- organizing code into `app`, `routes`, and `models`
- creating a simple `Todo` interface
- handling JSON request bodies with `body-parser`
- building basic todo API routes for creating, reading, updating, and deleting todos

The app currently stores todos in memory, so the data resets whenever the server restarts.

## Available Routes

- `GET /` - get all todos
- `POST /todo` - create a new todo
- `PUT /todo/:todoId` - update an existing todo
- `DELETE /todo/:todoId` - delete a todo

## Run the Project

Start the compiled app with:

```bash
npm start
```
