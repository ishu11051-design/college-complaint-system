# College Complaint System - Setup Guide

## Installation Guide

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/ishu11051-design/college-complaint-system.git
   ```
2. Navigate to the backend directory:
   ```bash
   cd college-complaint-system/backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd college-complaint-system/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## API Endpoints Documentation
- **Base URL:** `http://localhost:3000/api`

- **Endpoints:**
  - `GET /complaints`: Get all complaints
  - `POST /complaints`: Create a new complaint
  - `GET /complaints/:id`: Get a complaint by ID
  - (Add more endpoints as necessary)

## Test Accounts
- **Admin Account**
  - Username: `admin`
  - Password: `admin123`

- **User Account**
  - Username: `user`
  - Password: `user123`

## Troubleshooting
- **Common Issues:**
  - If the backend fails to start, ensure that the database is running.
  - Check for missing environment variables and ensure they are set correctly.

## Deployment Instructions
1. Build the application:
   ```bash
   npm run build
   ```
2. Deploy the backend to your server of choice. Ensure you have the necessary environment configurations.
3. Deploy the frontend to a web server. (Add specific instructions based on the hosting solution)