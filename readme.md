Create a full-featured Student Management System for an educational institution. The system should allow admins, teachers, and students to interact with the platform based on their roles. The system must be secure, scalable, and responsive.

Core Features:
Authentication and Role Management
Admin, Teacher, and Student roles
Secure login/logout
Password hashing and reset option
Role-based access control
Student Management
Add, edit, delete, and view student profiles
Upload student photos and documents
Assign students to classes or courses
Class and Course Management
Create and manage classes, subjects, and schedules
Assign teachers to courses
Attendance tracking (manual or automatic)
Grades and Reports
Record and view student grades
Generate report cards and downloadable PDFs
Communication Tools
Announcements/Notices from Admin
Messaging between teachers and students
Dashboard
Role-specific dashboards (admin overview, teacher tasks, student progress)
Charts and analytics (student count, attendance rates, average grades)
Settings
Manage academic year, grading system, school profile
Tech Stack Suggestions
Frontend:

HTML5, CSS3, JavaScript (ES6+)
Framework: React.js (or Vue.js or Angular if preferred)
State Management: Redux or Context API
UI Library: Tailwind CSS or Material UI
Form handling with validation (Formik or React Hook Form)
Chart Library: Chart.js or Recharts
Axios or Fetch API for HTTP requests
Backend:

Language: Node.js (Express.js) or Python (Django or Flask)
Authentication: JWT or OAuth
ORM: Sequelize (for Node.js) or Django ORM (for Python)
Validation: Joi (Node.js) or Django forms
Database:

PostgreSQL or MySQL for relational data
MongoDB (optional, if needed for document storage)
APIs:

RESTful API (or GraphQL if preferred)
CRUD operations for all major entities
Secure endpoints with middleware for role checking
DevOps/Deployment:

Git for version control
Docker for containerization (optional)
Deployment to platforms like Heroku, Vercel, or DigitalOcean
CI/CD with GitHub Actions (optional)
Optional Add-ons:
