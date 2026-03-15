# 💬 Private Chat System (Free Hosting)

🎓 **Educational Project**

---

## 🎥 Tutorial Video

📺 Watch the full tutorial here:
👉 https://anonfilesnew.com/s/FHF8OHpHSGQ

Follow the tutorial step-by-step to properly set up the chat system using **Firebase + GitHub Pages**.

---

## ⚠️ Disclaimer

🚫 This project is created **only for educational and learning purposes**.
📚 It is meant to help students understand how a **private chat system works using Firebase and GitHub hosting**.

❗ **Please do NOT misuse this project** for illegal, harmful, or unethical activities.
The creator is **not responsible for any misuse** of this project.

---

## 🚀 Setup Guide

Follow these steps to run the project using **Firebase + GitHub Pages**.

---

### 🔹 1. Create Firebase Project

1️⃣ Go to Firebase Console
👉 [https://console.firebase.google.com/](https://console.firebase.google.com/)

2️⃣ Login with your Google account.

3️⃣ Click **Create New Project / App**.

---

### 🔹 2. Enable Realtime Database

1️⃣ Open your project dashboard.
2️⃣ Go to **Build → Realtime Database**.
3️⃣ Click **Create Database**.
4️⃣ Select **Start in Test Mode** and click **Next**.

5️⃣ Open **Rules** tab and replace the code with:

```json
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```

6️⃣ Click **Publish**.

---

### 🔹 3. Get Firebase Web Configuration

1️⃣ Go to **Project Settings**.
2️⃣ Open the **General** tab.
3️⃣ Scroll down to **Your Apps** section.
4️⃣ Click the **Web (</>) icon**.
5️⃣ Enter an **App Nickname** and register the app.

📌 After setup you will see your **Firebase configuration code** like:

* apiKey
* databaseURL
* projectId
* appId

⚠️ **Do not share your Firebase configuration with others.**

---

### 🔹 4. Upload Project to GitHub

1️⃣ Login to **GitHub**.
2️⃣ Create a **New Repository**.
3️⃣ Upload the provided **index.html** file.

---

### 🔹 5. Edit Firebase Configuration

1️⃣ Open **index.html** in your repository.
2️⃣ Paste your Firebase configuration values:

* apiKey
* databaseURL
* projectId
* appId

3️⃣ Save and commit the changes.

---

### 🔹 6. Enable GitHub Pages

1️⃣ Go to **Repository Settings**.
2️⃣ Open **Pages** under **Code and Automation**.
3️⃣ Change **Branch** from `None` to `Main`.
4️⃣ Click **Save**.

---

### 🔹 7. Get Your Website URL

⏳ Wait around **30–45 seconds**.
🔄 Refresh the page.

🌐 GitHub will generate your **Live Website URL**.

🎉 Your **Private Chat System** is now ready!

---

## 📢 Important Notice

📷 **Image Upload Limit:**
Only images **smaller than 1MB** can be sent in the chat. Larger images may not upload properly.

🚪 **Exit Button Feature:**
When you click the **Exit button** in the web app, all chat data stored in the database will be **automatically deleted**.

💡 If you want **permanent storage or advanced database features**, you may consider **purchasing Firebase Console services or upgrading your database plan**.

---

## 🛠 Technologies Used

💻 HTML
🔥 Firebase Realtime Database
🌍 GitHub Pages (Free Hosting)

---

## 👨‍💻 Credits

⭐ **Project By:** MAXMENTOR
📢 **Telegram:** [https://t.me/maxmentor](https://t.me/maxmentor)

🙏 If you like this project, please **follow the Telegram channel for more free projects and updates.**

🚀 Thank you for supporting!
