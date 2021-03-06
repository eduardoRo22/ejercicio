Books API
Assumptions
This document assumes that you are familiar with the Mule ESB and Anypoint Studio. To run this project you'll need Maven and Anypoint Studio installed.

Use Case
This API allows you to manage a simple book catalog.

Available Operations
List all books.
Create a new book.
Update an existing book (using its id).
Delete an existing book (using its id).
Find a book by title.
Running the project
To run this project on Anypoint studio you will need to import the project from file/import on the pop up select Anypoint Studio folder and click Maven-based Mule project from pom.xml. On the application select the Global Elements tab, double-click the HTTP Listener global element and change port field to a desired HTTP port such as 8081.

On the package explorer pane, right click on the project folder and click Run as / Mule Application with Maven. Anypoint Studio starts the application and automatically opens an API console below the canvas. You can interact with the application exploring the resources and operations described on the console and try them. Also you can interact with the API following the guidelines provided on the RAML definition and the JSON examples available on src/main/resources using an external application. Eg. Postman.

RAML Definition
Open the RAML file in the src/main/resources folder to review the details of the API. All the resources referenced by !includes also reside in your src/main/resources folder. You can also check the interactive documentation available on the API console tab inside studio or check the following url: 0.0.0.0:8081/booksapi/console.
