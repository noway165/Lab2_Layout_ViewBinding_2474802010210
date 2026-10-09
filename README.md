# Lab 2 – Flat XML Layouts & ViewBinding

- **Student:** Tăng Thoại Lâm
- **Student ID:** 2474802010210
- **Class:** 72ITSE30603
- **Course:** Mobile Application Programming
- **Tech:** Kotlin, ConstraintLayout, ViewBinding
- **Package:** `vn.edu.vlu.lab2`

## Description
The app has two screens: **Login** and **User Profile**. The whole UI uses a flat ConstraintLayout hierarchy and ViewBinding (no `findViewById`). All strings live in `strings.xml`, with an English version in `values-en`.

## How to run
1. Open the project in Android Studio and wait for Gradle Sync to finish.
2. Run it on an emulator (Shift + F10).
3. Sign in with: `sv01@vlu.edu.vn` / `123456`.

## Features
- Login input validation:
  - Empty fields: shows a "missing data" message.
  - Invalid email format: shows an email error.
  - Password shorter than 6 characters: shows a password error.
  - Valid input: shows "Login successful" and opens the Profile screen (simulated authentication, no server call).
- Profile screen with a 1:1 avatar, name, role, three info rows (Email, Student ID, Class) and two equally sized buttons (Edit, Log out).
- Level 1 exercise: a "Forgot password?" link that shows a Toast, and an English translation in `values-en`.
- Both screens are wrapped in a `ScrollView`, so they stay scrollable in landscape.

## Screenshots

### Login screen
![Login](docs/screenshots/login.png)

### Profile screen
![Profile](docs/screenshots/profile.png)

### Landscape
![Landscape](docs/screenshots/landscape.png)

### Layout Inspector
![Layout Inspector](docs/screenshots/layout_inspector.png)
