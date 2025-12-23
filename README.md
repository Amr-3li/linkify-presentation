# linkify

📱 Linkify

    Linkify is a modern social media app built with Flutter and Firebase, designed to connect people through posts, media sharing, and real-time messaging. The app delivers a smooth, responsive, and engaging user experience across devices.

🚀 Features

   - User Authentication – Secure sign-in & sign-up with Firebase Authentication.

   - Create & Share Posts – Support for text, images, and videos.

   - Real-Time Messaging – Instant chat powered by Firebase.

   - Responsive UI – Seamless experience on mobile & tablets.

   - State Management – Efficient and scalable using Cubit.

   - Data Storage – Integration with Supabase for structured data handling.

   - Performance Optimized – Smooth navigation and fast interactions.

🛠️ Tech Stack

   - Framework: Flutter

   - State Management: Cubit (Bloc)

   - Backend Services: Firebase (Auth, Firestore, Storage)

   - Database: Supabase

   - Local Storage: SQLite

   - Tools: Dart, Android Studio, VS Code

📸 Screenshots



📂 Project Structure

    lib/
    │── core/                     # Core modules shared across the app
    │   ├── constants/            # App constants
    │   ├── dependency_injection/ # Service locator & dependency injection setup
    │   ├── errors/               # Error handling & exceptions
    │   ├── exports/              # Barrel files for exports
    │   ├── helper/               # Utility helpers
    │   ├── services/             # Firebase, APIs, etc.
    │   ├── shared_logic/         # Shared business logic
    │   ├── utils/                # Utility functions & extensions
    │   └── widgets/              # Reusable UI components
    │
    │── Features/                 # App features (modularized)
    │   ├── add_post/             # Add new posts feature
    │   └── chat/                 # Chat / messaging feature
    │       ├── data/             # Data layer (models, repository, web services)
    │       │   ├── model/
    │       │   ├── repository/
    │       │   └── web_services/
    │       └── presentation/     # Presentation layer
    │           ├── cubit/        # State management with Cubit
    │           └── view/         # UI screens

🔮 Future Enhancements

   - Push notifications for real-time updates

   - Advanced post interactions (likes, comments, shares)

   - Story feature (images & videos)

   - Dark mode support

👨‍💻 Author

Developed by Amr Ali

GitHub: [[your-github-link]](https://github.com/Amr-3li)

LinkedIn: [your-linkedin-link]
