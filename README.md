
# Points Claiming App (MERN Stack)

This is a full-stack web application that allows users to register, claim random points, and view a dynamic leaderboard. Built with **Vite + ReactJS** on the frontend and **Node.js + Express + MongoDB** on the backend.


## Features

-  User registration (simple name input)
-  Random point claiming per user
-  Claim history tracking
-  Leaderboard sorted by total points
-  Switch between users via dropdown
-  Toast notifications with `react-hot-toast`
-  Responsive, clean UI using Tailwind CSS
-  Server-side pagination for leaderboard

---

## Tech Stack

### Frontend:
- React (Vite)
- React Router
- Axios
- Tailwind CSS
- React Hot Toast

### Backend:
- Node.js
- Express
- MongoDB
- Mongoose
- dotenv
- colors (for dev console logs)

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/jvkedev/leaderboard-app.git

```

### 2. Navigate to the Project Directory

```
cd leaderboard-app

```
### 3. Install Frontend Dependencies

```
cd frontend

npm install

```

### 4. Start Backend

```
cd backend

nodemon app

```

### 5. Start Frontend

```
cd frontend

npm run dev

```
## Notes

- The project uses React, Tailwind CSS and Node.js with Express for handling backend logic.
- Frontend and backend are placed in separate folders for a clear structure.
- Users can register with a simple name input and switch between accounts using a dropdown.
- Each user can claim random points, and all claims are stored for history tracking.
- The leaderboard updates automatically based on total points and supports server-side pagination.
- Toast notifications are handled through react-hot-toast for better UX.
- The layout is responsive and built with clean UI patterns.
- This setup is designed for learning and practicing MERN development.

---

## License

This project is for educational purposes only.

## Author
### JVKE
