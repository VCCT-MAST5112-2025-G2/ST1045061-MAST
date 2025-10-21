# Chef Christoffel Menu Builder App

### 📱 MAST5112 POE — Part 2: Adding the Logic
**Developer:** John Germishuys  
**Institution:** The Independent Institute of Education (IIE)  
**Course:** MAST5112 (Mobile App and Software Development Techniques)  
**Year:** 2025

---

## 🧑‍🍳 Project Overview
This project is a React Native (Expo + TypeScript) mobile application built for **Chef Christoffel**. It forms **Part 2** of the MAST5112 Practical (POE). The app demonstrates the use of core React Native components, TypeScript logic, and in-memory data management to create a simple, interactive user interface.

The purpose of the app is to allow Chef Christoffel to **create and manage a dynamic restaurant menu** by adding dishes, specifying details, and viewing a summary of the menu.

---

## 🎯 Learning Outcomes Implemented
This project demonstrates the ability to:
- Use **core components** to create a fully featured user interface.
- Use **layouts** to position components effectively.
- Apply a **colour scheme** and simple visual design.
- Handle **text inputs** and **button presses**.
- Use **TypeScript variables** to store and manage data.
- Use **if-statements** for validation logic.
- Implement **animations** for improved user experience.
- Display data dynamically with **FlatList**.
- Navigate between states in the app (single-screen layout for Part 2).

---

## ⚙️ Features Implemented
1. **Add Dish Form**  
   Chef can enter:
   - Dish Name  
   - Description  
   - Course (Starter, Main, Dessert)  
   - Price (in Rands)

2. **Dynamic Menu List**  
   - Displays all dishes added by the chef.  
   - Shows total number of menu items.  
   - Each dish can be removed using a “Remove” button.

3. **Validation Logic**  
   - Ensures all input fields are filled before adding a dish.  
   - Checks for valid numeric price values.

4. **In-Memory Data**  
   - Menu items are stored temporarily during runtime (not hardcoded).  
   - Resets on app reload as permanent storage is not required for Part 2.

5. **Animations**  
   - New dishes fade into the list when added.

---

## 🧩 Technologies Used
- **React Native (Expo Framework)**  
- **TypeScript** for static typing and logic handling  
- **React Hooks (useState, useRef)** for state management  
- **Animated API** for simple fade-in effects  
- **FlatList** for dynamic menu rendering

---

## 🚀 How to Run the App
1. Install Expo CLI (if not already installed):
   ```bash
   npm install -g expo-cli
   ```
2. Create a new Expo TypeScript project:
   ```bash
   npx create-expo-app -t expo-template-blank-typescript ChefChristoffelApp
   ```
3. Replace the generated **App.tsx** file with the provided code.
4. Start the Expo development server:
   ```bash
   cd ChefChristoffelApp
   npx expo start
   ```
5. Open the app on:
   - **Expo Go App (Android/iOS)**, or  
   - **Web browser** via the `w` key in terminal.

---

## 🧠 Notes for Demonstration
- Data is stored in memory only and clears when the app reloads.
- Use the “Add Dish” form to dynamically update the menu list.
- Each new dish appears instantly and increases the item counter.
- The “Remove” button deletes an item from the menu list.

---

## 🎥 Video Submission
- Record a **screen capture with voice-over** explaining each feature.
- Mention how TypeScript and if-statements are used for logic.
- Export or upload the video to **YouTube (unlisted)**.

---

## 🌐 GitHub Submission
- Upload your working project to GitHub.
- Include this README file and all project files.
- Share your GitHub repository link as part of the official submission.

---

### ✅ Example Repository Structure
```
ChefChristoffelApp/
├── App.tsx
├── README.md
├── package.json
├── tsconfig.json
├── node_modules/
└── assets/
```

---

### © The Independent Institute of Education (Pty) Ltd — 2025
