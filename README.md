# CalmBoundaries - Smart Screen-Time Blocker & Mindfulness Catalyst

> Transform screen-time friction into immediate mental restoration.

**Digital Wellness / Screen Time / Productivity** built with Kotlin and modern Android development standards.

---

## 📖 How It Works

This application is built following **Clean Architecture**, **MVVM / MVI pattern**, and **Offline-First** principles.

### Architecture & System Modules
- **`:app` Module**: Application initialization, Hilt module graphs, dynamic provider bindings.
- **`:core_ui` Module**: Wellness design tokens (Warm Sand, Soft Sage, Earth Terracotta), custom path interpolators, and physical spring animations.
- **`:feature_blocker` Module**: AccessibilityService binder, UsageStats crawler, WindowManager overlay controller, and target blacklist repository.
- **`:feature_wellness` Module**: Sensor listener hooks, accelerometer change vector calculators, custom breathing pacer canvas, and unlock listeners.
- **`:feature_stats` Module**: Custom canvas charts (splines, bar charts, streak calendars), focus metrics, and historical logs.
- **`:feature_pro` Module**: Google Play Billing 6.x repository, subscription verification logic, dynamic comparison tables, and paywall layouts.

### Required Android Permissions
- `android.permission.SYSTEM_ALERT_WINDOW (Essential for drawing blocking overlays over external applications)`
- `android.permission.PACKAGE_USAGE_STATS (Required for tracking foreground package transitions if Accessibility is offline)`
- `android.permission.BIND_ACCESSIBILITY_SERVICE (Crucial for high-speed, instant app block triggering)`
- `android.permission.FOREGROUND_SERVICE (Required to maintain persistent app blocking states under SDK 33-34 rules)`
- `android.permission.POST_NOTIFICATIONS (To fire daily mindfulness prompts and notification logs)`
- `android.permission.INTERNET (For processing Google Play Billing, loading AdMob ads, and syncing databases)`

---

## 📱 How to Use

### 1. App Interception Engine
High-fidelity, low-latency app tracking system running in a persistent background architecture.

### 2. System Window Overlay
Draw the blocking layer securely over designated blacklisted target apps.

### 3. Wellness Mini Games


### 4. Analytics And Progress Dashboard
Visualize focus trends and successful mindful micro-interventions.

### 5. Admob Monetization Layer



---

## 🚀 Key Features

- **App Interception Engine**: High-fidelity, low-latency app tracking system running in a persistent background architecture.
- **System Window Overlay**: Draw the blocking layer securely over designated blacklisted target apps.
- **Wellness Mini Games**: 
- **Analytics And Progress Dashboard**: Visualize focus trends and successful mindful micro-interventions.
- **Admob Monetization Layer**: 

---

## 🛠️ Tech Stack & Architecture

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose (Material Design 3)
- **Architecture**: Clean Architecture + MVVM / MVI
- **Local Storage**: Room Database & DataStore
- **Async Operations**: Kotlin Coroutines & StateFlow
- **Build System**: Gradle Kotlin DSL
- **Min SDK**: 26 | **Target SDK**: 34

---

## 💻 Getting Started

### Prerequisites
- Android Studio Ladybug (2024.2.1+) or newer
- JDK 17+
- Android SDK 34+

### Building & Running
1. Clone the repository:
   ```bash
   git clone https://github.com/hsinidev/CalmBoundaries.git
   cd CalmBoundaries
   ```
2. Open the project in Android Studio.
3. Sync Gradle dependencies and run on an Android device or emulator.

---

## 📬 Contact & Support

Created and maintained by **Hsini**.

- **Website**: [hsini.dev](https://hsini.dev)
- **Email**: [contact@hsini.dev](mailto:contact@hsini.dev)
- **GitHub**: [@hsinidev](https://github.com/hsinidev)

---

© 2026 [hsini.dev](https://hsini.dev). All rights reserved.
