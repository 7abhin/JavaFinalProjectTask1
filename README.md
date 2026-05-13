# Spring Boot MVC Application

## Project Introduction

This project is a basic Spring Boot MVC application developed for learning how Spring controllers and views work together.

The application receives requests from the browser and returns a web page using Thymeleaf templates.

---

## Application Flow

- User opens the application in browser
- Spring controller handles the request
- Data is passed from controller to HTML page
- Thymeleaf displays the result on the screen

Example URL:

```text
http://localhost:8080/greeting?name=Alex
```

Example Output:

```text
Hello, Alex!
```

---

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Thymeleaf
- Maven

---

## Project Packages

- `controller` → handles browser requests
- `templates` → contains HTML files
- `static` → stores images and static resources

---

## Running the Project

1. Open project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run the main application class
4. Open browser on:

```text
http://localhost:8080
```
