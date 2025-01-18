# FirstRestAPI

## Project Description

A REST API application created using Spring Boot. 
The application allows creating, updating, deleting, 
and retrieving product data, while ensuring appropriate error handling 
and API documentation.

### Creating a New Product

The user sends a POST request with product data in JSON format (e.g., `{"name": "Product1"}`) to the `/api/v1/products` endpoint.

### Retrieving Product Details

The user sends a GET request to the `/api/v1/products/{id}` endpoint, where `{id}` is the product identifier.

### Updating a Product

The user sends a PUT request with updated product data (e.g., `{"name": "Product1Updated"}`) to the `/api/v1/products/{id}` endpoint.

### Deleting a Product

The user sends a DELETE request to the `/api/v1/products/{id}` endpoint.

### Retrieving All Products

The user sends a GET request to the `/api/v1/products` endpoint.

## Exception Handling

- **Class `ProductNotFoundException`**: For handling exceptions related to the absence of a product.
- **Class `ProductExceptionSupplier`**: Supporting exception handling.
- **Class `ErrorMessageResponse`**: For storing error messages.

## Case Study

### Application Workflow

1. **Creating a New Product**: Sending a POST request with product data.
2. **Retrieving Product Details**: Sending a GET request with the product identifier.
3. **Updating a Product**: Sending a PUT request with updated product data.
4. **Deleting a Product**: Sending a DELETE request with the product identifier.
5. **Retrieving All Products**: Sending a GET request to obtain a list of products.

The application ensures proper error handling and API documentation using Swagger UI. All data is stored in the H2 Database.

---

### Author
Adrian Grabowski
