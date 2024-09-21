Job Portal
This job portal is developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It offers a secure platform for users to search for jobs, apply for positions, and manage their profiles, while providing admin functionalities for managing job listings and applications.

Table of Contents
Features
Technologies Used
Installation
Project Structure
API Endpoints
Usage
Contributing
License
Features
User Authentication: Secure login and signup with protected routes.
Job Filtering: Search and filter job listings by location, job type, and salary.
User Profiles: Manage personal profiles and track job applications.
Admin Dashboard: Admin functionalities for managing job listings and applications.
File Uploads: Support for file uploads using Multer.
State Management: Utilizes Redux Toolkit for efficient state management.
Custom Hooks: Custom React hooks for API calls.
Responsive Design: Built with Shadcn UI and Vite for a modern look and feel.
Technologies Used
Frontend:

React.js
Vite
Shadcn UI
Redux Toolkit
Backend:

Node.js
Express.js
MongoDB
JWT (JSON Web Tokens) for authentication
Multer for file uploads
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/job-portal.git
cd job-portal
Install backend dependencies:

bash
Copy code
cd backend
npm install
Install frontend dependencies:

bash
Copy code
cd frontend
npm install
Configure environment variables:

Create a .env file in the backend folder and add your MongoDB connection string and other necessary variables.
Run the application:

Backend:

bash
Copy code
cd backend
npm start
Frontend:

bash
Copy code
cd frontend
npm run dev
Project Structure
arduino
Copy code
job-portal/
├── backend/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── .env
│   ├── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── hooks/
│   ├── public/
│   ├── index.html
│   ├── package.json
API Endpoints
User Routes:

POST /api/users/signup: Register a new user.
POST /api/users/login: Authenticate user and return a token.
Job Routes:

GET /api/jobs: Get all job listings.
POST /api/jobs: Create a new job (admin only).
PUT /api/jobs/:id: Update a job (admin only).
DELETE /api/jobs/:id: Delete a job (admin only).
Application Routes:

POST /api/applications: Apply for a job.
GET /api/applications: Get all applications (user specific).
Usage
App Demo: [Link to demo if available]
Users can register and log in to access their profiles and job listings.
Admins can manage job postings and applicant statuses.
Contributing
Feel free to submit issues and pull requests. Please ensure to follow the code style and structure outlined in this README.


