# Simple Mbanking RESTful API Website

## Introduction

Welcome to the Financial Tracking RESTful API website.

## RESTful Principles

The Financial Tracking API adheres to the principles of RESTful design to ensure a standardized and user-friendly experience:

1. **Resources**: The API treats financial entities such as transactions and accounts as resources, each accessible through a unique endpoint.

2. **HTTP Methods**: HTTP methods such as GET, POST, PUT, PATCH, and DELETE are employed to interact with these resources.

3. **Representation**: Data is exchanged in JSON format, allowing for structured and easy-to-parse information.

## Endpoints and Examples

[Copy me on postman](https://mnajmytsss.onrender.com)

### HTTP Methods

**Get all User**

```http
GET | https://mnajmytsss.onrender.com/user
```

**Get User by ID**

```http
GET | https://mnajmytsss.onrender.com/user/:id
```

**Post Transaction**

```http
POST | https://mnajmytsss.onrender.com/transaction
```

**Put transaction by ID**

```http
PUT | https://mnajmytsss.onrender.com/transaction/:id
```

**Delete Transaction by ID**

```http
DELETE | https://mnajmytsss.onrender.com/transaction/:id
```