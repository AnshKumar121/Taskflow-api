Get All Tasks:
GET /api/tasks

Create Task:
POST /api/tasks
Body:
{
  "text": "Learn Express"
}

Get Single Task:
GET /api/tasks/1

Update Task:
PUT /api/tasks/1
Body:
{
  "completed": true
}

Delete Task:
DELETE /api/tasks/1
Response:
204 No Content

Run the Project:
npm install
npm start
Server starts at:
http://localhost:5000
