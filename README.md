🌍 Globetrotter Challenge
Globetrotter Challenge is an exciting travel-themed guessing game where players have to guess the destination based on clues. Challenge your friends by sharing your score and see who’s the ultimate globetrotter!

🚀 Features
Guess the destination based on clues within a 30-second timer.

Fun facts and trivia revealed after each guess.

Invite friends to challenge your score via a shareable link.

Dynamic questions and random options from a curated dataset.

Game over screen with the final score and a restart option.

Beautiful travel-themed aesthetic with MUI styling.

🛠️ Tech Stack
Frontend
React: Component-based UI.

MUI (Material-UI): For modern, aesthetic design.

Axios: For making HTTP requests.

React Confetti: Celebration effect on correct answers.

Backend
Node.js and Express: Backend server and APIs.

Body-Parser and CORS: Middleware for request parsing and cross-origin support.

File System (fs): To store and retrieve user data and questions.

JSON: Storing questions and user scores.

🗃️ Project Structure
csharp
Copy
Edit
Globetrotter-Challenge/
├── client/                 # Frontend React application
│   ├── public/              # Static assets
│   ├── src/                 # Source code
│   │   ├── components/      # React components
│   │   ├── api.js           # API calls to backend
│   │   ├── App.js           # Main application component
│   │   └── index.js         # Entry point
└── server/                 # Backend server
    ├── data.json           # User data file
    ├── questions.json      # Destination questions
    └── server.js           # Express server
⚙️ Setup Instructions
Prerequisites
Node.js (v14+)

npm (v6+)

Step 1: Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/globetrotter-challenge.git
cd globetrotter-challenge
Step 2: Install dependencies
Frontend
bash
Copy
Edit
cd client
npm install
Backend
bash
Copy
Edit
cd ../server
npm install
Step 3: Start the server
bash
Copy
Edit
node server.js
The server runs at http://localhost:5000.

Step 4: Start the frontend
bash
Copy
Edit
cd ../client
npm start
The client runs at http://localhost:3000.

🚀 Running the Game
Open your browser and go to http://localhost:3000.

Enter your username to register.

Start guessing the destinations based on clues.

Share your score with friends using the Challenge a Friend button!

📝 Future Improvements
Image-based clues instead of text.

Multiplayer mode.

Track player progress and achievements.

Real-time leaderboard.