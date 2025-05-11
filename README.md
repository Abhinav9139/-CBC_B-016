# -CBC_B-016
AI-Based travel planner
Overview
AI Trip Advisor is a web application that generates personalized travel itineraries and hotel recommendations based on user preferences, budget, and destination. Powered by Google Maps APIs, Google Gemini AI, and Firebase, it simplifies travel planning with a user-friendly interface built using React and Tailwind CSS.
Features

Personalized Itineraries: Tailored trip plans based on user inputs (budget, destination, dates).
Hotel Recommendations: Budget-conscious hotel suggestions.
Dynamic Scheduling: Real-time itinerary adjustments.
Secure Authentication: Google OAuth for user login.
Responsive UI: Modern design with parallax effects and animations.

Tech Stack

Frontend: React 18.3.1, Vite 6.3.5, Tailwind CSS 3.4.6, Radix UI
APIs: Google Maps Places, Photos, Geolocation, Google Gemini AI
Backend: Firebase 11.7.1
Libraries: Axios, React Router DOM, GSAP, React Scroll Parallax
Tools: ESLint, PostCSS, Vite Plugin React

Installation
Prerequisites

Node.js (>=18.0.0)
npm
Google Cloud account for API keys
Firebase project for authentication

Steps

Clone the Repository:
git clone https://github.com/your-username/ai-trip-advisor.git
cd ai-trip-advisor


Set Up Environment Variables:Create a .env.local file in the root directory:
VITE_GOOGLE_PLACE_API_KEY=your_google_place_api_key
VITE_GOOGLE_GEMINI_AI_API_KEY=your_google_gemini_ai_api_key
VITE_GOOGLE_AUTH_CLIENT_ID=your_google_auth_client_id
FIREBASE_API_KEY=your_firebase_api_key


Install Dependencies:
npm install


Run the Application:
npm run dev

Access the app at http://localhost:5173.


Build for Production
npm run build
npm run preview

Usage

Homepage: Navigate to / for the main landing page with a Hero section.
Create Trip: Visit /create-trip to input travel preferences and generate an itinerary.
View Trip: Access /view-trip/:tripId to see detailed trip plans.
My Trips: Go to /my-trip to view saved trips.
Login: Use Google OAuth for personalized features.

Screenshots
(Include 6 screenshots here, e.g., homepage, trip creation form, itinerary view, etc. Placeholder for now due to lack of actual images.)
Contributing

Fork the repository.
Create a feature branch (git checkout -b feature/your-feature).
Commit changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
MIT License. See LICENSE for details.
