# ✨ MyFlix - The Ultimate Cinema Experience

MyFlix is a premium, high-performance media streaming ecosystem built with Flutter and Firebase. It features a stunning glassmorphic UI, a robust 7-day trial system, deep-linking capabilities, and a comprehensive Admin management suite.

---

## 📱 Main App Features

### 🎬 1. Advanced Media Discovery
*   **Dual-Category Browsing**: Dedicated sections for Movies and TV Shows.
*   **Deep Detail Screens**: Full overviews, cast lists, trailers, and intelligent recommendations.
*   **Seasons & Episodes**: Intuitive episode picker with season tracking for TV series.
*   **Global Search**: Instant search functionality across the entire TMDB library.
*   **Interactive Photo Gallery**: Fullscreen image slider in detail pages supporting pinch-to-zoom gestures, copying direct image URLs, and downloading high-resolution backdrops to local storage.

### 💎 2. Premium User Experience
*   **7-Day Free Trial**: Automated trial activation for all new users.
*   **Glassmorphic UI**: A state-of-the-art design language using dark mode, smooth gradients, and blurred surfaces.
*   **Integrated Watchlist with Offline Sync**: Saves favorites locally inside a Hive database for instant offline access, and auto-syncs with Cloud Firestore on authentication updates.
*   **Ad-Block Shield Player**: Custom WebView sandbox layer containing AT_DOCUMENT_START script injections, window object sandboxing, network request interception, and CSS overrides to block popups, tracking, and ads.
*   **Multi-Server Drawer**: Integrates VidLink, AutoEmbed, VidSrc, MoviesAPI, and Videasy for instant source switching in-player.
*   **Sinhala Subtitle Aggregator**: Direct integration with the SinhalaSub Worker, letting users search, download, unzip, and apply Sinhalese subtitle tracks (filtered to PirateLK) directly from the player.

### 🔗 3. Advanced Connectivity
*   **Deep Linking & Sharing**: Copy links or share via social apps using a custom glassmorphic `ShareBottomSheet`. Custom domain links (`myflix.techlasiya.com`) automatically open the app and route to specific movies or shows.
*   **Real-time Live Chat**: A built-in customer support channel with markdown formatting (bold, italic, code, links) and image attachment uploads.

---

## 🛡️ Admin Suite (`MyFlix Admin`)

A high-control dashboard designed for project owners to manage the user ecosystem in real-time.

*   **Real-time Analytics**: Live counters for Active, Awaiting, Expired, and Blocked users.
*   **Universal Search**: Effortlessly find users and support chats by name or email.
*   **Manual Subscription Control**: Calendar-based tool to manually extend or modify user expiry dates.
*   **Status Management**: One-tap approval, blocking, or manual expiry triggers.
*   **Support Chat**: Integrated real-time customer support chat featuring Markdown and picture uploads.
*   **OneSignal Push Console**: Comprehensive composer to schedule and broadcast notifications with custom action buttons (up to 3), FreeImage.host media uploads, and template manager (Firestore integration) optimized via `ValueNotifier` and debounced validation.

---

## 🌐 Web Fallback Ecosystem
*   **Premium Landing Page**: A gorgeous web presence for non-app users.
*   **Smart Redirects**: Automatically guides mobile users to download the app releases.
*   **AssetLinks Verified**: Fully configured for Android App Links support.

---




## 📄 License
© 2026 MyFlix Cinema. All rights reserved.
