# First Spring Boot MVC Project

## About the Project

This is a simple Spring Boot web application created to understand the basics of the MVC (Model–View–Controller) architecture in Java.

The project shows how a controller can receive a request from the browser, send data to a view, and display it using a web page.

## How It Works

1. The application starts using Spring Boot.
2. A user opens a URL in the browser.
3. The controller handles the request.
4. The controller sends data (name parameter) to the view.
5. The view (`greeting.html`) displays a greeting message and an image.

Example URL:

```
http://localhost:8080/greeting?name=John
```

The page will display:

```
Hello, John!
```

## Technologies Used

* Java
* Spring Boot
* Spring MVC
* Thymeleaf
* Maven

## Project Structure

* `controller` – handles HTTP requests
* `templates` – HTML pages (views)
* `static/images` – static resources like images


