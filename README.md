TASK 1
## Project Description
The application demonstrates basic Spring Boot setup, controller handling, and using a Thymeleaf template.



## 🛠 Technologies Used
- Java 17/21
- Spring Boot
- Spring Web (MVC)
- Thymeleaf
- Lombok
- Maven



## Features
- Basic `@Controller` with `@GetMapping`
- Usage of `@ResponseBody`
- Dynamic data passing using `Model`
- Thymeleaf template with static resources (images)





## Project Structure Highlights
- `src/main/java/.../controller/HelloController.java`
- `src/main/resources/templates/greeting.html`
- `src/main/resources/static/images/vistula.png`


## How it works
The application defines a controller class:

HelloController

It provides two endpoints

1 Root Endpoint (/) . URL:http://loclhost:8080/

. Return a plain text response

2 Greeting Endpoint ( /greeting)

. URL:http://localhost:8080/greeting?name = Vistula

. Accepts a query parameter: name

. Passes the value to a view (HTML template)

## How to Run

1. Open the project in IntelliJ IDEA
2. Run the main class: `FirstProjectJavaSpringApplication`
3. Open the browser and paste this URL
   - `http://localhost:8080`- Response in Plain text
   - `http://localhost:8080/greeting`- greeting on a Thymeleaf page
   - `http://localhost:8080/greeting?name=Vistula`- Personalized greeting with Thymeleaf Page



## Project Structure
- `src/main/java/.../controller/HelloController.java`
- `src/main/resources/templates/greeting.html`
- `src/main/resources/static/images/vistula.png`



## Screenshots of the Pages

<img width="562" height="570" alt="image" src="https://github.com/user-attachments/assets/bc9dca08-ed4f-480d-84e7-3fd691ef0388" />
<img width="562" height="570" alt="image" src="https://github.com/user-attachments/assets/ba815d50-373c-46a8-93db-c49b1a17bca0" />
<img width="562" height="570" alt="image" src="https://github.com/user-attachments/assets/e699a975-04a0-4601-8cd7-546edcb071f4" />
