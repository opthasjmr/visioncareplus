# Vision Care Plus

Vision Care Plus is a comprehensive Android app designed to promote eye health, prevent common eye conditions, and provide accessible information and tools for users to maintain optimal vision.

## Features
- Guided eye care exercises (20-20-20 rule, eye rotations, etc.)
- Customizable reminders for breaks and exercises
- Library of articles and FAQs on eye health
- Basic vision self-assessment tests (Amsler grid, color blindness, visual acuity)
- Symptom checker (informative, not diagnostic)
- Progress tracking and personalized recommendations
- Dark mode and accessibility support

## Tech Stack
- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Navigation:** Bottom Navigation Bar
- **Architecture:** Modular, scalable, MVVM-ready
- **Testing:** JUnit (Android), Pytest-style stubs for logic

## Setup Instructions
1. Open the project in Android Studio (latest version recommended).
2. Let Gradle sync and build the project.
3. Run the app on an emulator or Android device (API 23+).

## Code Structure
- `app/src/main/java/com/visioncareplus/` — Main app code
  - `MainActivity.kt` — App entry point
  - `navigation/BottomNav.kt` — Bottom navigation bar
  - `screens/` — Main screen Composables (Home, Exercises, Learn, Tests, Profile)
- `tests/` — Unit/UI test stubs

## Accessibility & Best Practices
- Large text options, color contrast, and clear navigation
- Modular code, PEP8/black for Python tests, and clear documentation

---
_Disclaimer: This app is for informational/self-assessment purposes only and not a substitute for professional medical advice._ 