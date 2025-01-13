# todo-backend

Testing the API
Endpoint Method Auth Required Description Body Example
/register POST No Register a new user { "username": "user1", "password": "pass" }
/login POST No Login a user { "username": "user1", "password": "pass" }
/todos GET Yes Get all to-dos None
/todos POST Yes Add a new to-do { "title": "New Todo" }
/todos/:id PUT Yes Update a to-do { "title": "Updated Title", "completed": true }
/todos/:id DELETE Yes Delete a to-do None
