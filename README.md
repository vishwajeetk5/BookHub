# BookHub

BookHub is a comprehensive bookstore management system designed to streamline the operations of a bookstore, both online and offline. The application allows bookstore owners to manage inventory, track sales.

## Tech Stack

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate**
- **Thymeleaf**
- **MySQL**
- **Maven**

## Features

- **Inventory Management:** Add, update, delete, and search for books.
- **Sales Tracking:** Record transactions, generate reports, and analyze trends.
- **User Authentication:** Secure authentication and authorization using Spring Security.
- **Dynamic Web Pages:** Rendered with Thymeleaf for a seamless user experience.

## Installation and Setup

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Apache Maven
- MySQL

### Steps to Install and Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/BookHub.git
    cd BookHub
    ```

2. **Configure the database:**
   - Create a MySQL database named `bookhub`.
   - Update the `application.properties` file with your MySQL username and password.
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/bookhub
    spring.datasource.username=yourusername
    spring.datasource.password=yourpassword
    ```

3. **Build the project:**
    ```bash
    mvn clean install
    ```

4. **Run the application:**
    ```bash
    mvn spring-boot:run
    ```

5. **Access the application:**
    Open your browser and go to `http://localhost:1001`.
### Screenshots
![image](https://github.com/user-attachments/assets/430f568f-a0d8-48b9-926a-0e6166dff5ad)
![image](https://github.com/user-attachments/assets/bf58389d-3125-4330-b475-ebfb0148c399)
![image](https://github.com/user-attachments/assets/0023006c-08cb-4278-9a40-2f341e09c5a8)
![image](https://github.com/user-attachments/assets/d00df2e7-6fde-4748-a5e6-7870721a6267)

## Usage

- **Add Books:** Navigate to the inventory section to add new books.
- **Update Books:** Select a book from the inventory to update its details.
- **Delete Books:** Remove books from the inventory.
- **Search Books:** Use the search functionality to find specific books.
- **Record Sales:** Navigate to the sales section to record transactions.
- **Generate Reports:** Generate sales reports for analysis.
