[Polski](README.md) | **English**

# From Zero to Flutter Developer

A mobile development course from the **KN Solvro** student research group's Summer Challenge (*Wakacyjne Wyzwanie*). Over the course, participants build **Where to Go** (`where_to_go/`) — a Flutter app for browsing and saving places worth visiting.

## My solutions

Each list is on its own branch, named `{list_number}-franciszek-pora`. The `main` branch contains the course materials.

| List | Branch | What I built |
|------|--------|--------------|
| 1 | [`1-franciszek-pora`](../../tree/1-franciszek-pora) | Home screen with a list of places and a details screen; data layer separated from the widgets |
| 2 | [`2-franciszek-pora`](../../tree/2-franciszek-pora) | State management in three versions — `InheritedWidget`, Flutter Hooks and **Riverpod** — plus navigation with **GoRouter** |
| 3 | [`3-franciszek-pora`](../../tree/3-franciszek-pora) | Light/dark theme saved with `shared_preferences`, a local database and favourites |
| 4 | [`4-franciszek-pora`](../../tree/4-franciszek-pora) | Connecting to the course REST API with **Dio**: login and registration, fetching, adding and deleting places |
| 5 | [`5-franciszek-pora`](../../tree/5-franciszek-pora) | Full **CRUD** (including editing), **search**, **sorting**, a favourites-only filter and swipe-to-delete |

The latest version of the app is on `5-franciszek-pora`. To run it:

```bash
git checkout 5-franciszek-pora
cd where_to_go
flutter pub get
dart run build_runner build --delete-conflicting-outputs
flutter run
```

## Course structure and schedule

The course was designed as an intensive 7-week programme that combines regular learning with a practical final project.

* **Total duration:** 7 weeks.
* **Topic modules:** 5 weeks spent on weekly task lists.
* **Final project:** 2 weeks for building the final project independently.
* **Regular meetings:** weekly "Lightning Talks" sessions (20+ minutes) covering key topics, followed by Q&A.

## Requirements

* basic knowledge of object-oriented and functional programming

## Contents

* List 0 (Dart and the environment).
Dart syntax, installing the Flutter SDK, IDE and emulator/device.
* List 1 (Flutter basics).
Stateless/Stateful widgets, layout, a list of places and a details screen. Asset generation and UI polishing — optional.
* List 2 (State and navigation).
Flutter Hooks, Riverpod, GoRouter.
* List 3 (Local data and theme).
shared_preferences, light/dark theme, a local database (READ + favourites).
* List 4 (API and authentication).
HTTP/JSON, login and registration, connecting the list of places and favourites to the API.
* List 5 (Filtering and CRUD).
CREATE/EDIT/DELETE, filtering, searching and sorting. Photo upload — optional.

## Project

The culmination of the course is an intensive two-week sprint. The goal is to design and code a fully functional app on your own, which consolidates the knowledge gained and becomes the centrepiece of your portfolio. The topic and scope of the project must first be discussed with and approved by the course leader.

## Course participation rules

To keep the course well organised and communication effective, all participants must follow these rules:

* **Communication and support:** Discord is the official communication channel. It is the right place to get help and discuss any problems, questions or doubts about the material.

* **Working in Git:** Work on the tasks on a separate Git branch named `{list_number}-{first_name}-{last_name}`.

* **Submitting tasks for review:** Submit finished tasks by opening a Pull Request on GitHub. The Pull Request title must follow the pattern `{list_number}-{first_name}-{last_name}`, and the description should include screenshots of the UI you built. The CI/CD pipeline linked to the Pull Request must pass — all its steps must be green.

* **Order of tasks:** The task lists (modules) must be completed in chronological order. Completing and passing a list is required before starting the next one.

* **Deadlines:** Each task list has a deadline set by the course leader. If you expect to be late, you must let the course leader know in advance and give the reason.
