# Super30_sem1_project
Ice Cream Inventory Management
This is an inventory management system for ice cream products, built with React.js, Node.js, and SQL databases.

Technologies Used
Frontend: React.js

Backend: Node.js

Database: SQL (MySQL/PostgreSQL)

Features
Manage ice cream inventory

Add, update, and delete products

View product details with quantity

User-friendly interface for inventory tracking

Real-time updates of the stock quantity

Installation and Setup
Follow these steps to set up the project locally.

Prerequisites
Before you begin, ensure that you have the following installed:

Node.js (Latest version)

npm or yarn

SQL Database (MySQL or PostgreSQL)

A code editor (e.g., VS Code)

1. Clone the Repository
Clone this repository to your local machine:

bash
Copy
Edit
git clone https://github.com/kanishkagarud26/icecream-inventory-management.git
cd icecream-inventory-management
2. Set up the Backend
Go to the backend directory:

bash
Copy
Edit
cd backend
Install the required dependencies:
bash
Copy
Edit
npm install
Set up the database:
Create a database in MySQL/PostgreSQL.

Modify the database configuration in backend/config/db.js to match your credentials.

Run the server:
bash
Copy
Edit
npm start
The server should now be running at http://localhost:5000.

3. Set up the Frontend
Go to the frontend directory:

bash
Copy
Edit
cd ../frontend
Install the required dependencies:
bash
Copy
Edit
npm install
Run the React app:
bash
Copy
Edit
npm start
The app should now be running at http://localhost:3000.

4. API Endpoints
The backend exposes the following API endpoints:

GET /api/products - Get all products in the inventory.

POST /api/products - Add a new product.

PUT /api/products/:id - Update an existing product.

DELETE /api/products/:id - Delete a product.

5. Accessing the Application
Once both the backend and frontend are running, you can access the app in your browser at http://localhost:3000.

6. Troubleshooting
Ensure the backend server is running properly and that the database configuration is correct.

If the frontend is not loading, check the console for errors and resolve any dependency issues.

Make sure the backend and frontend are connected through API calls.

