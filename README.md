
# First Spring Boot Web Project - Vistula University

This is a foundational Spring Boot web application developed as part of a Java programming course at Vistula University. The application demonstrates the integration of a Spring Controller with the Thymeleaf template engine to render dynamic web pages.

## 🚀 Technologies
* **Java 21**: The core programming language.
* **Spring Boot 4.0.1 (SNAPSHOT)**: The framework used for rapid application development.
* **Thymeleaf**: Server-side Java template engine used to display the HTML content.
* **Maven**: Used for project build and dependency management.
* **Lombok**: Integrated to reduce boilerplate code.

## 🛠️ Setup and Installation

1.  **Clone the Repository**: Download or clone this project from GitHub.
2.  **Open in IDE**: Import the project into IntelliJ IDEA or any preferred Java IDE.
3.  **Install Dependencies**: Let Maven download the necessary libraries (Spring Web, Thymeleaf, etc.).
4.  **Run the Application**: Execute the `main` method in `FirstProjectJavaSpring1Application.java`.
5.  **Access the App**: Open your browser and navigate to: `http://localhost:8080/greeting`.

## 🔗 How It Works

The application currently listens on the `/greeting` endpoint:

* **Static Display**: It is configured to display "Hello Vistula" or "Hello World" depending on your `greetings.html` settings.
* **Dynamic Greeting**: Using the `name` parameter, you can customize the message:
    * Example: `http://localhost:8080/greeting?name=Novruz` will display **"Hello Vistula Novruz"**.

## 📂 Project Structure
* `HelloController.java`: Handles incoming web requests and prepares data for the view.
* `greetings.html`: The Thymeleaf template located in `src/main/resources/templates/`.
* `pom.xml`: Contains all project configurations and dependencies.

---
*Created for educational purposes at Vistula University.*
