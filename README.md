# **React Native To-Do App**

![React Native](https://img.shields.io/badge/React%20Native-0.73-blue)
![Expo](https://img.shields.io/badge/Expo-Latest-green)
![Platforms](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS-lightgrey)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active-success)

This isn’t just a UI prototype—this is a real, full-stack, real-time to-do app.

✅ Works on physical devices & simulators (Android / iOS)  
✅ Everything updates instantly across users (create, complete, delete)  
✅ No native Swift / Kotlin required—just JavaScript & React Native  

---

## **🧑‍🍳 App Features Overview**

### **📝 Todos Tab**  
- ➕ Add new tasks  
- ✅ Mark as completed / uncompleted  
- 📝 Edit existing tasks  
- 🗑️ Delete tasks  
- 📊 Live progress bar at the top  

### **⚙️ Settings Tab**  
- 📈 View task stats (total, completed, remaining)  
- 🌙 Toggle Dark Mode (actually works!)  
- 🔔 Notification toggle (UI only)  
- 🔄 Auto-sync toggle (UI only)  
- 🚨 Danger Zone to delete everything  

### **🔄 Real-Time Sync**  
- All updates reflect instantly across devices  

---

## **🧠 Features**
- 🏗️ Build a mobile app using **React Native + Expo**  
- 🧭 Use both tab and stack navigation (**React Navigation**)  
- 🧱 Master core components: **View**, **Text**, **FlatList**, **ScrollView**, **TouchableOpacity**, **Switch**  
- 🌈 Style with gradients, modals, alerts, and themes  
- ⚡ Connect to a real-time backend with **Convex**  
- 🌓 Implement **Dark Mode** and local state toggles  
- 🧹 Handle deletion, editing, and real-time sync  
- 📱 Run apps on iOS, Android, or the web—no Mac needed!  

---

## **📁 .env Setup**
Create a `.env` file in the project root:  

```env
CONVEX_DEPLOYMENT=<get_it_from_convex>
EXPO_PUBLIC_CONVEX_URL=<get_it_from_convex>

🚀 Run the App
npm install
npx expo

🗄️ Run the Convex DB
Open a separate terminal and run:

npx convex dev
