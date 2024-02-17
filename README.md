# Rest API project

This is a repository for a REST API using Node, Express, Typescript & MongoDB.

Features:

- Environment, Typescript, Nodemon setup
- MongoDB & Mongoose connect, Database creation
- Controllers creation
- Middlewares creation
- Cookie based authentication
- Postman testing
- Create, Read, Update

### Prerequisites

**Node version 14.x**

# API for postman

http://localhost:8080/auth/register =>  {
                                            "email": "two@gmail.com",
                                            "password": "--",
                                            "username": "two"
                                        }

http://localhost:8080/auth/login    =>  {
                                            "email": "two@gmail.com",
                                            "password": "--"
                                        }

http://localhost:8080/users

http://localhost:8080/users/:id => {
                                        "username": "two"
                                    }, request type : "PATCH

http://localhost:8080/users/:id 