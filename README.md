# Task3 
RESTful Book Management API using Node.js & Express
 Tech Stack: Node.js, Express.js, Postman
Type: Backend API (In-Memory Storage, No Database)
Hosted On: Localhost (for development/testing)

Project Overview:
I built a simple REST API for managing a list of books using Node.js and Express. This backend application allows you to perform full CRUD operations — Create, Read, Update, Delete — on a list of books stored in memory.

This project was developed entirely in Visual Studio Code and tested using Postman to simulate real-world API requests.

 Key Features:
 GET /books — Fetch all books in the collection.

 POST /books — Add a new book with title and author.

 PUT /books/:id — Update a specific book by its ID.

 DELETE /books/:id — Remove a book from the list by ID.

 How It Works:
Used Express to set up a server on port 3000.

Created an in-memory array to store books ({id, title, author}).

Built each endpoint to handle proper validation and return meaningful responses.

No external database was used — all data is stored temporarily in runtime memory.

Middleware: Used express.json() to parse incoming JSON data.

 Tested With Postman:
All endpoints were thoroughly tested using Postman to ensure correct request and response handling.

 Goal:
To strengthen my backend development skills and gain hands-on experience with API development, routing, and request handling using Node.js and Express.

 Next Steps (Future Scope):
Add persistent storage using MongoDB or MySQL.

Implement authentication using JWT.

Create a simple frontend using React for users to interact with the API.
