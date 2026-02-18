# 🌿 Hapi — Plant Growth Tracking App

> Making plant care simple, organized, and enjoyable.

Hapi is a mobile application that helps users identify plant species, manage their personal garden, and stay on top of care routines through structured checklists and reminders. Built as a collaborative student project, Hapi combines intuitive design with practical backend architecture to create a seamless plant care experience.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📸 **Photo-Based Plant Identification** | Identify plant species using image-based API integration |
| 🪴 **Personal Garden Dashboard** | Maintain a digital inventory of all your plants in one place |
| ✅ **Custom Care Checklists** | Track watering, fertilizing, repotting, and other tasks |
| 🔔 **Reminders & Notifications** | Stay consistent with personalized plant care schedules |
| 📈 **Growth Tracking** | Monitor plant progress over time |

---

## 🏗️ Tech Stack

### Backend
- **Python** — Core application logic
- **Flask** — REST API development
- **PostgreSQL** — Relational database

### Frontend
- Mobile UI built from **Figma** wireframes
- Integrated with backend REST APIs

### Tools & Integrations
- **Git & GitHub** — Version control
- **Third-party Plant Identification API**
- **Weather API** *(planned)*

---

## 🧠 Motivation

Many people enjoy owning plants but struggle to consistently care for them due to busy schedules or lack of knowledge. Hapi was created to centralize identification, tracking, and reminders into one intuitive application — making plant care feel approachable, structured, and rewarding.

---

## 👥 Team

Developed collaboratively by a student team, with coordinated frontend and backend development under structured project management.

---

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.


## Backend Docker Usage Guide

This guide explains how to build, run, and manage the backend using Docker Compose.

### Prerequisites
- Install [Docker](https://www.docker.com/get-started) and [Docker Compose](https://docs.docker.com/compose/).
- Clone the backend repository

### Run containers 
- Build the contianers first
```bash
docker-compose build
```
- Run the containers
```bash
docker-compose up
```
- NOTE: Each time you make a change in the backend code, be sure run the above two commands for the changes to be reflected after stopping the containers

- Stop Containers
```bash
docker-compose down
```

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
