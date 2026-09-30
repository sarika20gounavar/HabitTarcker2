HABIT TRACKER - FEATURE SET A

Requirements:
- Node.js
- MongoDB Community Server or MongoDB-compatible local server

SETUP:

1. Open this folder in VS Code.
2. Open the terminal in this folder.
3. Run:
   npm install

4. Make sure MongoDB is running locally.

5. Run:
   node server.js

6. Open:
   http://localhost:3000

Features:
- Add habits
- Habit categories
- Complete habit for today
- Current streak calculation
- Progress history
- Delete habit

MongoDB database:
habitTracker

API:
POST   /api/habits
GET    /api/habits
PUT    /api/habits/:id/complete
DELETE /api/habits/:id
