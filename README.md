# 🏨 HotelEase – AI-Powered Hotel Booking Chatbot

## 📌 Overview

**HotelEase** is an AI-driven chatbot that simplifies hotel searching and booking. With smart, conversational interaction, it provides real-time hotel recommendations based on user preferences such as location, budget, check-in/check-out dates, and number of guests. It also offers travel itinerary suggestions, making trip planning seamless and user-friendly.

---

## ✨ Features

- **💬 Conversational Hotel BookingSearch for hotels by chatting naturally with the bot.**

- **🧠 Personalized RecommendationsAI suggests hotels tailored to your preferences.**

- **⚡ Instant BookingBook hotels directly from the chatbot interface.**

- **📁 My Bookings ManagementView, modify, or cancel your hotel reservations easily.**

- **🗽 Travel Itinerary SuggestionsGet AI-powered recommendations for must-visit places at your destination.**

- **⌨️ Text SupportChat with the bot using natural language text commands.**

---

## 💠 Technology Stack

### 🔹 Frontend

- React.js – UI framework

- CSS – Styling and layout

### 🔹 Backend

- Node.js & Express.js – API and server handling

- MongoDB – Stores bookings and user preferences

### 🔹 AI & NLP

- Gemini / Dialogflow – Natural Language Processing for chatbot conversations

- Sentiment Analysis – Enhances interaction understanding

### 🔹 API Integrations

- **TBO API** – For real-time hotel search data

## 📁 Project Structure

HotelEase/
│
├── src/
│   └── components/
│       ├── Chatbot.jsx          # Chatbot UI Component
│       ├── Navbar.jsx           # Navigation Bar
│       ├── ExploreRooms.jsx
│       ├── Hero.jsx
│       └── MyBookings.jsx
│
├── backend/
│   ├── main.py
│   ├── .env
│   └── __pycache__/
│
├── public/
├── README.md
└── package.json

## ⚙️ Installation & Setup

### 1. Clone the Repository

- git clone https://github.com/SHAKSHIY/Hotel-Search-Chatbot.git

- cd Hotel-Search-Chatbot

### 2. Install Dependencies

#### Frontend

- cd HotelEase
- npm install
- npm run dev

#### Backend

- cd backend
- pip install uvicorn fastapi python-dotenv requests google-generativeai

### 3. Configure Environment Variables

- Create a .env file inside the backend/ directory and add the following keys:

- TBO_API_KEY=your_tbo_api_key
- GEMINI_API_KEY=your_gemini_api_key

## 🔌 API Endpoints

| Method | Endpoint                                 | Description                     |
|--------|------------------------------------------|---------------------------------|
| GET    | `/api/hotels?location=Paris&budget=200` | Fetch hotel listings by query  |
| POST   | `/api/bookings`                          | Book a selected hotel          |
| GET    | `/api/bookings/:userId`                  | Retrieve bookings for a user   |


## 📣 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change. Contributions that improve functionality, design, or documentation are highly appreciated.
🙌 Acknowledgments

TBO.com for hotel API

Google Gemini / Dialogflow for AI integration

