🌐 Server-Based Social Media App

A cross-platform social media application built with Flutter and Firebase, featuring real-time user interactions, cloud-based data management, and a clean, responsive interface.

This project demonstrates full-stack mobile development skills — from authentication and database structure to UI design and deployment.

🚀 Features

🔐 User Authentication — Secure sign-up, login, and logout using Firebase Auth.

🗂️ Cloud Firestore Integration — Real-time storage and retrieval of user posts, comments, and likes.

👤 User Profiles — Editable display names, profile info, and ability to delete posts.

💬 Interactive Posts — Users can create posts, like, and comment instantly with cloud synchronization.

🎨 Modern UI/UX — Responsive layout, gradient scaffold design, and smooth page transitions built in Flutter.

☁️ Scalable Backend — Powered by Firebase for seamless data synchronization and scalability across platforms.

🧠 Tech Stack
Category	Tools / Frameworks
Frontend	Flutter (Dart)
Backend	Firebase Cloud Firestore
Authentication	Firebase Auth
Development Tools	VS Code · Android Studio · Git · GitHub
Platforms	Android · iOS (potential) · Web (optional build)
🧩 App Architecture

The project follows a Model-View-Controller (MVC) inspired structure for maintainability:

lib/
├── main.dart               # Entry point
├── screens/                # UI pages (login, feed, profile, etc.)
├── widgets/                # Reusable UI components
├── services/               # Firebase services (auth, db)
├── models/                 # Data models for users/posts
└── utils/                  # Helpers, constants, and themes

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/Sekki-vi/ServerBasedApp.git
cd ServerBasedApp

2️⃣ Install Dependencies
flutter pub get

3️⃣ Set Up Firebase

Create a Firebase project at Firebase Console
.

Enable Authentication → Email/Password.

Create a Cloud Firestore database.

Download the google-services.json file and place it inside your app’s android/app/ directory.

(Optional) For iOS, download and add GoogleService-Info.plist in /ios/Runner/.

4️⃣ Run the App
flutter run

📸 Screenshots (Optional)
Login	Feed	Profile
(Add screenshots here)	(Add screenshots here)	(Add screenshots here)
🔍 Example Features in Action

Feed Page: Displays all posts in real time using Firestore snapshot listeners.

Profile Page: Fetches user-specific data and displays their posts.

Post Creation: Uploads text content and attaches metadata (timestamp, author ID).

Like/Comment: Uses document references for quick interaction updates.

🧪 Future Improvements

Add image upload support for posts.

Integrate Firebase Cloud Storage.

Add friend/follow system.

Implement dark mode and user notifications.

Add AI-based content recommendations (future ML integration).

👨‍💻 Author

Kenyon Jones
Computer Science Graduate & Software Developer passionate about building scalable, data-driven, and creative apps.

📧 Email: kenyonj4@gmail.com

💻 GitHub: @Sekki-vi

🏷️ License

This project is released under the MIT License. You’re free to use, modify, and distribute it for personal or educational purposes.
