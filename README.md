# Velvet & Cocoa

Full-stack MERN chocolate/sweets store ready for GitHub.

## Deploy
- MongoDB: MongoDB Atlas
- Backend: Render, root directory `backend`, build `npm install`, start `npm start`
- Frontend: Vercel, root directory `frontend`, build `npm run build`

## Environment
Backend: copy `.env.example` to `.env` and set `MONGO_URI`, `JWT_SECRET`, `CLIENT_URL`.
Frontend: set `VITE_API_URL` to your deployed backend URL.

## Admin
Register normally, then run from backend:
`npm run make-admin -- your@email.com`
