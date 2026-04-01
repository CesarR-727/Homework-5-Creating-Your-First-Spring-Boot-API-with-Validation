Campus TaskBoard API

Description: A Restful API with Spring Boot that allows users to manage tasks. The API supports creating, reading, updating and deleting tasks with input validation.

How to run the application?

To run this application you will need Java 17 or higher installed on your computer. 

Once you have Java installed, clone this repository to your computer and open the project folder in VS Code or any IDE of your choice.

To start the application, open the terminal inside the project folder and run the following command:

On Mac or Linux:
cd campus-taskboard./mvnw spring-boot:run

On Windows:
mvnw.cmd spring-boot:run

Wait for the application to start. When you see the message "Started CampusTaskboardApplication" in the terminal, the server is running successfully.

You can now open your browser and go to http://localhost:8080 to see the API working. You should see an empty array [] if no tasks have been created yet.

To test all the endpoints you can use Postman or any API testing tool of your choice.

API endpoints documentation

Application starting successfully (console output)
<img width="1090" height="22" alt="Screenshot 2026-03-26 at 7 17 31 PM" src="https://github.com/user-attachments/assets/7ee1b153-e3cc-473e-bd4d-dd43ddfdd2f0" />

GET /api/tasks endpoint working (Postman or browser)
<img width="842" height="159" alt="Screenshot 2026-03-30 at 2 01 12 PM" src="https://github.com/user-attachments/assets/3591182b-0f5c-4422-8511-e5e1d5de4dc8" />
<img width="842" height="159" alt="Screenshot 2026-03-30 at 2 01 12 PM" src="https://github.com/user-attachments/assets/77c61fb7-5e4f-4977-907b-ecafffdf6e75" />


POST /api/tasks creating a task 
![preview](https://github.com/user-attachments/assets/e84852c3-8c84-442a-864e-fed22fa55d97)

GET /api/tasks/{id} retrieving a task
![Screebshot](https://github.com/user-attachments/assets/eb236237-85af-45cb-ba52-38d359273d3b)

PUT /api/tasks/{id} updating a task
![Screenshot copy](https://github.com/user-attachments/assets/c17b0ab2-acce-4b73-a604-003fb6c84439)

DELETE /api/tasks/{id} deleting a task
![Screenshot copy 2](https://github.com/user-attachments/assets/1550b313-08c2-4444-8593-b1d8af4cfa84)

Validation error example (show invalid request and error response)
<img width="1267" height="601" alt="Screenshot 2026-03-30 at 2 51 33 PM" src="https://github.com/user-attachments/assets/f56c4582-c469-4bb7-b7f2-ca8931bd55b4" />

At least 2-3 tasks created and displayed
<img width="1267" height="496" alt="Screenshot 2026-03-31 at 4 13 10 PM" src="https://github.com/user-attachments/assets/90b07648-aa94-4ec7-825c-8f746068ca94" />

Video Link
https://youtu.be/Y9Qv9jL0VNQ



