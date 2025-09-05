# 🌐 CrashNetwork Website

This is the template website for **CrashNetwork**, made for a client of mine!  
It provides players with information about the server, live player counts, gamemodes, store links, and contact details.

---

## 🚀 Features
- 🎨 **Modern UI** with a glassy navigation bar and smooth animations  
- 🎮 **Live player count** using the [mcsrvstat.us API](https://api.mcsrvstat.us/)  
- 📋 **Click-to-copy IP** functionality for easy server joining  
- 📜 **Welcome section** with styled server description  
- 🕹️ **Game Modes showcase** with hover effects  
- 🛒 **Store section** with product previews  
- 📞 **Contact section** with email support  
- 📱 Fully **responsive** design for desktop and mobile  

---

## 🛠️ Tech Stack
- **HTML5** – Page structure  
- **CSS3** – Styling, animations, responsiveness  
- **JavaScript (Vanilla)** – Player count API, smooth scrolling, copy-to-clipboard  

---

## Status
- Not fully developed!

---

## ⚡ Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/crashnetwork-website.git
   ```
2. Open the project folder:
   ```bash
   cd crashnetwork-website
   ```
3. Open index.html in your browser (or use a live server extension in VS Code).

## 🌍 Live Player Count
The server IP is fetched via:

  ```js
  fetch(`https://api.mcsrvstat.us/2/play.crashnet.fun`)
  ```
- Displays current online players

- Shows Server Offline or Error Loading when unreachable

- Updates on page load

## 📂 Project Structure

  ```bash
  ├── img/               # Images and assets
  │   ├── Hardcore_Heart_Full.png
  │   ├── Diamond_Sword.png
  │   ├── Red_Bed.png
  │   ├── crate.jpg
  │   ├── keys.jpg
  │   └── logo.png
  ├── index.html         # Main website file
  ├── style.css          # Styles (if extracted)
  ├── README.md          # Project documentation
  ```
## 📸 Preview


## 📬 Contact
Discord: [Join My Discord Server!](https://dsc.gg/code-with-codfy)
Email: support@crashnet.fun

📜 License
This project is licensed under the MIT License.
Feel free to use and modify for your own Minecraft server website! 🎉
