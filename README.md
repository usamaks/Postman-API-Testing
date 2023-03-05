# Postman-API-Testing-Project

# API Testing with Postman CRUD with Local Dummy Server

This project is a sample of how to perform API testing using Postman with a local dummy server. The server is implemented using JSON Server, which allows us to create a mock REST API quickly.

In this project, we will perform CRUD (Create, Read, Update, and Delete) operations on a mock API for a simple user management system. We will use Postman to send requests to the API and verify the responses.

Requirements

You will need the following software installed on your machine:

- Postman
- Node.js

Getting Started

To get started, follow these steps:

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Install the project dependencies by running the following command:
   npm install
4. Start the local server by running the following command:
   npm run start
   This will start the server on http://localhost:3000.
5. Import the Postman collection from the postman directory into Postman.
6. In Postman, select the CRUD User Management System collection and click on the Runner button to open the collection runner.
7. Click on the Run button to run all the requests in the collection.

Collection Requests

The collection contains the following requests:

- Create User - Creates a new user in the system.
- Get Users - Retrieves a list of all the users in the system.
- Get User - Retrieves a single user by ID.
- Update User - Updates an existing user.
- Delete User - Deletes an existing user.

Each request has a set of pre-request and test scripts that handle the setup and validation of the request.

Conclusion

This project demonstrates how to perform API testing using Postman with a local dummy server. We created a mock REST API using JSON Server and performed CRUD operations on it using Postman. This sample project can be used as a starting point for testing APIs in your own projects.
