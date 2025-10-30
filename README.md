# Cactus-Information-Website
# Cactus Information Website (Full-stack)
This project is a college assignment web application.
It includes:
- Frontend: React (in /frontend)
- Backend: Node.js + Express + Mongoose (in /backend)
- MongoDB used for data storage

# Setup (local)
1. Install Node.js (v18+ recommended) and MongoDB (or use MongoDB Atlas).
2. Backend:
   - cd backend
   - npm install
   - create a .env file (you can copy .env.example) and set MONGO_URI and JWT_SECRET
   - npm run dev
3. Frontend:
   - cd frontend
   - npm install
   - npm start
   - The frontend expects the backend to be served under the same origin (proxy can be added in package.json) or adjust API URLs.

## Notes
- You created this project for your college coursework; feel free to customize UI and data.
- Seed data script is provided at backend/seed.js
