# IDATT2506 Mobile Application Development (NTNU)

## About
This repository is a course archive for **IDATT2506 Mobile Application Development** at NTNU.

It contains:
- One main project in `IDATT2506-ProsjektOving/idatt2506-prosjektoving/`
- Several Android/Kotlin exercise folders

Each folder is a separate course assignment with its own scope and setup.

## Main Project
The main project is located in:

`IDATT2506-ProsjektOving/idatt2506-prosjektoving/`

It is an `Ionic React` + `TypeScript` + `Capacitor` mobile todo/shopping list app with:
- Multiple lists
- Item completion toggling
- Local persistence via `Capacitor Filesystem`
- Android packaging through `Capacitor`

For setup, features and project-specific details, see the project README:

[`IDATT2506-ProsjektOving/idatt2506-prosjektoving/README.md`](IDATT2506-ProsjektOving/idatt2506-prosjektoving/README.md)

## Folder Overview
| Folder | Description |
|---|---|
| `IDATT2506-ProsjektOving` | Final project folder (Ionic React/TypeScript/Capacitor app) |
| `Oving1` | Intro `Jetpack Compose` UI task (menu/dropdown and logging) |
| `Oving2_a` | Random number provider using implicit intents and activity results |
| `Oving2_b` | Arithmetic quiz app that uses values from `Oving2_a` |
| `Oving3` | Friend list app with `Spinner`, `GridView`, and edit flow |
| `Oving4` | Fragment-based master/detail layout with rotation handling |
| `Oving5` | Networked number-game client using `Coroutines` and `HttpURLConnection` |
| `Oving6_Client` | TCP chat client app |
| `Oving6_Server` | TCP chat server app |
| `oving7` | `Jetpack Compose` film app with `Room`, `DataStore`, and navigation |

## Technologies
- `Kotlin`
- `Android SDK`
- `Jetpack Compose`
- `Fragments` and XML layouts
- `Coroutines`
- `Intents` and `Activity Result API`
- `HttpURLConnection`
- `Socket` / `ServerSocket`
- `Room`
- `DataStore`
- `Navigation Compose`
- `Ionic React`
- `TypeScript`
- `Capacitor`
- `Vite`

A short overview of all exercises is available here:

[`docs/exercises.md`](docs/exercises.md)

## Repository Structure
```text
IDATT2506-Prosjekter/
+-- IDATT2506-ProsjektOving/
|   `-- idatt2506-prosjektoving/   # main project
+-- Oving1
+-- Oving2_a
+-- Oving2_b
+-- Oving3
+-- Oving4
+-- Oving5
+-- Oving6_Client
+-- Oving6_Server
`-- oving7
```

## Notes
- This repository is a collection of course assignments, not one single app.
- Setup and run instructions can differ between folders.
