# Customer CRUD Application

This project is a Spring Boot REST API for managing customers using CRUD operations.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/customers` | Get all customers |
| GET | `/customers/{id}` | Get a customer by ID |
| POST | `/customers` | Create a new customer |
| PUT | `/customers/{id}` | Update a customer |
| DELETE | `/customers/{id}` | Delete a customer |


## Database

This project uses an H2 in-memory database for storing customer data.

The database is configured using Spring Data JPA and Hibernate.

H2 Console:

`http://localhost:8080/h2-console`


## CRUD Operations

The application supports the following customer operations:

- Create a new customer using POST.
- Retrieve all customers using GET.
- Retrieve a customer by ID using GET.
- Update an existing customer using PUT.
- Delete a customer using DELETE.
## Project Structure

- `Customer.java` - Customer entity
- `CustomerRepository.java` - Database repository
- `CustomerService.java` - Business logic
- `CustomerController.java` - REST API endpoints
- `application.properties` - Application and database configuration 

## Screenshots

### GET - Retrieve Customers
![GET](doc/GET.png.png)

### POST - Create Customer
![POST](doc/POST.png.png)

### PUT - Update Customer
![PUT](doc/PUT.png.png)

### DELETE - Delete Customer
![DELETE](doc/DELETE.png.png)

### H2 Database Query
![H2 Database](doc/H2-Database.png.png)
