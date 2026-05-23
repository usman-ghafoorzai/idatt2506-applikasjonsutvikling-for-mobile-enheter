# IDATT2506 Final Project: Mobile Todo/Shopping List App

## Overview
This project is a mobile todo/shopping list application built with `Ionic React`, `TypeScript`, and `Capacitor`.

The app supports:
- Multiple lists
- Item creation
- Item completion toggling
- Local persistence using `Capacitor Filesystem`
- Android packaging through `Capacitor`

## Context
This application was developed as part of **IDATT2506 Mobile Application Development** at **NTNU**.

It is an academic mobile app project for coursework and portfolio use, and it is **not a production-ready application**.

## Features
- Create and manage multiple todo/shopping lists
- Switch between lists using segment tabs
- Add new items to the active list
- Mark items as done/undone
- Keep completed items grouped after active items
- Persist list data locally on device storage

## Tech Stack
- `Ionic React`
- `TypeScript`
- `React`
- `Capacitor` (`@capacitor/core`, `@capacitor/android`, `@capacitor/filesystem`)
- `Vite`
- Initial test setup with `Vitest` and `Cypress`

## Project Structure
```text
idatt2506-prosjektoving/
+-- android/                # Capacitor Android project
+-- cypress/                # E2E test setup
+-- public/                 # Static assets
+-- src/
|   +-- components/         # UI components
|   +-- models/             # Type definitions
|   +-- utils/              # Filesystem persistence helpers
|   +-- App.tsx             # Main app logic/state
|   `-- main.tsx            # App entry point
+-- capacitor.config.ts
`-- package.json
```

## How to Run Locally
Install dependencies and start the development server:

```bash
npm install
npm run dev
```

Build and preview web assets:

```bash
npm run build
npm run preview
```

## How to Sync/Build Android with Capacitor
Typical Android workflow:

```bash
npm run build
npx cap sync android
npx cap open android
```

Then run the app from Android Studio on an emulator or device.

## Testing
This project includes an initial/basic test setup.

Run available checks:

```bash
npm run test.unit
npm run test.e2e
npm run lint
```

## Screenshots
No screenshots are currently committed in this repository.

## Status and Limitations
- Status: Completed as a course final project and maintained as portfolio material.
- Limitations:
  - Academic scope; not hardened for production deployment
  - No authentication or user account system
  - Local-device persistence only (no backend sync/collaboration)
  - Test setup is basic and should be expanded for broader confidence
