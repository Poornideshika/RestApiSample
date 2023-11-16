
# REST API CRUD Example with Node.js, Express, Sequelize, and MySQL

This project demonstrates a simple RESTful API using Node.js and Express for performing CRUD (Create, Read, Update, Delete) operations on a MySQL database. Sequelize is used as an ORM (Object-Relational Mapping) tool for managing the database models.

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Set up the environment variables:
   - Add the necessary environment variables (such as database credentials) in the `.env` file:

     ```
     DB_USERNAME=your_database_username
     DB_PASSWORD=your_database_password
     DB_DATABASE=your_database_name
     DB_HOST=your_database_host
     ```

4. Run the application:

   ```
   node src/index.js
   ```

## Dependencies

- `dotenv`: Library for loading environment variables from a `.env` file into `process.env`.
- `express`: Web application framework for Node.js.
- `mysql2`: MySQL client for Node.js.
- `sequelize`: Promise-based ORM for Node.js.
- `swagger-ui-express`: Middleware for serving Swagger UI documentation generated from Swagger/OpenAPI specifications.

## Usage

The API endpoints can be accessed as follows:

- **GET `/api/resource`**: Retrieve all resources.
- **GET `/api/resource/:id`**: Retrieve a specific resource by ID.
- **POST `/api/resource`**: Create a new resource.
- **PUT `/api/resource/:id`**: Update a resource by ID.
- **PATCH `/api/resource/:id`**: Partially update a resource by ID.
- **DELETE `/api/resource/:id`**: Delete a resource by ID.

## API Documentation

API documentation can be accessed using Swagger UI. After starting the application, visit `[/api-docs](http://localhost:3000/api-docs)` in your browser to view and interact with the API documentation.

## Contributing

Feel free to contribute by opening issues or submitting pull requests.

---
