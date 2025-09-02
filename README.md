<h1>DevCircle</h1>


DevCircle is an Android application designed to foster a vibrant community of programmers. It enables developers to share the latest tech trends, showcase their projects, network with peers, and get AI-powered assistance to solve coding problems and analyze algorithms.

---

<h3>✨ Key Features</h3>

Trend Sharing & Discovery: Stay updated with the latest domain trends by browsing and sharing insightful articles and resources. Discover new technologies and best practices shaping the industry.

Project Showcase: Display your recent development work to receive feedback and inspire the community. Share code snippets, demos, and details to highlight your skills.

1:1 Developer Networking: Connect with like-minded developers, make friends, and expand your professional network. Explore profiles, view portfolios, and initiate conversations to collaborate.

AI-Powered Chatbot Assistance: Get instant help with coding doubts through an intelligent chatbot integrated with the OpenAI API. It provides solutions, detailed algorithm explanations, and generates code snippets in multiple programming languages.

Seamless Engagement: Enjoy a smooth experience with features like real-time notifications, offline access to content, and a responsive UI designed for high engagement.

---

<h3>🛠️ Technical Implementation</h3>

This app is built with modern Android development practices to ensure scalability, maintainability, and a great user experience.

Language: Kotlin

Architecture: Model-View-ViewModel (MVVM) for a clean separation of concerns, testability, and streamlined data management.

Dependency Injection: Dagger Hilt for efficient and scalable management of dependencies across the application.

Database:

Room DB for robust offline caching and local data persistence, supporting 20+ items per session.

Firebase Realtime Database for seamless cloud synchronization.

Networking: Retrofit for efficient API communication.

Asynchronous Operations: Kotlin Coroutines to manage 10+ async flows, ensuring non-blocking UI and smooth performance.

UI: Jetpack Compose (or XML - choose one) with RecyclerView for efficient list rendering.

---

<h3>Screenshots</h3>

Login/Register UI
<p align="left">
<img width="45%" height="738" alt="login screen" src="https://github.com/user-attachments/assets/1f032e7d-cbd4-48d7-942a-bd3a8f45da60" /> <img width="45%" height="738" alt="login screen 2" src="https://github.com/user-attachments/assets/973683b9-9427-43cf-8866-00507879b1d0" />
</p>

DashBoard
<p align="left">
  <img width="403" height="827" alt="image" src="https://github.com/user-attachments/assets/5cdb86bc-8b58-4810-9b76-9c260e45e4ec" />
</p>

User-Profile
<p align="left">
  <img width="406" height="824" alt="image" src="https://github.com/user-attachments/assets/b12a29fe-9c71-4820-8f51-2ed1af5b8087" />
</p>

Chatbot
<p align="left">
  <img width="45%" height="784" alt="image" src="https://github.com/user-attachments/assets/34a2bb52-79c0-477b-814d-840d0333518f" />
  <img width="45%" height="790" alt="image" src="https://github.com/user-attachments/assets/770f1ca7-8923-4483-ba02-6ef5422d8437" />
</p>

---

<h3>Key Technologies:</h3>

OpenAI API: Integrated to support 50+ Data Structures and Algorithms (DSA) problems with explanations and multi-language code output.

Firebase Cloud Messaging (FCM): Implemented for real-time notifications to keep users engaged.

Glide: For efficient image loading and caching.

---

<h3>📊 Impact & Highlights</h3>

Engineered a full-featured community app using modern MVVM architecture and Jetpack Navigation.

Integrated the OpenAI API to create an intelligent assistant capable of explaining complex algorithms and generating code, significantly enhancing learning and problem-solving for users.

Implemented a seamless chat interface and user profiles with offline support using Room DB and Coroutines.

Optimized the user experience with image caching (Glide) and real-time notifications (FCM).

---

<h3>🔮 Future Enhancements</h3>

Integration of video playback for project demos using ExoPlayer.

Adding community forums and dedicated Q&A sections.

Implementing a gamification system with badges and rewards for active users.
