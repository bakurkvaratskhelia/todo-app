# Cross-Platform Todo App

A **full-stack, real-time todo application** that runs on **iOS, Android, and the Web** from a single codebase.  
Built with **React Native + Expo** on the frontend and powered by **Convex** as the backend.

This project demonstrates cross-platform development, real-time data synchronization, and modern full-stack architecture.

---

## Live Demo

<!-- If deployed, provide a link below. If using Expo, you might link to the Expo Go app or a Snack link. -->
*Coming soon!*  
<!-- Example: [Try on Expo Snack](https://snack.expo.dev/@bakurkvaratskhelia/todo-app) -->

---

## Screenshots

### Mobile
![Mobile Screenshot](screenshots/mobile.png)

### Web
![Web Screenshot](screenshots/web.png)

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

### Frontend
- React Native
- Expo

### Backend
- Convex (database, server functions, real-time sync)

### Language
- JavaScript / TypeScript

### Tooling
- Git & GitHub
- Expo CLI
- Convex CLI

---

## Project Structure

```
todo-app/
├── app/            # Main React Native portable app code
├── convex/         # Convex backend schema and serverless functions
├── screens/        # UI screens for mobile and web
├── components/     # Reusable UI components
├── public/         # Static assets (icons, splash, etc.)
├── screenshots/    # Demo screenshots (see above)
├── package.json    # Project metadata & scripts
└── ...
```

---

## Why This Project?

I built this project to explore and demonstrate modern techniques for delivering a consistent user experience across mobile and web platforms with a **single codebase**. Leveraging **Expo** and **React Native**, I focused on seamless cross-platform UI, while **Convex** allowed me to implement real-time data sync and simplified backend logic.

### Key challenges tackled:
- Ensuring truly live updates—todos appear instantly across devices
- Organizing code for easy sharing between platforms and backend
- Navigating platform-specific quirks with Expo and React Native

---

## Installation & Running Locally

Works on **Windows, macOS, and Linux**.

### Prerequisites
- **Node.js** (v18 or newer)
- **npm**
- **Git**

### 1. Clone the repository

```bash
git clone https://github.com/bakurkvaratskhelia/todo-app.git
cd todo-app
npm install
npm install -g convex
npx convex dev      # Starts Convex backend locally
npx expo start      # Launch Expo development tools (choose iOS, Android, or Web)
```

---

## License

MIT License

---

## Contact

Feel free to [open an issue](https://github.com/bakurkvaratskhelia/todo-app/issues) or contact me via  
**Email:** bakur@example.com  
  
Contributions and suggestions are always welcome!

