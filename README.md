# Shopify-E-Commerce Webpage

This project is a basic implementation of an e-commerce website, inspired by Shopify, and built using the Spring Boot framework. It showcases product listings, handles product management, and provides an embedded H2 database for quick testing.

## Key Features
- **Spring Boot**: Backend framework for rapid application development.
- **Spring Data JPA**: ORM to easily interact with the database.
- **H2 Database**: In-memory database for development and testing.
- **Lombok**: Reduces boilerplate code using annotations like `@Getter`, `@Setter`, etc.
- **Spring Boot DevTools**: Enables hot reloading, speeding up the development process.

## Tech Stack
- **Java 21**: Leveraging the latest features of Java.
- **Spring Boot 3.3.0**: Provides powerful support for building scalable applications.
- **Maven**: Dependency management and build tool.
- **Embedded H2 Database**: Used for development and testing; can be switched to MySQL or PostgreSQL for production.

## Project Structure
The project follows a standard Spring Boot layered architecture:
- **Controllers**: Handles incoming API requests.
- **Services**: Contains business logic.
- **Repositories**: Handles database operations.
- **Entities**: Represents data objects mapped to the database.

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/shopify-e-commerce-webpage.git
   cd shopify-e-commerce-webpage
   ```

2. **Build the project using Maven:**
   ```bash
   mvn clean install
   ```

3. **Run the project:**
   ```bash
   mvn spring-boot:run
   ```

4. **Access the application:**
   - Open your browser and go to `http://localhost:8080`.

## Sample Data
The application comes with pre-populated dummy product data to showcase functionality. You can view, add, update, and delete products through the API or user interface.

## Configuration
- **Database**: The project uses an embedded H2 database by default. The configuration can be found in `src/main/resources/application.properties`.
- **Switching to MySQL or PostgreSQL**: Update the properties file with your production database credentials.

## Error Handling
- Global exception handling is implemented using `@ControllerAdvice` to manage errors across the application in a clean and uniform way.
- Custom exceptions and error codes are defined for better readability and maintainability.

## Future Enhancements
- **User Authentication**: Integrate Spring Security for user roles and permissions.
- **Frontend Framework**: Plan to integrate a frontend using React, Angular, or Vue.js.
- **Payment Gateway Integration**: Add payment options using third-party services like Stripe or PayPal.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
