# 🚀 Avinya 3.0

**Avinya 3.0** is a Java-based web application developed using the Spring Boot framework. This project serves as a foundational template for building scalable and maintainable web applications, incorporating best practices and standard conventions.

---

## 📁 Project Structure

```
Avinya-3.0/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── avinya/
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               ├── repository/
│   │   │               └── service/
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── avinya/
├── target/
├── .gitignore
├── HELP.md
├── mvnw
├── mvnw.cmd
└── pom.xml
```

- **`src/main/java`**: Contains the main application code organized into packages:
  - `controller`: Handles HTTP requests and responses.
  - `model`: Defines the data models or entities.
  - `repository`: Interfaces for database operations.
  - `service`: Contains business logic.

- **`src/main/resources`**:
  - `static`: Static assets like CSS, JS, and images.
  - `templates`: Thymeleaf templates for rendering views.
  - `application.properties`: Configuration properties for the application.

- **`src/test/java`**: Contains unit and integration tests.

- **`target/`**: Compiled bytecode and packaged application files.

- **`pom.xml`**: Maven configuration file managing project dependencies and build lifecycle.

---

## 🛠️ Technologies Used

- **Java 17**: Core programming language.
- **Spring Boot**: Framework for building web applications.
- **Maven**: Build automation and dependency management.
- **Thymeleaf**: Server-side Java template engine for web and standalone environments.
- **Spring Data JPA**: Simplifies data access layers.
- **H2 Database**: In-memory database for development and testing.

---

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- Maven 3.6 or higher

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Meghraj2004/Avinya-3.0.git
   cd Avinya-3.0
   ```

2. **Build the project using Maven**:
   ```bash
   ./mvnw clean install
   ```

3. **Run the application**:
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Access the application**:
   Open your browser and navigate to `http://localhost:8080`

---

## ⚙️ Configuration

The application uses `application.properties` for configuration. You can set various properties like server port, database configurations, etc.

Example:
```properties
server.port=8080
spring.datasource.url=jdbc:h2:mem:avinya
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
```

---

## 🧪 Running Tests

To run the tests, execute:

```bash
./mvnw test
```

This will run all unit and integration tests located in the `src/test/java` directory.

---

## 📄 Documentation

- **HELP.md**: Contains helpful information about the project setup and usage.
- **Javadoc**: Generate Javadoc by running:
  ```bash
  ./mvnw javadoc:javadoc
  ```
  The documentation will be available in `target/site/apidocs/index.html`.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

For any inquiries, feedback, or collaboration opportunities:

- 👨‍💻 **GitHub**: [Meghraj2004](https://github.com/Meghraj2004)
- 📧 **Email**: megharajdandgavhal2004@gmail.com
- 📱 **Phone**: +91 9421612110
- 📷 **Instagram**: [@megharaj_2004](https://www.instagram.com/megharaj_2004)
- 💼 **LinkedIn**: [Megharaj Dandgavhal](https://www.linkedin.com/in/megharajdandgavhal)

---
