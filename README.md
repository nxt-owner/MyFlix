# ✨ MyFlix - The Ultimate Cinema Experience

MyFlix is a premium, high-performance media streaming ecosystem built with Flutter and Firebase. It features a stunning glassmorphic UI, a robust 7-day trial system, deep-linking capabilities, and a comprehensive Admin management suite.

---

## 📱 Main App Features

### 🎬 1. Advanced Media Discovery
*   **Dual-Category Browsing**: Dedicated sections for Movies and TV Shows.
*   **Deep Detail Screens**: Full overviews, cast lists, trailers, and intelligent recommendations.
*   **Seasons & Episodes**: Intuitive episode picker with season tracking for TV series.
*   **Global Search**: Instant search functionality across the entire TMDB library.

### 💎 2. Premium User Experience
*   **7-Day Free Trial**: Automated trial activation for all new users.
*   **Glassmorphic UI**: A state-of-the-art design language using dark mode, smooth gradients, and blurred surfaces.
*   **Integrated Watchlist**: Save your favorite movies and shows for later viewing.
*   **High-Performance Player**: Seamless video playback with support for movies and episodic content.

### 🔗 3. Advanced Connectivity
*   **Deep Linking**: Share specific movies or shows using your custom domain (`myflix.techlasiya.com`). Links automatically open the app and navigate to the correct page.
*   **OneSignal Push Notifications**: Real-time engagement with users through direct push messaging.

---

## 🛡️ Admin Suite (`MyFlix Admin`)

A high-control dashboard designed for project owners to manage the user ecosystem in real-time.

*   **Real-time Analytics**: Live counters for Active, Awaiting, Expired, and Blocked users.
*   **Universal Search**: Effortlessly find users and support chats by name or email.
*   **Manual Subscription Control**: Calendar-based tool to manually extend or modify user expiry dates.
*   **Status Management**: One-tap approval, blocking, or manual expiry triggers.
*   **Support Chat**: Integrated glassmorphic chat interface to communicate with users directly.

---

## 🌐 Web Fallback Ecosystem
*   **Premium Landing Page**: A gorgeous web presence for non-app users.
*   **Smart Redirects**: Automatically guides mobile users to download the app releases.
*   **AssetLinks Verified**: Fully configured for Android App Links support.

---

## 🛠️ Technical Stack
*   **Framework**: Flutter (Dart)
*   **State Management**: Riverpod (Real-time streams & providers)
*   **Navigation**: GoRouter (Deep-link & path-parameter support)
*   **Backend**: Firebase (Auth & Firestore)
*   **Notifications**: OneSignal SDK
*   **Local Storage**: Shared Preferences (Watchlist & Local State)
*   **API**: TMDB (The Movie Database)

---

## 🚀 Getting Started

1.  **Clone the Repo**: `git clone https://github.com/nxt-owner/MyFlix.git`
2.  **Install Dependencies**: `flutter pub get`
3.  **Setup Firebase**: Ensure `google-services.json` is in `android/app/`.
4.  **Run Application**: `flutter run`

---

## 📁 Project Structure
*   `lib/core`: Routing, Themes, and Constants.
*   `lib/models`: Data structures and JSON serialization.
*   `lib/providers`: Riverpod state management logic.
*   `lib/screens`: All UI screens (Home, Detail, Player, Admin).
*   `lib/services`: Firebase, Watchlist, and OneSignal services.

---

## 📄 License
© 2026 MyFlix Cinema. All rights reserved.
