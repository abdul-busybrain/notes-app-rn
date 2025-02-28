# React Native Notes App

![Project Banner](./assets/images/post-it.png)

A fully-featured notes application built with React Native and Expo. This project was created following the "React Native Crash Course+ | Build a Mobile App In a 3 Hours" tutorial.

## 📱 About This Project

This mobile application allows users to create, read, update, and delete notes with a clean, intuitive interface. Built for both iOS and Android platforms using a single codebase, it features:

- User authentication (signup/login)
- Full CRUD functionality for notes
- Backend integration with Appwrite
- Responsive and attractive UI

## 🚀 Quick Start

### Prerequisites

- Node.js installed on your machine
- Expo CLI (`npm install -g expo-cli`)
- Expo Go app installed on your physical device (optional)
- iOS Simulator or Android Emulator (optional)

### Installation

1. Clone this repository

   ```bash
   git clone https://github.com/abdul-busybrain/notes-app-rn
   cd notes-app-rn
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Start the development server

   ```bash
   npx expo start
   ```

4. Run the app
   - Scan the QR code with Expo Go (Android) or Camera app (iOS)
   - Press 'a' for Android Emulator
   - Press 'i' for iOS Simulator
   - Press 'w' for web browser

## 📖 What I've Learned

### Introduction to React Native

Learn how React Native enables building native mobile applications for iOS and Android using a single JavaScript codebase. Understand the key differences between React Native and traditional web development.

### Project Setup and Configuration

Master the process of setting up a React Native project with Expo, including initializing the project, understanding the file structure, and configuring necessary dependencies.

### Building Core Functionality

Develop the essential features of a notes app:

- Creating new notes
- Viewing a list of existing notes
- Updating note content
- Deleting unwanted notes

### Backend Integration

Implement a connection to Appwrite to store and retrieve data, enabling persistence across app sessions and devices. Learn how to structure API calls for efficient data management.

### User Authentication

Implement secure user signup and login functionality to protect user data and provide personalized experiences. Learn best practices for handling user credentials and maintaining session state.

### Styling and UI/UX Design

Apply styling techniques specific to React Native to create an intuitive and visually appealing interface that follows mobile design principles and enhances user experience.

### Deployment Preparation

Understand the process of building and publishing your application to app stores, including configuration requirements and submission guidelines.

## 🛠️ Advanced Development

### Fresh Project Setup

When you're ready to start from scratch:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

### File-Based Routing

This project leverages Expo's file-based routing system. Navigation is handled automatically based on the file structure in the `app` directory.

## 🤝 Join the Community

- [Expo on GitHub](https://github.com/expo/expo): View the open source platform and contribute
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions

## 📚 Additional Resources

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Learn Expo Tutorial](https://docs.expo.dev/tutorial/introduction/)

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
