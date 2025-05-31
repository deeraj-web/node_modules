Book API – Simple Node.js Express REST API
This is a simple REST API built using Node.js and Express to manage a collection of books in memory. It supports basic CRUD (Create, Read, Update, Delete) operations. No database is used — data is stored in memory and will reset when the server restarts.

Tools Used
Node.js
Express.js
Postman (for testing)
How to Run
Initialize a new Node.js project: open terminal in vs code and run the following command to download dependencies and modules!!! npm init -y npm install express

Run the server: node app.js

API Endpoints
Method	Endpoint	Description
GET	/books	Get all books
GET	/books/:id	Get a single book by ID
POST	/books	Add a new book
PUT	/books/:id	Update an existing book
DELETE	/books/:id	Delete a book by ID
