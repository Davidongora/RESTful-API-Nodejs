# RESTful-API-Nodejs
This project is a Node.js-based web application that uses the Express framework to create a RESTful API for managing users and shops. It interacts with a MySQL database to store and retrieve data.
Here's a description of the project components and functionality:

Node.js and Express: The project uses Node.js, a server-side JavaScript runtime, along with the Express framework, which simplifies the creation of web applications and APIs by providing routing, middleware, and other essential features.

MySQL Database: The application interacts with a MySQL database to store user and shop data. The database contains tables, such as "users" and "shops," where user and shop information is stored.

API Endpoints:

/routes: This endpoint is handled by the router and is related to administrative routes.
/users: This endpoint is used for retrieving all users.
/ById: This endpoint is used for getting users by ID and getting shops using the LIKE operator.
Controllers: The project uses controller functions to handle specific routes. Controllers encapsulate the business logic and database interactions for each route.

Route Parameters: Route parameters are used to pass dynamic values (such as user IDs and shop names) to the API endpoints, allowing you to perform specific actions based on the provided data.

Search Functionality: The application provides search functionality using the LIKE operator for retrieving shops based on a partial match of the shop name.

Error Handling: The project handles errors using try-catch blocks, and it returns appropriate error responses (with status codes and error messages) when necessary.

Environment Variables: The application uses the dotenv package to manage environment variables. Environment variables can be used to store sensitive information, such as database credentials, securely.
