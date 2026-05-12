# 🐝 Madhu-Siri: Bee-Farmer Harmony App

**Madhu-Siri** is an agriculture-focused Android application built to protect bees from pesticide spraying in nearby crop fields. The app connects **beekeepers** and **farmers** through real-time hive location sharing and spray alerts.

Beekeepers can pin hive locations, farmers can send a **"Spraying Today"** alert, and all beekeepers within a **2 km radius** are notified so they can close their hives for **4 hours**, helping save pollinators and support sustainable agriculture.

---

## 📌 Project Domain

**Android App Development using GenAI - Agriculture**

Focus Area:
- Apiculture
- Pollinator protection
- Sustainable farming
- Farmer-beekeeper communication
- Biodiversity support

---

## 🚜 Problem Statement

Beekeeping is a useful side-income source for rural communities, but bees are often harmed when pesticides are sprayed in nearby crop fields.

The main issues are:

- Beekeepers do not know when nearby farmers are spraying pesticides.
- Farmers do not know where active bee hives are located.
- Bees are exposed during active foraging hours.
- Bee deaths reduce honey production and crop pollination.
- Lack of communication affects biodiversity and crop yield.

---

## 💡 Solution

Madhu-Siri acts as a **Bee-Farmer Harmony platform**.

The app allows:

- Beekeepers to pin hive locations.
- Farmers to view nearby hive areas.
- Farmers to send spray alerts before pesticide use.
- Beekeepers within 2 km to receive alerts.
- Beekeepers to close hives for 4 hours.
- Users to access bee-friendly pesticide and spraying tips.

---

## ✨ Key Features

### ✅ Must-Have Features

- User login screen
- Beekeeper/Farmer role selection
- Hive Map screen
- Spray Alert system
- 2 km radius hive detection
- Hive closure recommendation for 4 hours
- Hive health tracking
- Honey production log
- Owner-only hive location editing
- Bee-friendly pesticide tips
- Clean nature/honey themed UI

### 🌱 Good-to-Have Features

- Firebase Authentication
- Firebase Firestore database
- Firebase Cloud Messaging notifications
- Google Maps live location support
- GenAI-based local language advisory
- Weather-based spray timing suggestions
- Offline hive records
- Admin monitoring dashboard
- Hive inspection image upload

---

## 📱 App Screens

### 1. Login Screen
Users log in using valid credentials before accessing the app.

### 2. Role Selection
Users choose their role:
- Beekeeper
- Farmer

### 3. Hive Map
Displays pinned hive locations and active spray alert areas.

### 4. Spray Alert
Farmers can tap **Spraying Today** before pesticide spraying.

### 5. Health Dashboard
Beekeepers can track:
- Hive strength
- Honey production
- Hive location
- Health notes

### 6. Bee-Friendly Tips
Provides safe pesticide and spraying guidelines to protect bees.

---

## 🛠️ Technologies Used

### Frontend

- Kotlin
- Jetpack Compose
- Material 3
- Android Studio

### Maps

- Google Maps SDK for Android
- Google Maps Compose

### Backend / Planned Backend

- Firebase Authentication
- Firebase Firestore
- Firebase Cloud Messaging

### Core Logic

- Haversine distance formula
- 2 km radius matching
- Role-based user flow
- Owner-only hive editing logic

### Live Web Demo

- HTML
- CSS
- JavaScript
- Node.js local server

### Build Tools

- Gradle
- Android Emulator
- Android phone testing

---

## 🧠 GenAI Usage

GenAI is planned as an advisory layer for:

- Safe pesticide practice suggestions
- Local language farmer guidance
- Hive health summary generation
- Bee-friendly spraying recommendations
- Awareness content for sustainable agriculture

GenAI will support decision-making but will not replace verified agricultural or pesticide guidelines.

---

## 🏗️ System Architecture

```text
User
 |
 |-- Login
 |
 |-- Role Selection
 |      |-- Beekeeper
 |      |-- Farmer
 |
 |-- Android Frontend
 |      |-- Hive Map
 |      |-- Spray Alert
 |      |-- Health Dashboard
 |      |-- Bee-Friendly Tips
 |
 |-- Backend Services
        |-- Firebase Auth
        |-- Firestore Database
        |-- Firebase Cloud Messaging
        |-- Cloud Function for 2 km alert matching


# Madhu-Siri: Bee-Farmer Harmony App

Madhu-Siri is an agriculture-focused Android application built to protect bees from pesticide spraying in nearby crop fields. The app connects beekeepers and farmers through hive location sharing, spray alerts, hive health tracking, and bee-friendly guidance.

Beekeepers can pin hive locations, farmers can send a **Spraying Today** alert, and beekeepers within a **2 km radius** can be notified to close hives for **4 hours**.

---

## Project Domain

**Android App Development using GenAI - Agriculture**

Focus areas:
- Apiculture
- Pollinator protection
- Sustainable farming
- Farmer-beekeeper communication
- Biodiversity support

---

## Problem Statement

Beekeeping is a useful side-income source, but bees are often harmed when pesticides are sprayed in nearby crop fields.

Main problems:
- Beekeepers do not know when nearby farmers are spraying pesticides.
- Farmers do not know where active bee hives are located.
- Bees are exposed during active foraging hours.
- Bee deaths reduce honey production and crop pollination.
- Lack of communication affects biodiversity and crop yield.

---

## Solution

Madhu-Siri acts as a **Bee-Farmer Harmony platform**.

The app allows:
- Beekeepers to pin hive locations.
- Farmers to view nearby hive areas.
- Farmers to send spray alerts before pesticide use.
- Beekeepers within 2 km to receive alerts.
- Beekeepers to close hives for 4 hours.
- Users to access bee-friendly pesticide and spraying tips.

---

## Key Features

## Must-Have Features

- User login screen
- Beekeeper/Farmer role selection
- Hive Map screen
- Spray Alert system
- 2 km radius hive detection
- Hive closure recommendation for 4 hours
- Hive health tracking
- Honey production log
- Owner-only hive location editing
- Bee-friendly pesticide tips
- Clean nature/honey themed UI

## Good-to-Have Features

- Firebase Authentication
- Firebase Firestore database
- Firebase Cloud Messaging notifications
- Google Maps live location support
- GenAI-based local language advisory
- Weather-based spray timing suggestions
- Offline hive records
- Admin monitoring dashboard
- Hive inspection image upload

---

## Technologies Used

## Frontend

- Kotlin
- Jetpack Compose
- Material 3
- Android Studio

## Maps

- Google Maps SDK for Android
- Google Maps Compose

## Backend / Planned Backend

- Firebase Authentication
- Firebase Firestore
- Firebase Cloud Messaging
- Cloud Functions

## Core Logic

- Haversine distance formula
- 2 km radius matching
- Role-based user flow
- Owner-only hive editing logic

## Live Web Demo

- HTML
- CSS
- JavaScript
- Node.js local server

## Build Tools

- Gradle
- Android Emulator
- Android phone testing

---

## App Screens

## 1. Login Screen

Users log in using valid credentials before accessing the app.

Demo credentials:

```text
Email: himashree.22ece@cambridge.edu.in
Password: Hima@2118
