# EasyRide-Sharing-App
Ride for your life.
# EasyRide – Ride-Sharing Web App

## Project Overview
EasyRide is a **ride-sharing platform** connecting passengers and drivers using **React** and **Firebase**. It allows users to sign up as either drivers or passengers, book rides, manage bookings, and update their profiles. The application leverages **Firebase Authentication** and **Firestore** for secure user management and real-time data updates.

## Key Features
- **User Registration and Login**: Users can sign up and log in using their email and password. **Firebase Authentication** is used to manage user sessions and ensure persistent login across sessions.
  
- **Role-Based Access**: 
  - **Drivers** can post trips and manage bookings.
  - **Passengers** can search for available rides and make reservations.

- **Profile Management**: Users can update their profile information, including full name, phone number, and address. The app checks for profile completeness to ensure all required fields are filled before accessing sensitive areas such as the dashboard.

- **Ride and Booking Management**: 
  - **Drivers** can post trips with necessary details such as origin, destination, date, and available seats.
  - **Passengers** can search for trips that match their criteria and book rides.
  - Real-time data is managed using **Firestore’s onSnapshot** listeners for immediate updates.

- **Responsive Design**: The application is built with a mobile-first approach using **Tailwind CSS** to ensure a responsive and modern user interface.

## Build and Run Instructions
Follow these steps to set up and run the EasyRide project on your machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shivampatelcodes/Easyride
   cd easyride
Install Dependencies:

bash
Copy code
npm install
Setup Firebase Configuration:

Create a .env file in the root directory.
Add your Firebase configuration variables to the .env file as shown below:
env
Copy code
VITE_FIREBASE_API_KEY=your-api-key
VITE_FIREBASE_AUTH_DOMAIN=your-auth-domain
VITE_FIREBASE_PROJECT_ID=your-project-id
VITE_FIREBASE_STORAGE_BUCKET=your-storage-bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
VITE_FIREBASE_APP_ID=your-app-id
VITE_FIREBASE_MEASUREMENT_ID=your-measurement-id
Start the Development Server:

bash
Copy code
npm run dev
Build the Application for Production:

bash
Copy code
npm run build
Preview the Production Build:

bash
Copy code
npm run preview
Technologies Used
Frontend:

React: For building the user interface.
React Router: For client-side routing.
Tailwind CSS: For fast and responsive styling.
PropTypes: For prop type validation in React components.
Backend:

Firebase Authentication: For managing user sign up/sign in and maintaining persistent sessions.
Firestore: For storing app data, including user profiles, trips, and booking details.
Firebase Functions (optional): For hosting server-side logic if needed.
License
The MIT License was chosen because it’s simple, widely recognized, and allows others to freely use and contribute to the project. For full details, please see the LICENSE file.


