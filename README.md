# Cleaning Service Frontend (React)

This is the **frontend** part of the Cleaning Service Management System built using React and Material UI. It allows users to browse services, make bookings, and interact with the system through a user-friendly interface.

## Technologies Used

- React
- Axios
- React Router
- Material UI

## Setup Instructions

### 1. Clone the RepositoryOpen src/api.js and add this line to set the base URL for API calls:

```bash
git clone https://github.com/yourusername/cleaning-service-app.git
cd cleaning-service-app/frontend
npm install

**### Open src/api.js and add this line to set the base URL for API calls:**
const API = axios.create({ baseURL: 'http://localhost:5000/api' });

--Terminal--
npm start

The app will run at http://localhost:3000
