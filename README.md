# Samura's MTG Life Counter

A high-performance, real-time synchronized life counter for Magic: The Gathering (Commander/EDH), powered by Firebase.

## 🚀 Features

*   **Real-time Sync**: Uses Cloud Firestore to keep life totals and counters in sync across all devices instantly.
*   **High Performance**: Optimized with Firebase Hosting CDN and cache settings for a "lightning-fast" experience.
*   **Simple Setup**: Designed as a "plug-and-play" template.

## 🛠️ How to Use

1.  **Firebase Configuration**
    Open `firebaseConfig.js` and replace the placeholder values with your own Firebase project credentials.
2.  **Member List**
    Edit `members.txt` and add your playgroup's nicknames (one per line).
3.  **Deployment**
    Deploy the app to your Firebase Hosting with a single command:
    ```bash
    npx firebase deploy
    ```

## 📄 License
This project is open-source. Feel free to fork and customize it for your own playgroup!
