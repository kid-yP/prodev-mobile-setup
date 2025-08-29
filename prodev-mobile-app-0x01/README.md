# 👋 Welcome to Your Expo App

This project was bootstrapped with **[create-expo-app](https://www.npmjs.com/package/create-expo-app)** and uses the **Expo Router** for navigation.  

With Expo, you can quickly build cross-platform apps for **Android, iOS, and the Web** — all from one codebase. 🚀  

---

## 🛠️ Getting Started

1 Install dependencies
```bash
npm install
2. Start the development server
npx expo start


Once running, you’ll see options to open the app in:

📱 Expo Go
 (quick sandbox for testing)

📱 Development build

🤖 Android Emulator

🍏 iOS Simulator

📂 Project Structure

Your source code lives in the app/ directory, which uses file-based routing:

Add a new file inside app/ → It automatically becomes a new route in your app.

Example:

app/
 ├── (tabs)/
 │    └── index.tsx   # Default tab screen
 └── _layout.tsx      # Navigation layout

🔄 Resetting the Project

If you want a clean slate, run:

npm run reset-project


This will:

Move the starter code into an app-example/ directory.

Create a fresh, empty app/ folder for you to start building your app from scratch.
