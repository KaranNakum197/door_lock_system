# 🔒 Smart Door Lock System using ESP32, Firebase & Android

A smart IoT-based door locking system using **ESP32**, **Google Firebase**, and an **Android application**. Control and monitor your door from anywhere using a secure, real-time system.

## 📱 Features

- Lock/Unlock the door via Android app
- Real-time door status sync with Firebase
- Access logs stored in Firebase Realtime Database
- Manual override button for emergencies
- Internet-based remote access (Wi-Fi)

## 🛠️ Components Used

- **ESP32 Dev Board**
- **Servo Motor** (or solenoid lock)
- **Push Button**
- **Firebase Realtime Database**
- **Android App** (built with Android Studio / Kotlin/Java)
- **Optional: OLED/LED display for status**

## 🔗 System Architecture


## 🚀 Getting Started

### 1. Firebase Setup
- Go to [Firebase Console](https://console.firebase.google.com/)
- Create a project and enable **Realtime Database**
- Set rules (for testing):
  ```json
  {
    "rules": {
      ".read": "true",
      ".write": "true"
    }
  }


#define WIFI_SSID "Your_SSID"
#define WIFI_PASSWORD "Your_PASSWORD"
#define FIREBASE_HOST "your-project.firebaseio.com"
#define FIREBASE_AUTH "your_firebase_database_secret"
