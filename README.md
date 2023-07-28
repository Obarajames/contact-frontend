#Introduction
This documentation provides an overview of the "MERn Contact List" project, a web application built using the MERn stack (MongoDB, Express, React, and Node.js). The project allows users to log in and save contacts in their contact list. Users are categorized into different roles based on their level of work: Employee, Manager, and Admin. Each role has different levels of access and permissions within the application.

#Technologies Used
React: A front-end JavaScript library used for building the user interface.
Node.js: A JavaScript runtime environment used for server-side development.
Express: A web application framework for Node.js used for building the back-end.
MongoDB: A NoSQL database used for storing contact information.
JSON Web Tokens (JWT): Used for authentication and session management.
#Features
User Authentication
Users can create an account and log in to the application.
Passwords are securely hashed and stored in the database.
JSON Web Tokens (JWT) are used for secure authentication and session management.
Role-Based Access Control
The application supports three different roles: Employee, Manager, and Admin.
Each role has different levels of access and permissions within the application.
Employees can view and edit their own contacts.
Managers can view and edit contacts of employees in their team.
Admins have full access to all contacts and can manage user roles.
Contact Management
Users can add new contacts to their contact list.
Contacts can have various fields, such as name, phone number, email, and work details.
Contacts are associated with the user who added them.
Users can edit or delete contacts from their list.


Setup and Installation
Clone the project repository from [GitHub link].
Install Node.js and npm (Node Package Manager) if you haven't already.
Set up MongoDB on your system or use a cloud-based MongoDB service.
Create a .env file in the server directory to store environment variables such as database connection string and JWT secret.
Getting Started
Run the MongoDB server and ensure it's connected.
Navigate to the server directory and install the required dependencies using npm install.
Start the server using npm start or node index.js.
Navigate to the client directory and install the required dependencies using npm install.
Start the React development server using npm start.
Access the application in your web browser at http://localhost:3000.
