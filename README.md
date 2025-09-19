Online Transport Tracking and Scheduling System

Tech Stack at a Glance
Layer	Technology / Tools
Frontend	React Native, Expo, Redux, React Navigation, react-native-maps, Axios, socket.io-client
Backend	Flask, SQLite, Socket.IO
Additional	Google Maps API for live bus tracking
Overview

This project is a complete Online Transport Tracking and Scheduling System, fully developed by me (Ankit Jadhav), including both frontend and backend.
It allows efficient bus management, real-time tracking, ticket booking, and administrative control.

Key Features

Real-Time Bus Tracking: View live bus locations on a map with estimated arrival times.

Ticket Booking: Book tickets for specific routes and schedules.

Admin Dashboard: Manage routes, schedules, and monitor system operations.

Notifications: Receive alerts about bus arrivals, delays, or cancellations.

Project Structure
├── backend/        # Flask backend
│   ├── app.py      # Main server file
│   ├── models.py   # Database models
│   └── utils/      # Helper modules (e.g., CSV handler)
├── frontend/       # React Native frontend
│   ├── App.js      # Main entry point
│   ├── components/ # Reusable UI components
│   └── screens/    # App screens
└── README.md       # Project documentation

Installation
Backend Setup

Clone the repository:

git clone https://github.com/ankit8801/Online-Transport-Tracking-And-Scheduling.git
cd Online-Transport-Tracking-And-Scheduling/backend


Install dependencies:

pip install -r requirements.txt


Apply migrations:

python manage.py migrate


Run the server:

python manage.py runserver

Frontend Setup

Navigate to the frontend directory:

cd ../frontend


Install dependencies:

npm install
npm install expo
npm install @react-navigation/native @react-navigation/stack
npm install redux react-redux
npm install react-native-maps
npm install socket.io-client
npm install axios


Run the application:

npm start


⚠️ Make sure you have Expo CLI installed globally:

npm install -g expo-cli

Team Contribution

This was a team project, but the entire frontend and backend development — including all core features, APIs, UI, and real-time tracking — was implemented entirely by me (Ankit Jadhav).
Other team members contributed in areas such as conceptualization, testing, and documentation.

License

This project is licensed under the MIT License. See LICENSE
 for details.

Contact

👨‍💻 Developed by Ankit Jadhav
🔗 GitHub: ankit8801

For questions or feedback, feel free to open an issue or contact me directly.