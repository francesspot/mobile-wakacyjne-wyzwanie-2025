🇵🇱 **Polski** | 🇬🇧 [English](README.en.md)

# 📱 Where to Go — aplikacja we Flutterze

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white) ![Riverpod](https://img.shields.io/badge/Riverpod-00B4AB)

> 🎓 Ścieżka mobilna **Wakacyjnego Wyzwania 2025** koła naukowego **KN Solvro** (Politechnika Wrocławska)

Przez cały kurs rozwijałem jedną aplikację — **Where to Go**, służącą do przeglądania i zapisywania miejsc wartych odwiedzenia. Co tydzień dochodziła kolejna warstwa: stan, nawigacja, baza danych, API, CRUD. Każdy etap jest na osobnej gałęzi.

## 🪜 Etapy

| # | Gałąź | Co zrobiłem |
|---|---|---|
| 1 | [`1-franciszek-pora`](../../tree/1-franciszek-pora) | Lista miejsc i ekran szczegółów, warstwa danych oddzielona od widgetów |
| 2 | [`2-franciszek-pora`](../../tree/2-franciszek-pora) | Zarządzanie stanem na 3 sposoby — `InheritedWidget`, **Flutter Hooks** i **Riverpod** — oraz nawigacja w **GoRouter** |
| 3 | [`3-franciszek-pora`](../../tree/3-franciszek-pora) | Motyw jasny/ciemny zapamiętywany w `shared_preferences`, lokalna baza **Drift** i ulubione |
| 4 | [`4-franciszek-pora`](../../tree/4-franciszek-pora) | Logowanie i rejestracja, pobieranie, dodawanie i usuwanie miejsc przez **REST API** (Dio) |
| 5 | [`5-franciszek-pora`](../../tree/5-franciszek-pora) | Pełny **CRUD** z edycją, wyszukiwanie, sortowanie, filtr ulubionych i usuwanie przesunięciem palcem |

## 🚀 Uruchomienie

```bash
git checkout 5-franciszek-pora
cd where_to_go
flutter pub get
dart run build_runner build --delete-conflicting-outputs
flutter run
```
