<div align="center">

# 🎓 Engademy - Smart English Learning App

**Engademy** is an intelligent mobile application integrated with AI to support users in learning and improving their English skills. This application was developed as a Capstone Project.

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?logo=Flutter&logoColor=white)](#) 
[![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)](#)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?logo=Firebase&logoColor=white)](#)
[![Gemini API](https://img.shields.io/badge/Google%20Gemini-8E75B2?logo=google&logoColor=white)](#)

[Explore Features](#-key-features) • [Getting Started](#-getting-started) • [Tech Stack](#-tech-stack)

</div>

<br/>

## 🌟 Key Features

- 🤖 **Smart AI Integration (Gemini API):** An interactive virtual assistant that answers questions, suggests grammar corrections, and generates dynamic conversations.
- 💬 **Natural Language Processing (NLP):** Evaluates, corrects, and processes natural language inputs utilizing Node.js backend power.
- 🗂️ **Flashcard Learning:** A visual and interactive vocabulary memorization experience featuring physical card-flip animations.
- 🔐 **Secure Authentication:** Seamless multi-device synchronization and secure user login/registration powered by Firebase.
- 🎨 **Material Design & Effects:** Modern UI with smooth animations, shimmer loading effects, and support for Dark/Light Themes.

## 📸 Screenshots (*Placeholder*)

Add screenshots or GIFs of your application here to make the repository more visually appealing:

<p align="center">
  <img src="https://via.placeholder.com/250x500.png?text=Home+Screen" width="200" style="margin: 0 10px; border-radius: 10px;"/>
  <img src="https://via.placeholder.com/250x500.png?text=Flashcards" width="200" style="margin: 0 10px; border-radius: 10px;"/>
  <img src="https://via.placeholder.com/250x500.png?text=AI+Chatbot" width="200" style="margin: 0 10px; border-radius: 10px;"/>
</p>

## 🛠 Tech Stack

This project is built using a Client-Server architecture:

### 📱 Frontend (Mobile App / Client)
- **Framework:** Flutter (Mobile/Web)
- **Language:** Dart
- **State Management:** Provider
- **UI Libraries:** Cupertino Icons, Google Fonts, Shimmer, Flip Card
- **AI SDK:** `google_generative_ai`

### ⚙️ Backend (RESTful Server)
- **Runtime:** Node.js
- **Framework:** Express.js
- **Security & Middleware:** CORS
- **NLP Processing:** `natural`

### ☁️ Database & Cloud Services
- **Firebase Auth:** Identity management and session handling.
- **Cloud Firestore:** Real-time NoSQL database for flashcards, user profiles, and chat history.
- **Firebase Admin SDK:** Secure backend administrative access through the Node.js server.

## 🚀 Getting Started

Note: Ensure you have [Flutter SDK](https://docs.flutter.dev/get-started/install) and [Node.js](https://nodejs.org/) installed on your machine.

### 1. Server Setup (Node.js)

Clone this repository and start the backend development server:

```bash
# Clone the repository
git clone <YOUR_REPOSITORY_URL>

# Navigate to the project directory
cd <YOUR_PROJECT_FOLDER_NAME>

# Install NPM packages
npm install

# Start the Backend Server
node server.js
```
*(The server runs on `http://localhost:3000` by default)*

### 2. Client Setup (Flutter)

Open another Terminal window or your IDE (VSCode/Android Studio) to build the Flutter app:

```bash
# Ensure you are in the root directory containing pubspec.yaml
# Fetch Dart/Flutter dependencies
flutter pub get

# Run the application on an attached device or emulator
flutter run
```

### 🔑 Environment Variables & Firebase Configuration

For the project to work seamlessly, you must **add the environment secrets**:
1. Get a Gemini API Key from [Google AI Studio](https://aistudio.google.com/) and create a `.env` file in the root directory:
   ```env
   GEMINI_API_KEY=YOUR_API_KEY_HERE
   ```
2. Add your Firebase configuration files (`google-services.json` inside the `android/app/` directory for Android, and `GoogleService-Info.plist` inside `ios/Runner/` for iOS).

## 🤝 Contributing & Authors

Capstone Project (Đồ Án Chuyên Ngành)

If you find any bugs or have feature requests, please feel free to open a **Pull Request** or an **Issue** in this repository. Thank you for your interest!

---
<p align="center">Built with 💙 from the community and modern toolkits.</p>
