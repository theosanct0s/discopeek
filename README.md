<h1 align="center">👀 DiscoPeek</h1>

<p align="center">
  <b>Explore Discord profiles in seconds!</b><br>
  <sub>Fast, lightweight, and completely free</sub>
</p>

<p align="center">
  <a href="https://github.com/theosanct0s/discopeek/stargazers">
    <img src="https://img.shields.io/github/stars/theosanct0s/discopeek?style=for-the-badge" alt="Stars"/>
  </a>
  <a href="https://github.com/theosanct0s/discopeek/issues">
    <img src="https://img.shields.io/github/issues/theosanct0s/discopeek?style=for-the-badge" alt="Issues"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"/>
  </a>
</p>

---

## ⚡ Features

- 🔍 Search profiles by **Discord ID**  
- 🖼️ View **avatar** and **banner**  
- ⬇️ Download images with one click  
- 🌐 Support for **English and Portuguese**  
- 💻 **Lightweight, modern, and responsive** interface  

---

## 🛠 Technologies

- HTML, CSS, and pure JavaScript  
- Font Awesome for icons  
- Translation system via JSON files  

---

# 🚀 How to Use

DiscoPeek requires a **backend** to work properly using **Node.js** and the `server.js` file.  
Simply opening `index.html` directly in a browser will cause errors when fetching translations or making backend requests.

---

## 💻 Steps to Run the Site

1. Make sure **Node.js** is installed.
2. Open the **terminal** in the project's root folder.
3. Install dependencies:
    ```bash
    npm install
    ```
4. Start the server:
    ```bash
    npm start
    ```
    ⚠️ By default, the site will run at [http://localhost:3000](http://localhost:3000).

5. Open your browser and go to **http://localhost:3000**.

Now the frontend can communicate properly with the backend, and all site features will work correctly.

---

## 🔑 Setting Up the Bot Token

1. Create a file named `.env` in the root folder.
2. Add the following line inside `.env`:
    ```env
    DISCORD_BOT_TOKEN=your_discord_bot_token_here
    ```
    ⚠️ **Important:** The bot **does not need to be in any server**. It only needs to exist to provide the token.

---

## 🤖 How to Create a Discord Bot

1. Go to the [Discord Developer Portal](https://discord.com/developers/applications).
2. Click **"New Application"** and give it a name.
3. Go to the **Bot** tab.
4. In the **Token** section, click **"Reset Token"** to generate a new token.
5. Copy the token and paste it into your `.env` file as `DISCORD_BOT_TOKEN`.
- ⚠️ **Attention:** Do **not** share this token with anyone. Anyone with access can control your bot.
6. You **do not need to invite** the bot to any server. Just creating it is enough.

---

### 💡 Important Tip

**Do not** open `index.html` directly (e.g., by double-clicking).  
**Always** use the local server (`localhost`) to avoid errors with `fetch` requests and **CORS** issues.

---

## 🌍 Current Translations

- English  
- Português do Brasil

Want to contribute more translations? Open a [discussion](https://github.com/theosanct0s/discopeek/discussions) — your help is greatly appreciated! ❤️

---

### 🗳️ Feedback

> If you find any bugs, please open an issue in this repository with details.
