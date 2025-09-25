You can also check the my work at postman
https://www.postman.com/descent-module-cosmologist-81324735/workspace/task3/collection/32354479-557e7bb5-dcac-4f21-8610-36806675f775?action=share&source=copy-link&creator=32354479


Implementations done.
GET all books

Method: GET

URL: http://localhost:3000/books

Purpose: List all books

GET a single book

Method: GET

URL: http://localhost:3000/books/1

Purpose: Get details of one book by ID

POST – Add a new book

Method: POST

URL: http://localhost:3000/books

Body (JSON):

{
  "title": "Harry Potter",
  "author": "J.K. Rowling"
}


Purpose: Add a new book

PUT – Update a book completely

Method: PUT

URL: http://localhost:3000/books/1

Body (JSON):

{
  "title": "Animal Farm",
  "author": "George Orwell"
}


Purpose: Replace all details of a book

PATCH – Update part of a book

Method: PATCH

URL: http://localhost:3000/books/1

Body (JSON):

{
  "title": "The Lord of the Rings"
}


Purpose: Change only specific fields

DELETE – Remove a book

Method: DELETE

URL: http://localhost:3000/books/1

Purpose: Remove a book by ID
