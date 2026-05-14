# Spring Boot MVC Application

## About The Project

This project is a simple MVC application created using Spring Boot and Thymeleaf.

The application accepts a request from the browser and returns a web page with a greeting message.

---

## Use Case

### Greeting Page

The user opens the following URL in the browser:

```text
http://localhost:8080/greeting?name=Abhin
```

The application reads the `name` parameter and displays a greeting message on the HTML page.

Example output:

```text
Hello, Abhin!
```

---

## Screenshot

Example of greeting page:


<img width="1600" height="840" alt="WhatsApp Image 2026-05-14 at 6 12 59 PM" src="https://github.com/user-attachments/assets/985583c6-c214-4199-888a-7b1e1d543fbc" />



---

## Technologies

- Java
- Spring Boot
- Spring MVC
- Thymeleaf
- Maven

---

## Project Structure

- `controller` → handles requests
- `templates` → HTML pages
- `static` → images and static files
