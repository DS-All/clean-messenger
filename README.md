# 📱 CleanMessenger

CleanMessenger is a modern Android messaging application built with a focus on **performance, simplicity, and real-time communication**. It supports text, image, and audio messaging with a clean UI and scalable architecture.

---

## 🚀 Features

### 💬 Messaging

* Send & receive **text messages**
* Send & receive **images**
* Send & receive **audio messages**
* WhatsApp-style chat bubbles
* Date-based message grouping

### 🧠 Smart UI

* Dynamic message rendering (text/image/audio)
* Clean Material UI design
* Dark mode support
* Smooth RecyclerView performance

### 🔍 Search System

* Search users by username
* Real-time search results
* Recent search history (saved locally)

### 👤 Profile System

* Editable profile (name, username, bio)
* Profile picture upload with cropping
* Add up to 3 custom links
* 14-day restriction on profile image updates

### 📂 Media Handling

* Upload files to Cloudflare R2
* Local caching of media
* Scoped storage support (Android 10+)
* Gallery integration

### 🔐 Messaging Controls

* Delete for me
* Delete for everyone
* Message status (sent/viewed/downloaded)

---

## 🏗️ Tech Stack

* **Language:** Java
* **Architecture:** MVC (modular approach)
* **Backend:** Firebase Firestore
* **Storage:** Cloudflare R2
* **Image Loading:** Glide
* **Media Handling:** Android Media APIs
* **UI:** Material Design 3

---

## 📁 Project Structure

```
com.cleanmessenger.app
│
├── activities/
├── adapters/
├── fragments/
├── models/
├── utils/
└── res/
```

---

## 🔧 Key Components

### 📦 Message Model

Handles:

* text
* image
* audio
* metadata (timestamp, status, deletion)

### 📦 ChatItem

* Supports mixed RecyclerView items
* Date headers + messages

### 📦 MessageAdapter

* Multi-view type adapter
* Dynamically renders:

  * text
  * image
  * audio

---

## ⚠️ Known Issues

* Audio playback currently UI-only (logic in progress)
* Some edge-case crashes under testing
* Performance optimizations ongoing

---

## 🧩 Future Improvements

* Audio playback with waveform
* Push notifications
* End-to-end encryption
* Voice/video calling
* Message reactions
* Typing indicators

---

## 👨‍💻 Developer

**Danish Shaikh**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
