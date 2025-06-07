# EchoSafe

EchoSafe by Stetup, Because You Can't Be Trusted With Your Own Data™.

EchoSafe is a lightweight, private message-saving Discord bot designed to let users save, view, and manage personal notes and messages directly through Discord slash commands. It’s simple, fast, and keeps your messages local — no cloud nonsense, no ads, no leaks.

## 📦 Features
- 💾 `/save [text]` — Save a message to your personal vault.
- 📄 `/view` — View your saved messages.
- 🗑️ `/delete [id]` — Remove a saved message by its ID.
- 🔄 Auto-sync between `stetupyt` and `stetup.dev` profiles.

## 📂 Local Storage
User messages are stored locally in the `user.jsons/` folder under individual JSON files.

Example:
user.jsons/
├── messages_stetupyt.json
└── messages_stetup.dev.json

## ⚡ Setup

### 1. Install dependencies:
    ```
    npm install
    ```

### 2. Deploy slash commands:
    ```
    npm run deploy
    ```

### 3. Start the bot:
    ```
    npm start
    ```

---

# Made with ❤️ By [Stetup](https://www.github.com/stetupdev)
© 2025 EchoSafe / Stetup
