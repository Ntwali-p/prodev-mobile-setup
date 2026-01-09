# prodev-mobile-setup

# 0. Mobile Development Environment Setup (Expo)

## 📌 Objective

Mobile development requires more computational resources than web development.  
To simplify development and testing, this project uses the **Expo Framework** for React Native, which allows applications to be tested directly on a physical device using **Expo Go**.

The objective of this task is to install and verify **Expo Go** on a physical mobile device and ensure the development environment is ready for upcoming projects.

---

## 🛠️ Prerequisites

The following tools were required and already installed before starting this task:

- **Node.js** (LTS version)
- **Visual Studio Code (VS Code)**
- **Operating System:** Windows / macOS / Linux
- **Physical Mobile Device** (Android or iOS)

---

## 📱 Why Expo Go?

Mobile emulators require significant system resources and frequent updates to support new device models.  

**Expo Go** provides a lightweight and cost-effective alternative by allowing developers to:

- Run React Native apps directly on a physical device
- Avoid emulator and native build configuration
- Test apps across different devices easily
- Speed up development and debugging

---

## 🚀 Expo Go Installation Steps

1. Visited the official Expo Go website:  
   👉 https://expo.dev/go

2. Selected the latest available SDK version.

3. Installed Expo Go:
   - **Android:** Google Play Store  
   - **iOS:** Apple App Store

4. Opened the Expo Go application on the device.

5. Created an Expo account and logged in successfully.

---

## 🧪 Testing the Setup

To verify the setup:

```bash
npx create-expo-app test-app
cd test-app
npx expo start
