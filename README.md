# linkify (source code in private repo github)

📱 Linkify

    Linkify is a modern social media app built with Flutter and Firebase, designed to connect people through posts, media sharing, and real-time messaging. The app delivers a smooth, responsive, and engaging user experience across devices.
---
## Demo Video
https://github.com/user-attachments/assets/e1d80207-5cef-4db3-bd48-b5a8398601cc

---
## 🚀 Features

- **User Authentication**  
  Secure sign-in and sign-up using Firebase Authentication.

- **Post Creation & Sharing**  
  Create and share posts with support for text, images, and video content.

- **Real-Time Messaging**  
  Instant one-to-one messaging powered by Firebase real-time capabilities.

- **Responsive User Interface**  
  Optimized layouts ensuring a consistent experience across mobile phones and tablets.

- **State Management**  
  Scalable and maintainable architecture using Cubit (Bloc).

- **Data Management**  
  Structured data handling with Supabase integration.

- **Performance Optimization**  
  Smooth navigation and fast interactions with optimized app performance.

---

## 🛠️ Tech Stack

- **Framework:** Flutter  
- **Programming Language:** Dart  
- **State Management:** Cubit (Bloc)  
- **Backend Services:** Firebase (Authentication, Firestore, Cloud Storage,database)  
- **Database:** data storage  
- **Local Storage:** Sharedprefrence 
- **Development Tools:** Android Studio, Visual Studio Code
- **Clean Code**

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


LinkedIn: [[LinkedIn]](https://www.linkedin.com/in/amr-ali1/)
