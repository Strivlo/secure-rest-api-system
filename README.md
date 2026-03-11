## Secure REST API System

A REST API built using Node.js, Express, and TypeScript with user authentication and MongoDB integration.

This project demonstrates how to structure a backend API using controllers, routing, middleware, and database interaction while following common backend development patterns.


## Key Features

• RESTful API architecture

• User authentication (register & login)

• Middleware-based request handling

• Modular backend structure

• MongoDB database integration

• API testing using Postman


## Tech Stack

Node.js
Express.js
TypeScript
MongoDB
Mongoose
Postman


## Project Structure

```
src
├── controllers
│   ├── authentication.ts
│   └── users.ts
├── db
│   └── users.ts
├── helpers
│   └── index.ts
├── middlewares
│   └── index.ts
├── router
│   ├── authentication.ts
│   ├── index.ts
│   └── users.ts
└── index.ts
```

## Project Context

Strivlo Studio was developed as part of a portfolio project exploring AI-assisted development tools and modern full-stack application architecture.

The project demonstrates the integration of modern web technologies with AI-driven workflows to simulate an intelligent development environment.


## Running Locally

Clone the repository:

git clone https://github.com/Strivlo/secure-rest-api-system

Install dependencies:

```
npm install
```

Start the development server

```
npm run dev
```

The application will run at

```
[http://localhost:3000](http://localhost:8000/)
```

## API Testing

Endpoints can be tested using Postman or any REST client.

Example request:

GET http://localhost:3000/users


## Author

Rekan

Computer Science Student

Founder of Strivlo
