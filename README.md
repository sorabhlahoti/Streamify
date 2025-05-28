# ✨ Fullstack Chat & Video Calling App ✨

This is a fullstack application offering real-time chat and video calling functionalities.

---

## 🛠️ Setup & Installation

To get this project up and running, follow the steps below for both the backend and frontend.

### 🔧 Backend Setup (`/backend`)

1.  **Create a `.env` file** inside the `/backend` folder with the following contents. Make sure to replace the placeholder values with your actual keys and URIs:

    ```
    PORT=5001
    MONGO_URI=your_mongo_uri
    STEAM_API_KEY=your_steam_api_key
    STEAM_API_SECRET=your_steam_api_secret
    JWT_SECRET_KEY=your_jwt_secret
    NODE_ENV=development
    ```

2.  **Install dependencies and run the server**:

    ```bash
    cd backend
    npm install
    npm run dev
    ```

### 💻 Frontend Setup (`/frontend`)

1.  **Create a `.env` file** inside the `/frontend` folder with the following content, replacing `your_stream_api_key` with your actual Stream API key:

    ```
    VITE_STREAM_API_KEY=your_stream_api_key
    ```

2.  **Install dependencies and run the client**:

    ```bash
    cd frontend
    npm install
    npm run dev
    ```

---

## 🎥 Features

* **🌐 Real-time Chat**: Enjoy real-time chat with online status, typing indicators, and message reactions.
* **📹 Video Calls**: Conduct 1-on-1 and group video calls, including screen sharing and recording capabilities.
* **🔐 Secure Authentication**: Features JWT authentication with intuitive onboarding flows and protected routes for enhanced security.
* **🎨 Multiple UI Themes**: Personalize your experience with a variety of UI themes.
* **👥 Friends System**: Connect with others through a robust friends system and social interaction features.
* **🚨 Robust APIs**: Benefit from robust error handling and well-tested APIs for reliable performance.

---

## 📂 Project Structure
```
.
├── /backend         # Express server, APIs, and Mongoose models
└── /frontend        # React app, components, pages, and styles
```
---

## 🤝 Contributing

Contributions are always welcome! If you have suggestions for improvements, feel free to open an issue or submit a pull request.