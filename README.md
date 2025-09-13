# 🌐 CrashNetwork Website

This is the template website for **CrashNetwork**, made for a client of mine!  
It provides players with information about the server, live player counts, gamemodes, store links, and contact details.

---

## 📑 Table of Contents
- [🚀 Features](#-features)
- [📂 Project Structure](#-project-structure)
- [📜 License](#-license)
- [⚠️ Note](#️-note)

---

## 🚀 Features
- 🎨 **Modern UI** with a glassy navigation bar and smooth animations  
- 🎮 **Live player count** using the [mcsrvstat.us API](https://api.mcsrvstat.us/)  
- 📋 **Click-to-copy IP** functionality for easy server joining  
- 📜 **Welcome section** with styled server description  
- 🕹️ **Game Modes showcase** with hover effects  
- 🛒 **Store section** with product previews  
- 📞 **Contact section** with email support 

---

## 🛠️ Tech Stack
- **HTML5** – Page structure  
- **CSS3** – Styling, animations, responsiveness  
- **JavaScript (Vanilla)** – Player count API, smooth scrolling, copy-to-clipboard  

---

## Status
- Not fully developed!
  - Store not developed.
  - might break for smaller screens!

---

## ⚡ Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/CodeWithCODFY/CrashNetwork.git
   ```
2. Extact the file.
3. Open the project folder:
   ```bash
   cd crashnetwork-main
   ```
4. Change [your_erver_ip], [your_server_name] etc. to your name, server ip etc.
5. The default theme is red. You can change it to your liking.
6. Open index.html in your browser (or use a live server extension in VS Code).

## 🌍 Live Player Count
The server IP is fetched via:

  ```js
  const serverIP = "[your_ip]"; // Replace with your IP
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
  ├── style.css          # Styles 
  ├── README.md          # Project documentation
  ```
## 📸 Preview
<img width="1920" height="1000" alt="image" src="https://github.com/user-attachments/assets/c795ce77-4fe1-43f1-934e-12096ea3390d" />


## 📬 Contact
Discord: [Join My Discord Server!](https://dsc.gg/code-with-codfy)

Email: rishav.codfy2013@gmail.com

## 📜 License
This project is licensed under the MIT License.
Feel free to use and modify for your own Minecraft server website! 🎉
