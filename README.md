# 🤖 Messenger Bot Framework (Fork Version)

A powerful and modular **Facebook Messenger Bot Framework** built with **Node.js**.  
This project includes a command system, event handlers, database support, uptime system, and dashboard-ready controllers.

---

## ✨ Features

- Modular command & event system  
- Auto uptime system  
- MongoDB & SQLite database support  
- User / Thread / Global data controller  
- Reply, Reaction & Event handlers  
- Easy configuration & customization  
- Dashboard-ready API structure  

---

## 📂 Project Structure

.
├── Main.js
├── account.txt
├── configCommands.json
├── includes/
│   ├── autoUptime.js
│   ├── custom.js
│   ├── connectDB/
│   │   ├── connectMongoDB.js
│   │   └── connectSqlite.js
│   ├── controller/
│   │   ├── dashBoardData.js
│   │   ├── globalData.js
│   │   ├── threadsData.js
│   │   ├── usersData.js
│   │   └── index.js
│   ├── handler/
│   │   ├── CheckData.js
│   │   ├── onEvent.js
│   │   ├── onReaction.js
│   │   └── onReply.js
│   └── utils/
│       └── ...
└── package.json


---

## 🔐 Login System

This bot uses **appState login** to authenticate with Facebook Messenger.

- Login logic is handled inside `Main.js`
- Session data is stored in `account.json`
- No username/password required in code

> AppState allows secure and faster login handling.

---

## ▶️ Start the Bot

Run the bot using:

```bash
node Main.js


## 🧠 Core Modules

- **Command System** – Easily extendable command architecture  
- **Event Handler** – Handles message, reaction, and reply events  
- **Database Layer** – Abstracted MongoDB & SQLite connectors  
- **Controllers** – User, thread, global & dashboard data handling  
- **Uptime System** – Keeps the bot alive automatically  

---

## 🛠 Customization

- Custom logic can be added in:
- Uptime behavior can be modified in



---

## 📊 Dashboard Ready

Structured controllers designed for easy integration with dashboards and APIs.

---

## 🤝 Contributors

Thanks to everyone who contributed to this project:

- **Original Framework Author**  
- **Fork & Enhancements** – Community Contributors  

Want to contribute?  
Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is provided for **educational and development purposes only**.

---

## ❤️ Credits

Built with **Node.js**  
