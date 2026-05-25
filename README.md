# 📝 Notes App (Flutter + SQLite)

> A simple, fast and offline notes application built using Flutter and SQLite.

---

## ✨ Features

- 🆕 Create Notes
- ✏️ Edit Notes
- 🗑️ Delete Notes
- 🎨 Custom Note Colors
- 📅 Auto Date Stamp
- 📱 Grid UI Layout
- ⚡ Offline Storage (SQLite)

---

## 🛠️ Tech Stack

- Flutter (UI Framework)
- Dart (Programming Language)
- SQLite (Local Database)
- sqflite Package
- Path Provider

---

## 🧠 Project Concept

This app demonstrates how a real-world offline database system works in mobile apps:

- Data is stored locally using SQLite
- CRUD operations (Create, Read, Update, Delete)
- Smooth UI with real-time updates using setState
- Dialog-based input system

---

## 📂 Project Structure

lib/
├── database/
│ └── notes_database.dart
├── screens/
│ ├── notes_screen.dart
│ ├── note_card.dart
│ └── note_dialog.dart
└── main.dart
