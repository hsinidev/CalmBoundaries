<div align="center">
# 🚀 Calmboundaries
### *Production-Ready Native Android Application built with Android Jetpack Compose*

<p align="center">
  [![Architect](https://img.shields.io/badge/Architect-Hsini%20Mohamed-0055ff?style=for-the-badge&logo=github&logoColor=white)](https://hsini.dev)
  [![Portfolio](https://img.shields.io/badge/Portfolio-hsini.dev-00c853?style=for-the-badge&logo=google-chrome&logoColor=white)](https://hsini.dev)
  [![Language](https://img.shields.io/badge/Language-Kotlin-f59e0b?style=for-the-badge)](https://github.com/hsinidev)
  [![Framework](https://img.shields.io/badge/Framework-Android%20Jetpack%20Compose-6366f1?style=for-the-badge)](https://github.com/hsinidev)
  [![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
</p>

</div>

---
## 🌟 Executive Overview

**Calmboundaries** is a high-performance, native Android application engineered with **Android Jetpack Compose** for maximum responsiveness, fluid motion, and robust state persistence.

## ⚡ Key Highlights & Capabilities

- **Reactive State Flow**: Built on modern Android architecture patterns (MVVM / MVI).
- **Material 3 Design**: Modern, accessible UI with smooth micro-interactions and dark mode.
- **Offline-First Resilience**: Robust local caching with SQLite / Room database storage.
- **Battery & Memory Optimized**: Minimal background footprint and instantaneous startup.

---
## 🏗️ Architecture & Technology Stack

- **Primary Language**: `Kotlin`
- **Framework / Runtime**: `Android Jetpack Compose`
- **Design Pattern**: Modular Clean Architecture / Domain-Driven Design
- **License**: MIT Open Source Attribution

## 📖 Deep-Dive Technical Documentation

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

---
## 🚀 Quick Start & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/hsinidev/CalmBoundaries.git
cd CalmBoundaries
```

### 2. Install Dependencies
```bash
./gradlew build
```

### 3. Launch the Application
```bash
./gradlew installDebug
```


---

## 👨‍💻 System Architect & Author

<table align="center" style="border: none; background: transparent; width: 100%;">
  <tr>
    <td align="center" width="160" style="border: none; padding: 12px;">
      <img src="https://avatars.githubusercontent.com/u/232697467?v=4" width="120" height="120" style="border-radius: 50%; box-shadow: 0 8px 24px rgba(99,102,241,0.3); border: 2.5px solid #6366f1;" alt="Hsini Mohamed" />
      <br /><br />
      <b>Hsini Mohamed</b><br />
      <sub>Morocco 🇲🇦</sub>
    </td>
    <td style="border: none; padding: 12px; vertical-align: middle;">
      <h3 style="margin-top: 0;">🚀 System Architect & Full-Stack Engineer</h3>
      <p style="font-size: 0.95rem; line-height: 1.6; color: #475569;">
        Specializing in high-performance autonomous AI systems, deterministic multi-agent swarms, enterprise cloud architecture, and modern full-stack engineering.
      </p>
      <p>
        <a href="https://hsini.dev"><img src="https://img.shields.io/badge/Portfolio-hsini.dev-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
        <a href="mailto:contact@hsini.dev"><img src="https://img.shields.io/badge/Email-contact@hsini.dev-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
        <a href="https://github.com/hsinidev"><img src="https://img.shields.io/badge/GitHub-@hsinidev-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
        <a href="https://linkedin.com/in/hsinidev/"><img src="https://img.shields.io/badge/LinkedIn-hsinidev-0077b5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
      </p>
    </td>
  </tr>
</table>

---

## 📄 License & Attribution

This project is distributed under the **MIT License**. See [`LICENSE`](LICENSE) for complete terms.

<div align="center">
  <sub>⚡ Designed, architected, and maintained with engineering precision by <b><a href="https://hsini.dev">Hsini Mohamed</a></b>.</sub>
</div>
