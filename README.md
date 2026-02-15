# Quarkus API Project Documentation

## Overview
This project implements a RESTful API using the Quarkus framework, known for its fast startup time and low memory usage.

## REST Endpoints

### 1. GET /api/items
- **Description**: Retrieves a list of items.
- **Response**: Returns a JSON array of items.

### 2. GET /api/items/{id}
- **Description**: Retrieves details of a specific item by ID.
- **Response**: Returns a JSON object representing the item.

### 3. POST /api/items
- **Description**: Adds a new item to the list.
- **Request Body**: JSON object representing the item.
- **Response**: Returns the created item with its ID.

### 4. PUT /api/items/{id}
- **Description**: Updates an existing item by ID.
- **Request Body**: JSON object representing the updated item.
- **Response**: Returns the updated item.

### 5. DELETE /api/items/{id}
- **Description**: Deletes an item by ID.
- **Response**: Returns an acknowledgment of deletion.

## Quarkus Framework Features
- **Fast Startup**: Quarkus has optimized startup times for Java applications.
- **Native Compilation**: Quarkus can compile your application into a native binary via GraalVM, significantly reducing memory consumption.
- **Developer Experience**: Features such as live reload, and zero configuration to enhance developer productivity.
- **Extensive Extensions**: Offers a wide range of extensions for various integrations and functionalities.

## Installation Instructions
1. **Prerequisites**: Ensure you have Java 11+ installed, along with Maven.
2. **Clone the repository**:
   ```bash
   git clone https://github.com/yorrisonsouza/api-quarkus.git
   cd api-quarkus
   ```
3. **Build the project**:
   ```bash
   ./mvnw package
   ```
4. **Run the application**:
   ```bash
   ./mvnw quarkus:dev
   ```

## Development Guidelines
- Use descriptive commit messages to enhance the history.
- Follow the RESTful conventions in naming endpoints.
- Ensure unit tests accompany new features or changes.
- Regularly synchronize with the main branch to avoid merge conflicts.

## Conclusion
This documentation provides a foundational understanding of the API's structure and the capabilities of the Quarkus framework. For detailed inquiries, refer to the official [Quarkus documentation](https://quarkus.io/guides/).