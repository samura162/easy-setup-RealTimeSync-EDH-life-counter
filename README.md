# Samura's MTG Life Counter

A high-performance, real-time synchronized life counter for Magic: The Gathering (Commander/EDH), powered by Firebase.

# 🚀 Features

* **Real-time Sync**: Uses Cloud Firestore to keep life totals and counters in sync across all devices instantly.
* **High Performance**: Optimized with Firebase Hosting CDN for a "lightning-fast" experience.

---

# 🛠️ Setup Instructions

## 1. Prepare Firebase Project
* Go to the [Firebase Console](https://console.firebase.google.com/).
* Create a new project and add a **Web App**.
* Copy the `firebaseConfig` object values from the settings.

## 2. Configure the App
* Open `firebaseConfig.js` in this repository.
* Replace the placeholder values with your actual Firebase credentials.
* **Note:** Ensure the syntax is correct (watch out for trailing commas in JS objects).

## 3. Install Tools & Login
In your terminal (e.g., GitHub Codespaces), run the following commands:
```bash
### Install Firebase CLI
`npm install -g firebase-tools`

### Login (Use --no-localhost flag if you are on Codespaces)
`firebase login --no-localhost`

## 4. Deploy to Web
Link your local environment to your Firebase project and publish:

```bash
### Link your project ID (Replace [your-project-id] with yours)
`firebase use [your-project-id]`

### Upload to Firebase Hosting
`firebase deploy`

# 📋 Customization
Member List
Edit members.txt and add your playgroup's nicknames (one name per line). After editing, simply run the deploy command again:

```bash
`firebase deploy`

# 📄 License
This project is open-source. Feel free to fork and customize it for your own playgroup!
