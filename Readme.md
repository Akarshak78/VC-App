# 🎥 VC-App — Video Conferencing & Chat App

A powerful video conferencing and real-time chat app built with **Agora App Builder**, now enhanced with custom **😊 Emoji Reactions** and *(coming soon)* 🗳️ **Polls**!

---

## ✨ Features

- ✅ **Video & Audio Calls** — Crystal clear calls powered by Agora SDK.
- ✅ **Real-time Messaging (RTM)** — Instant chat for all participants.
- ✅ **Emoji Reactions** — React to any message with your favorite emoji!
- ✅ **Cross-Platform** — Works on Web, Android, iOS, and Electron.
- ✅ **Modular Architecture** — Easy to customize and extend.
- 🔜 **Polls Feature** — Create polls during calls and vote live!

---

## 📂 Project Structure

```bash
chatapp/
├── android/ # Native Android code
├── ios/ # Native iOS code
├── electron/ # Electron app for desktop
├── bridge/ # Native bridges
├── src/ # React Native source
│ ├── components/ # Shared UI components
│ │ ├── EmojiReaction/ # Emoji Reactions
│ │ ├── Poll/ # Polls (upcoming)
│ ├── atoms/ # State management (Recoil)
│ ├── pages/ # Screens/pages
│ ├── rtm-events/ # RTM event listeners
│ ├── utils/ # Helpers & utilities
├── App.tsx # App entry point
```
## 🚀 Getting Started

Get up and running with **VC-App** in just a few steps! 🎉

### 1️⃣ Clone the repository
🔗 Clone the repo and navigate into the project folder.
```bash
git clone https://github.com/Akarshak78/VC-App.git
cd VC-App
```


### 2️⃣ Install dependencies
📦 Install all required packages using `npm` or `yarn`.
```bash
npm install
yarn install
```

### 3️⃣ Run the app
🚀 Run the project for Web, Android, or iOS.

# 🌐 Run for Web
```bash
npm start
```

# 🤖 Run for Android
```bash
npx react-native run-android
```

# 🍏 Run for iOS
```bash
npx react-native run-ios
```

## 😊 Emoji Reactions

Interact with messages in real-time! 🎉

1️⃣ Click the 😊 emoji icon next to any chat message.
2️⃣ Choose your favorite emoji from the picker.
3️⃣ Your reaction is sent instantly via Agora RTM.
4️⃣ Everyone in the channel sees your reaction update in real-time!

---
## 🗳️ Polls (Coming Soon!)

- Create live polls during video calls
- Vote in real-time
- See results update instantly
