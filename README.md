<div align="center">

# Engademy - Smart English Learning App

**Engademy** is an intelligent mobile application integrated with Artificial Intelligence (AI) to help users improve their English skills. This application was developed as a Capstone Project.

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?logo=Flutter&logoColor=white)](#) 
[![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)](#)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?logo=Firebase&logoColor=white)](#)
[![Gemini API](https://img.shields.io/badge/Google%20Gemini-8E75B2?logo=google&logoColor=white)](#)

[Key Features](#key-features) • [Installation](#installation-and-setup) • [Tech Stack](#tech-stack)

</div>

---

## Key Features

- **Smart AI Integration (Gemini API):** An interactive virtual assistant that answers questions, suggests grammar corrections, and generates realistic conversations.
- **Natural Language Processing (NLP):** Evaluates, corrects, and processes natural language inputs utilizing a Node.js backend server.
- **Flashcard Learning System:** Provides an intuitive vocabulary memorization experience featuring physical card-flip animations.
- **Secure Authentication:** Secure user login, registration, and seamless multi-device data synchronization powered by Firebase.
- **Material Design Interface:** A modern UI with smooth animations, shimmer loading effects, and comprehensive Dark Theme support.

## Screenshots

*(Please update the screenshots or GIFs of the application here for better visualization)*

<p align="center">
  <img src="https://via.placeholder.com/250x500.png?text=Home+Screen" width="200" style="margin: 0 10px; border-radius: 10px;"/>
  <img src="https://via.placeholder.com/250x500.png?text=Flashcards" width="200" style="margin: 0 10px; border-radius: 10px;"/>
  <img src="https://via.placeholder.com/250x500.png?text=AI+Chatbot" width="200" style="margin: 0 10px; border-radius: 10px;"/>
</p>

## Tech Stack

This project is built using a Client-Server architecture and the following technologies:

### Frontend (Mobile App)
- **Framework:** Flutter
- **Language:** Dart
- **State Management:** Provider
- **UI Libraries:** Cupertino Icons, Google Fonts, Shimmer, Flip Card
- **AI SDK:** google_generative_ai

### Backend (RESTful Server)
- **Runtime:** Node.js
- **Framework:** Express.js
- **Security & Middleware:** CORS
- **NLP Processing:** natural

### Database & Cloud Services
- **Firebase Auth:** Identity management and user session handling.
- **Cloud Firestore:** Real-time NoSQL database to store flashcards, chat histories, and user profiles.
- **Firebase Admin SDK:** Secure backend administrative access through the Node.js server.

## Installation and Setup

**Prerequisites:**
Ensure you have the [Flutter SDK](https://docs.flutter.dev/get-started/install) and [Node.js](https://nodejs.org/) installed on your machine.

### 1. Server Setup (Node.js)

Run the following commands to clone the repository and start the server:

```bash
# Clone the repository
git clone <YOUR_REPOSITORY_URL>

# Navigate to the project directory
cd <YOUR_PROJECT_FOLDER_NAME>

# Install NPM dependencies
npm install

# Start the Backend Server
node server.js
```
*(Note: The server handles incoming requests on `http://localhost:3000` by default)*

### 2. Client Setup (Flutter)

Open a new Terminal window, navigate to the root directory representing the Flutter project:

```bash
# Fetch Dart dependencies
flutter pub get

# Run the application on an attached device or emulator
flutter run
```

### Environment Configuration

For the project to work properly, you must configure the following security parameters:
1. Register and generate an API Key from [Google AI Studio](https://aistudio.google.com/). Create a `.env` file in the root directory and add the following line:
   ```env
   GEMINI_API_KEY=YOUR_API_KEY_HERE
   ```
2. Add your Firebase configuration files based on the platform:
   - For **Android**: Place the `google-services.json` file inside the `android/app/` directory.
   - For **iOS**: Place the `GoogleService-Info.plist` file inside the `ios/Runner/` directory.

## Contributing and Additional Info

Capstone Project (Đồ án Chuyên ngành - DACN).

If you encounter any bugs or would like to propose new features, please feel free to open a **Pull Request** or create an **Issue** in this repository.

---
<p align="center">Built by the community and modern open-source toolkits.</p>
