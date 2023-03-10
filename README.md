#  Kikoba Micro Service Application
This is a Micro Service Application developed using Spring Boot framework. It provides microservices to perform various vikoba operations.

## Microservices
1. Account Service (port 8020)
   - The Account Service is responsible for maintaining records of all the different types of accounts offered by the bank. This information is stored in a database, which can be accessed by other microservices as needed.
   
2. Customer Service (port 8080)
   - The Customer Service is responsible for maintaining records of all the customers. This information includes customer details such as name, address, and contact information.
   
3. Loan Service (port 8030)
   - The Loan Service is responsible for maintaining records of all loan requests made by customers. This information includes details such as the amount of the loan and the customer's credit history.
   
4. Staff Service (port 8040)
   - The Staff Service is responsible for maintaining records of all the staff members. This information includes details such as the staff members' names, positions, and responsibilities.

5. Transaction Service (port 8050)
   - The Transaction Service is responsible for maintaining records of all transactions made by customers. This information includes details such as the date, amount, and type of transaction.


NOTE: All these Microservices have their own databases, which can be accessed y other microservices when needed

## Technology used for this project
- Spring Boot
- Java
- Microservices Architecture

## How to run the application
1. Clone the repository
2. Navigate to the project directory
3. Build the project
4. Run the application


## User Interface
The user interface for the bank microservices application is implemented using JSP (JavaServer Pages). JSP is a template engine that allows developers to create dynamic HTML pages using Java code.

## JSP Implementation
1. Required dependencies were added to the `pom.xml` file to use JSP with Spring Boot.
2. JSP files were created in the `src/main/webapp/views/.jsp` directory.
3. A Controller was implemented to map to the JSP files. This Controller uses the `@GetMapping` annotation to define a URL endpoint for the index page, which returns the `index.jsp` file.

## Database
All the microservices use the same database server (localhost), with the same username (root) and password ("").

## Dependencies
- tomcat-embed-jasper library
