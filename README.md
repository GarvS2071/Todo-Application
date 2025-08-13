# TODO-APPLICATION
A simple and neat **Todo Application** which is built using:
1. SpringBoot
2. JPA(Hibernate) + MySQL
3. Lombok
4. Thymeleaf + Bootstrap CSS

This application allows user to:
* Add new tasks
* Mark the tasks as completed (toggle functionality)
* Delete the tasks

<img width="1864" height="878" alt="image" src="https://github.com/user-attachments/assets/1843a34e-5009-4a41-8eaf-99cd1a746972" />

## FEATURES 🚀
* **ADD TASKS:** Enter a new task that you wish to complete in the input field and click on "Add" to save it to the database.
* **TOGGLE COMPLETION:** Click on the "Toggle" button to label the task as completed.
* **DELETE TASKS:** Click on the "Delete" button to remove any task permanently from the database.
* **RESPONSIVE UI:** Styled with **Bootstrap CSS** for a clean & interactive design.

## TECH STACK 🛠
**Backend:**
* Spring Boot (Java)
* Spring MVC
* Spring Data JPA (Hibernate)
* Lombok

**Frontend:**
* Thymeleaf
* Bootstrap CSS

**Database:**
* MySQL

## PROJECT STRUCTURE 📁
* main/
    * java/com/app/todo/
        - controller/      Handles HTTP requests
        - model/           Tasks entity
        - repository/      JPA repository for CRUD (Created, Read, Update & Delete)
        - service/         Business logic
    * resources/
        - templates/       Thymeleaf HTML templates
        - static/          CSS, JS, images
        - application.properties   Configuration

## INSTALLATION & SETUP ⚙
1. #### Clone The Repository
```
git clone https://github.com/GarvS2071/todo-application.git
cd todo-application
```
2. #### Configure MySQL Database

Edit the `application.properties` file:
```
spring.datasource.url=jdbc:mysql://localhost:3306/todo_db
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```
3. #### Build & Run
```
mvn spring-boot:run
```
4. #### Access the Application

Open a browser & go to:
```
http://localhost:8080
```

## USAGE 📌
1. Type a task in the input field and click **Add**.
2. Click on the **Toggle** button to toggle completion status.
3. Click the **Delete** button to remove the task.
