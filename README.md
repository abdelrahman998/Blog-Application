# Blog Application

This is a Spring Boot application for a blogging platform. It provides RESTful APIs for managing blog posts, user authentication, and authorization.

## Technologies Used

- Java
- Spring Boot
- Spring Security
- Hibernate
- MySQL
- Maven

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- MySQL

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/abdelrahman998/spring-boot-blog.git
    cd spring-boot-blog
    ```

2. Configure the MySQL database:
    - Create a database named `blog`.
    - Update the database configuration in `src/main/resources/application.properties`:
        ```ini
        spring.datasource.url=jdbc:mysql://localhost:3306/blog?useSSL=false&serverTimezone=UTC
        spring.datasource.username=your_username_here
        spring.datasource.password=your_password_here
        ```

3. Build the project:
    ```sh
    mvn clean install
    ```

4. Run the application:
    ```sh
    mvn spring-boot:run
    ```


## Security

This application uses JWT for authentication and authorization.
