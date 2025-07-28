# TravelEase

TravelEase is a smart travel companion web app that uses AI to generate personalized travel itineraries based on your preferences, budget, and destination. Plan your next adventure with ease!

## Features

- **AI-Powered Trip Planning:**  
  Generate custom travel itineraries for any location, tailored to your style, budget, and number of travelers.

- **Hotel & Place Recommendations:**  
  Get a list of hotels and must-visit places with details like address, price, images, geo-coordinates, and ratings.

- **Google Places Integration:**  
  Search and autocomplete destinations using Google Places API.

- **Save & View Trips:**  
  Save your generated trips and view them anytime.

- **User Authentication:**  
  Sign in with Google to save and manage your trips.

- **Modern UI:**  
  Responsive and visually appealing interface.

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm

### Installation

1. **Clone the repository:**
   ```
   git clone <your-repo-url>
   cd TravelEase
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the project root with the following content:

   ```
   VITE_GOOGLE_PLACE_API_KEY=your_google_place_api_key_here
   VITE_GOOGLE_GEMINI_AI_API_KEY=your_google_gemini_ai_api_key_here
   VITE_FIREBASE_API_KEY=your_firebase_api_key_here
   VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain_here
   VITE_FIREBASE_PROJECT_ID=your_firebase_project_id_here
   VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket_here
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id_here
   VITE_FIREBASE_APP_ID=your_firebase_app_id_here
   VITE_FIREBASE_MEASUREMENT_ID=your_firebase_measurement_id_here
   VITE_GOOGLE_AUTH_CLIENT_ID=your_google_auth_client_id_here
   ```

   > You can obtain Google API keys from the [Google Cloud Console](https://console.cloud.google.com/) and Firebase credentials from the [Firebase Console](https://console.firebase.google.com/).

4. **Start the development server:**
   ```
   npm run dev
   ```

5. **Open your browser:**  
   Visit [http://localhost:5173](http://localhost:5173) (or the port shown in your terminal).

## Project Structure

- `src/` - Main source code
  - `components/` - Reusable UI components
  - `create-trip/` - Trip creation logic and UI
  - `view-trip/` - Trip viewing pages
  - `service/` - API and Firebase configuration
  - `about-us/` - About page and contact info

## Tech Stack

- React
- Vite
- Firebase (Firestore)
- Google Places API
- Google Gemini AI API
- Tailwind CSS

## License

MIT
