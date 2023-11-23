# Software-Engineering
CS 361
1. Requesting Data
        Endpoint
        The microservice supports the following endpoint for removing a task:    DELETE /tasks/{task_id}: Remove a task by providing its unique identifier.
        
        Example Call:
        To remove a task with ID 123, make a DELETE request to the following endpoint:
                  curl -X DELETE http://localhost:5000/tasks/123

2. Receiving Data
       Example successful response:
               "message": "Task removed successfully"  

       Example error response (if the task with the specified ID is not found):
             "error": "Task not found"



   ![image](https://github.com/OwenBrunty/Software-Engineering/assets/79432016/167268fa-cdbc-4db4-a2d5-5c623d5db87a)
