# Todo API Project  

A simple Todo API built using **Postman** and **Supabase** to demonstrate CRUD operations (Create, Read, Update, Delete).  

## Features  
- Add a new task  
- View all tasks  
- Update a task’s status (e.g., pending → done)  
- Delete a task  

## Tech Stack  
- **Supabase** (PostgreSQL backend)  
- **Postman** (API testing and documentation)  
- REST API principles  

## API Endpoints  
- `POST /todos` → Add a new task  
- `GET /todos` → View all tasks  
- `PATCH /todos?id=eq.{id}` → Update a task’s status  
- `DELETE /todos?id=eq.{id}` → Remove a task  

## Example Request  
**Add a Task (POST /todos)**  
```json
{
  "task": "Learn APIs",
  "status": "pending"

}
Added project documentation including features, tech stack, API endpoints, and example request for the Todo API.
}
