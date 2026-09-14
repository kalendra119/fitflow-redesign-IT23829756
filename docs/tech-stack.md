# FitFlow Technology Stack

## Frontend

React Native with Expo was selected for the mobile application. React Native Web will support the web interface. This approach allows the development team to reuse components and maintain a consistent experience across platforms.

## Backend

Node.js with Express was selected for the main backend API. It is lightweight, flexible and consistent with the FitFlow case study. Socket.IO can support real-time community interactions and challenge updates.

## Database

Firebase Firestore was selected as the main database. It provides real-time synchronization, offline mobile support and direct integration with React Native and Firebase services.

## Authentication

Firebase Authentication was selected to manage registration and login. The Express backend will verify Firebase identity tokens and apply authorization rules.

## Artificial Intelligence

TensorFlow Lite and ML Kit will support suitable on-device workout personalization and meal recognition. An optional FastAPI cloud service may be added later for heavier AI processing.

## Notifications and Storage

Firebase Cloud Messaging can provide push notifications. Firebase Cloud Storage can store consented meal images when cloud processing is required.

## Delivery

GitHub Actions CI is used to check the basic repository structure whenever changes are pushed.
