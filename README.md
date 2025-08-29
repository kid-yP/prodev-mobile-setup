# 🚀 Getting Started with Expo & React Native

This guide walks you through setting up a mobile development environment, building your very first **React Native app** with Expo, and testing it on a physical device.  

---

## 🛠️ Prerequisites

Before you begin, make sure you have the following installed and ready:

- **Node.js (LTS version)**  
- **Visual Studio Code** (or your preferred editor)  
- **Expo Go App** on your Android device → [Download here](https://expo.dev/go)  
- **Windows OS** (tested setup, should work on macOS/Linux as well)  

---

## 📦 Create a New Expo App

1 Open your terminal and navigate to your project folder:
   ```bash
   cd prodev-mobile-setup
Create a new Expo project using the Expo Router template:

npx create-expo-app@latest .


Start the development server:

npx expo start


Open Expo Go on your phone and scan the QR code to run the app live on your device.

✏️ First Customization

Open the file:

app/(tabs)/index.tsx


Replace the default text with your own message:

// Original
Welcome!

// Updated
First App Created 🎉


Save, and watch your changes appear instantly in the app!

🔄 Resetting the Project

To reset the project state, run:

npm run reset-project


This will refresh the app.

After reset, a folder called app-example is created automatically.

It includes default screens and constants, acting as a fallback demo.

📂 Project Structure (After Reset)
prodev-mobile-setup/
│
├── app/                  # Main project
│   └── (tabs)/index.tsx  # Customized to show "First App Created 🎉"
│
├── app-example/          # Auto-generated demo after reset
│   ├── app/(tabs)/index.tsx
│   └── constants/Colors.tsx
│
└── README.md             # Documentation