# Dummy Student API (JSON Server)

This project demonstrates how to create a simple dummy REST API using **Node.js** and **JSON Server**. It can be used for API testing, frontend development, and learning REST API concepts.

---

## Project Overview

A local dummy API was created using **JSON Server** and a `student.json` file. The API was tested in **Postman** by performing CRUD operations and validating the response status codes.

---

## Environment Setup

### 1. Install Node.js

Install **Node.js** from the official website:

[https://nodejs.org/](https://nodejs.org/)

Node.js automatically installs **npm (Node Package Manager)**, which is used to install project dependencies.

### 2. Install JSON Server

Run the following command in the terminal:

```bash
npm install -g json-server
```
### 3. Creat a json file as dataset like student.json

### 4. Start dummy server 
 Run the following command in the terminal:

 ```bash
json-server student.json
```
This will generate a endpoint like 

```bash
http://localhost:3000/students
```

## Request Performed
The following HTTP methods were tested in Postman:
- Get
- Post
- Put
- Delete
## Response Validation 
The API responses were validated in Postman using test scripts to verify that the expected HTTP status codes were returned for each request. Validate response for:
- Status Code
- Header
- Cookies
- Response time
- Response body

  Script is provided through 'API-testing/Dummy API.postman_collection.json'

## Tools Used
- Node.js
- Postman
- JSON server
- Github
