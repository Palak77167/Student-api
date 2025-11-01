Student Record API

This is a small project made using **Node.js**, **Express**, and **MongoDB**.  
It is used to store and manage student records.



 How to Run

1. Install all packages  
   
   npm install
   

2. Create a .env file and add  
   
   MONGO_URI=your_mongodb_link
   PORT=5000
   

3. Start the server  
   
   npm start
   



 API Routes

| Method  |   Route        | Work |

| GET     |`/`             | Check if server is running |
| GET     |`/students`     | Show all students |
| POST    |`/students`     | Add new student |
| PUT  `  |`/students/:id` | Update student |
| DELETE  |`/students/:id` | Delete student |



 Files

- server.js → main file  
- config/db.js → database connection  
- routes/students.js → routes for students  


 Note
Run MongoDB before starting the project.  
You can test all APIs using **Postman**.
https://response-06-palak-4430881.postman.co/workspace/Personal-Workspace~20f101ae-1ea5-4af8-b45a-9f92afb1484b/collection/48668157-3beea816-00fc-4410-a861-f53e3a0d0b73?action=share&creator=48668157


   
