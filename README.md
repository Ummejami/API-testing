# API testing with Public API, Authinticated API and Local API 
---
Here's i worked with API testing request,response validation,environment set up,api chaining methodology,assertion,field validation,file upload with three type of API 
- Local API (Dummy Students API)
- Authenticated API (Simple Book Store)
- Public API (Go_rest API)
---
## 1. Dummy Student API (JSON Server)

This project demonstrates how to create a simple dummy REST API using **Node.js** and **JSON Server**. It can be used for API testing, frontend development, and learning REST API concepts.

---

## Overview

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
  ---
  Response Body validation required two type schema conversion . One for old version which used keyword **tv4** and one for new version which required **jsonschema**. Json to schema conversion site
  ```bash
  https://www.liquid-technologies.com/online-json-to-schema-converter
  ```

 ---



# 2. 📚 Book Store API Testing (Simple Book Store API)

## 📌 Project Overview
This project demonstrates end-to-end API testing of a Book Store system using the Simple Books API. It covers authentication, book retrieval, order management, API chaining, and automation using Postman.
Documentation is available here.
``` bash
https://share.google/clnJvpt786PwDN5Os
```
---

## 🌐 API Used
```bash
https://simple-books-api.glitch.me/
```
---

## 🎯 Objectives
- Perform API testing on a book ordering system  
- Validate request and response data  
- Implement API chaining using environment variables  
- Automate API execution using Newman  
- Integrate API tests with Jenkins  

---

## 🔐 Authentication
The API requires authentication for order-related endpoints.

### Generate Token:
- Send POST request to `/api-clients/`
- Store token in environment variable  
---
# 3. Go_rest API
## 📌 Overview
This project demonstrates end-to-end API testing of a User Management system using the GoRest public API. It covers authentication, CRUD operations, API chaining, validation, and automation.
##  🌐 API Used
```bash
https://gorest.co.in/
```
## 🎯Objectives
-Perform CRUD operations on user resources
-Implement Bearer Token authentication
-Validate API responses (status codes, body, schema)
-Perform API chaining using environment variables
## Tools Used
- Node.js
- Postman
- JSON server
- Github
## Summary
What I have done here?
- Dummy API creation
- Performed HTTP requests
- Validated the responses:
  - Checked status codes for different HTTP methods
  - Verified response data types such as object, array, string, and number
  - Validated specific response fields like `id`, `name`, `location`, `phone`, and `courses`
  - Confirmed required properties exist in the response body
  - Performed JSON schema validation
  - Checked response time
  - Verified header,cookies
- API chaining
