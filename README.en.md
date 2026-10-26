🇵🇱 [Polski](README.md) | 🇬🇧 **English**

# 📱 Where to Go — a Flutter App

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white) ![Riverpod](https://img.shields.io/badge/Riverpod-00B4AB)

> 🎓 Mobile track of the **Summer Challenge 2025** (*Wakacyjne Wyzwanie*) run by the **KN Solvro** student research group (Wrocław University of Science and Technology)

All summer I developed one app — **Where to Go** 🗺️, for browsing and saving places worth visiting. Every week added a new layer: state, navigation, a database, an API, CRUD. Each step lives on its own branch.

## 🪜 Steps

| | Branch | What I did |
|---|---|---|
| 1️⃣ | [`1-franciszek-pora`](../../tree/1-franciszek-pora) | List of places and a details screen, with the data layer separated from the widgets |
| 2️⃣ | [`2-franciszek-pora`](../../tree/2-franciszek-pora) | State management three ways — `InheritedWidget`, **Flutter Hooks** and **Riverpod** — plus navigation with **GoRouter** |
| 3️⃣ | [`3-franciszek-pora`](../../tree/3-franciszek-pora) | 🌗 Light/dark theme remembered in `shared_preferences`, a local **Drift** database and ❤️ favourites |
| 4️⃣ | [`4-franciszek-pora`](../../tree/4-franciszek-pora) | 🔐 Login and sign-up; fetching, adding and deleting places through a **REST API** (Dio) |
| 5️⃣ | [`5-franciszek-pora`](../../tree/5-franciszek-pora) | Full **CRUD** with editing, 🔎 search, ↕️ sorting, a favourites filter and swipe-to-delete |

## 🚀 Run it

```bash
git checkout 5-franciszek-pora
cd where_to_go
flutter pub get
dart run build_runner build --delete-conflicting-outputs
flutter run
```
