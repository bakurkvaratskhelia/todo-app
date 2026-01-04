# Cross-Platform Todo App

A **full-stack, real-time todo application** that runs on **iOS, Android, and the Web** from a single codebase, built with **React Native + Expo** and powered by **Convex** as the backend.

This project demonstrates cross-platform development, real-time data synchronization, and modern full-stack architecture.

---

## Screenshots

### Mobile
![Mobile Screenshot](./screenshots/mobile.png)

### Web
![Web Screenshot](./screenshots/web.png)

---

## Features

- Cross-platform support: **iOS, Android, Web**
- Real-time data synchronization
- Create, update, and delete todos
- Shared codebase across all platforms
- Backend logic and database handled by Convex
- Clean and responsive UI

---

## Tech Stack

**Frontend**
- React Native
- Expo

**Backend**
- Convex (database, server functions, real-time sync)

**Language**
- JavaScript / TypeScript

**Tooling**
- Git & GitHub
- Expo CLI
- Convex CLI

---


---

## Installation & Running Locally

### Prerequisites (All OS)
Make sure you have installed:
- **Node.js** (v18+ recommended)
- **npm**
- **Git**

---
## Project Structure (Overview)
/app        → Application screens and components
/convex     → Backend logic and database schema
/assets     → Images and static files


1. Clone the repository
git clone https://github.com/bakurkvaratskhelia/todo-app.git
cd todo-app
2. Install dependencies
npm install
3. Install Convex CLI (if not installed)
npm install -g convex
4. Start the Convex backend
npx convex dev

This command:
Starts the backend
Initializes the database
Enables real-time synchronization
Keep this terminal running.

5. Start the Expo application

Open a new terminal and run:

npx expo start


You can now:
Run the app on Android Emulator
Run on iOS Simulator
Open in a Web Browser
Scan the QR code using Expo Go on a physical device



---


Author

Bakur Kvaratskhelia
Full-Stack JavaScript Developer
GitHub: https://github.com/bakurkvaratskhelia




