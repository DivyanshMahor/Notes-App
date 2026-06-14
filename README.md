<h1 align="center">📝 Notes App (Flutter + SQLite)</h1>
<p align="center"><b>A simple, fast, offline notes app built with Flutter and SQLite</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

> Create, edit, delete, and manage your notes — fully offline, with a clean UI.

---

## ✨ Features

- 🆕 Create notes
- ✏️ Edit notes
- 🗑️ Delete notes
- 🎨 Custom note colors
- 📅 Auto date stamp
- 📱 Grid UI layout
- ⚡ Offline storage with SQLite

---

## 🛠️ Tech Stack

- Flutter (UI framework)
- Dart (programming language)
- SQLite (local database)
- sqflite package
- path_provider

---

## 🧠 Project Concept

This app demonstrates how a real-world offline database system works in mobile apps:

- Data is stored locally using SQLite
- Full CRUD operations (Create, Read, Update, Delete)
- Smooth UI with real-time updates using `setState`
- Dialog-based input system

---

## 📂 Project Structure

```
lib/
├── database/
│   └── notes_database.dart   # SQLite database setup & queries
├── screens/
│   ├── notes_screen.dart     # Main grid view of notes
│   ├── note_card.dart         # Individual note widget
│   └── note_dialog.dart       # Add/edit note dialog
└── main.dart
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/DivyanshMahor/Notes-App.git
```

### 2. Install dependencies
```bash
flutter pub get
```

### 3. Run the app
```bash
flutter run
```

---


## 💡 What I Learned

- Local data persistence using SQLite in Flutter
- Implementing full CRUD operations
- Building a dynamic grid UI
- Managing dialogs and form input

---

## 🔥 Future Improvements

- [ ] Search and filter notes
- [ ] Pin / favorite notes
- [ ] Categories or tags for notes
- [ ] Cloud sync / backup

---

## 👨‍💻 Developer

**Divyansh Mahor** — Flutter Developer
🔗 [LinkedIn](https://www.linkedin.com/in/divyansh-mahor/) · [GitHub](https://github.com/DivyanshMahor)

---

<p align="center">⭐ If you found this project useful, consider giving it a star!</p>
