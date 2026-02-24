# GoPass!
GoPass is a travel booking system developed as part of a Database Management Systems course. The project focuses on relational database design, SQL queries, constraints, normalization, and data integrity. The frontend and backend are designed to support database operations, with the primary focus on SQL and data modeling.

🚀 Tech Stack

Backend:

Java (JDBC)
RESTful service structure  /
Layered architecture (Controller – Service – DAO)  /
Input validation & exception handling  /
Spring Boot  /
Spring Data JPA  /
Maven  /
Relational Database System  /
Architecture

Database:

PostgreSQL/
Relational schema design/
Normalization (up to 3NF)/
Primary & Foreign Keys/
Unique & Check Constraints/
NOT NULL constraints/
Indexing for performance optimization/
Transaction management/
Complex SQL queries (JOIN, GROUP BY, aggregate functions, subqueries)


The project follows a layered architecture approach:

src ├── controller ├── service ├── repository ├── entity └── config

Application layers are separated to improve maintainability and scalability.

Frontend:

HTML5/
CSS3/
JavaScript (Vanilla JS)/
Form validation & dynamic DOM manipulation

✨ Features

-User registration & login
-Trip listing & filtering
-Reservation creation
-Booking history tracking
-Admin-side data management
-Transaction-safe booking operations


Navigate to the project directory:

cd GoPass

Run the application:

mvn spring-boot:run

The application runs on:

http://localhost:8080
