chek the following assignment in postman how to work CRUD opration on url

1:--
method:GET
http://localhost:3000/tasks //this url is get the in blank 
output is -->
[]


2:--
Method: POST
URL: http://localhost:3000/tasks
in herader saction type key is "Content-Type" and Value is "application/json"
after that in body section select row and write a title and description
example:
      {
      "id":1,
  "title": "Sample Task",
  "description": "This is a description for the sample task"
}


and send the request


3:-- is 
Method: GET
URL: http://localhost:3000/tasks/1
Headers: None
Body: None

output is 
{
  "id": 1,
  "title": "Sample Task",
  "description": "This is a sample task description"
}

4:--
Method: PUT
URL: http://localhost:3000/tasks/1
Headers:
in herader saction type key is "Content-Type" and Value is "application/json"
and body section is following because put method is update the title and descriotion

example--
{
  "title": "Updated Task",
  "description": "Updated task description"
}

5:--
Method: DELETE
URL: http://localhost:3000/tasks/1
id 1 is deleted.


this all are a CRUD opration in this assignment..




