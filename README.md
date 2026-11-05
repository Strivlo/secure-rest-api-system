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

## Running Locally

Clone the repository:

```
git clone https://github.com/Strivlo/secure-rest-api-system
```

Install dependencies:

```
npm install
```

Start the development server

```
npm start
```

The application will run at

```
http://localhost:8000
```

## API Testing

Endpoints can be tested using Postman or any REST client.

| Method | Route | Auth |
| --- | --- | --- |
| POST | `/auth/register` | None |
| POST | `/auth/login` | None (sets the session cookie) |
| GET | `/users` | Logged in |
| PATCH | `/users/:id` | Logged in, own account only |
| DELETE | `/users/:id` | Logged in, own account only |


## Author

Rekan

Computer Science Student

Founder of Strivlo
