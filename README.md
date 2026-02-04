# Taehb-Ai-Cross-Platform-Learning-App-Flutter-Firebase-
Designed and delivered a scalable assessment-first learning experience across mobile/web/desktop with Firebase backend, BLoC-driven state, bilingual RTL UI, gamification (points/leaderboard), and AI chatbot support.
# Taehb (Flutter + Firebase) — Multi-Platform Learning App

Taehb is a cross-platform Flutter application (Android, iOS, Web, Windows, macOS, Linux) built for interactive learning and assessments. The app includes authentication, quizzes/exams, results analytics, points & leaderboard, multi-language support (AR/EN), light/dark themes, and an AI chatbot integration.

## Key Features
- **Cross-platform Flutter**: Android / iOS / Web / Desktop
- **Firebase Backend**: Authentication, Firestore, (Cloud) Functions
- **State Management**: BLoC / Cubit
- **Learning & Assessment**:
  - Quizzes / Exams flow
  - Results & progress tracking
  - Points system + Leaderboard
- **AI Chatbot**: Integrated chat experience (Groq/AI service)
- **Localization**: Arabic / English + RTL support
- **Theming**: Light / Dark mode with persistent settings
- **Clean Architecture**: Models, repositories, services, reusable UI widgets

## Tech Stack
- Flutter / Dart
- Firebase (Auth, Firestore, Functions)
- BLoC / Cubit
- Localization (ARB)
- REST/HTTP integrations (AI service)

## Project Structure (High Level)
- `lib/`
  - `auth/` authentication BLoC + screens
  - `core/` themes, constants, utils, shared widgets
  - `data/` models, datasources, repositories
  - `services/` quiz/exam logic, leaderboard, chatbot service
  - `screens/` app UI pages (home, exams, results, profile, chatbot)
  - `l10n/` localization ARB files
- `firebase/` firestore rules/indexes, functions, seed data

## Setup
1. Install Flutter SDK and dependencies:
   - `flutter pub get`
2. Configure Firebase:
   - Add your Firebase project
   - Ensure `firebase_options.dart` is generated / present
3. Run:
   - `flutter run`

## Notes
- Make sure Firestore rules and indexes are deployed if required.
- Seed data can be used to populate initial questions/units.

## License
MIT (or choose your preferred license)
