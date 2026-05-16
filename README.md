<!-- Header -->
<div align="center">

# Hi, I'm Gayathri Kolli 👋

**Android Engineer** · Kotlin · Jetpack Compose · System-level APIs · Clean Architecture · On-device ML

[![Portfolio](https://img.shields.io/badge/Portfolio-gayathrikolliportfolio.netlify.app-4A90E2?style=flat-square&logo=google-chrome&logoColor=white)](https://gayathrikolliportfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gayathri--k-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gayathri-k-45666a3ab/)
[![Medium](https://img.shields.io/badge/Medium-@gayathrikolli1905-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@gayathrikolli1905)
[![Email](https://img.shields.io/badge/Email-gayathrikolli1905%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gayathrikolli1905@gmail.com)

![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Android%20Engineer-22C55E?style=flat-square)

</div>

---

I build Android apps that ship to real users. Health tech, fintech, on-device ML. Previously at **Willow Laboratories** on [Nutu Wellness](https://play.google.com/store/apps/details?id=com.willow.nutu&hl=en_US), a health app with **40K+ active users**. I care about offline-first architecture, testable code, and getting the details right.

- 🏗️ Building production Android with **Jetpack Compose, Room, Coroutines, Hilt, KMP**
- 🔧 Comfortable at the system level: **LauncherApps, AppWidgetHost, ShortcutManager, HOME intent**
- 🤖 Interested in **on-device ML**: TFLite, MobileNet, real-time image analysis
- 🧪 Strong believer in unit tests that actually catch bugs, not just inflate coverage
- 🎓 M.S. Computer Science, University of Central Oklahoma (GPA 3.89)

---

> *"The best Android code is boring at the UI layer and interesting at the domain layer."*

---

## Featured projects

### 🚀 [NexusLaunch](https://github.com/gayathrikolli11/NexusLaunch) — AI-powered Android home screen launcher
A fully functional home screen replacement using system-level Android APIs. Built a **weighted app-ranking engine** (recency decay + launch frequency + time-of-day affinity) extracted as a standalone `:ranking-engine` library module with a clean public API. I wrote about the algorithm in depth — [read it here](https://medium.com/@gayathrikolli1905/i-got-tired-of-my-launcher-being-dumb-so-i-replaced-it-97132b63ba05).

`LauncherApps` · `AppWidgetHost` · `ShortcutManager` · `Jetpack Compose` · `Room + Flow` · `Hilt` · `MVVM` · `Clean Architecture`

### 🔍 [SmartLens](https://github.com/gayathrikolli11/SmartLens) — real-time object detection camera app
Real-time object detection using **TensorFlow Lite + MobileNet**, CameraX live feed, and custom View overlays. Kotlin Coroutines for background inference with zero UI jank during per-frame detection.

`TensorFlow Lite` · `MobileNet` · `CameraX` · `Kotlin Coroutines` · `Custom View`

### 🏃 [Health Mantra](https://github.com/gayathrikolli03/health-mantra-android) — exercise scheduling & Health Connect sync
Exercise scheduling with automated conflict detection for overlapping entries, one-tap resolution, and bidirectional **Google Health Connect** sync.

`Health Connect API` · `MVVM` · `Hilt` · `Room + Flow` · `Jetpack Compose` · `Material 3`

---

## Tech stack

```
Languages       Kotlin · Java
UI              Jetpack Compose · Material Design 3
Architecture    MVVM · Clean Architecture · Repository Pattern · Offline-first
System-level    LauncherApps · AppWidgetHost · ShortcutManager · HOME intent
DI              Hilt · Dagger 2
Async           Coroutines · Flow
Storage         Room · DataStore
Background      WorkManager · Paging 3
Camera & ML     CameraX · TensorFlow Lite · MobileNet
APIs            Health Connect · Google Maps SDK · Firebase · AWS S3 · Retrofit
Testing         JUnit · Mockito
Cross-platform  Kotlin Multiplatform (KMP)
```

---

## How I approach architecture

- **Offline-first by default**, not as an afterthought. If the app breaks without internet, the design is wrong.
- **Domain logic belongs in its own module.** If your use case knows what a Composable is, something has gone wrong.
- **Tests should run in milliseconds.** If a test needs an emulator, it's testing the wrong thing.

---

## What I'm currently exploring

Kotlin Multiplatform for sharing business logic across Android and iOS without sacrificing native feel. Also going deeper into on-device ML pipelines: inference, quantisation, and keeping it fast on mid-range hardware.

---

## Latest writing

📝 [I Got Tired of My Launcher Being Dumb. So I Replaced It.](https://medium.com/@gayathrikolli1905/i-got-tired-of-my-launcher-being-dumb-so-i-replaced-it-97132b63ba05) — a deep dive into building a custom Android launcher and the ranking algorithm behind it.

---

<div align="center">
<sub>Open to new opportunities and always happy to talk Android architecture · gayathrikolli1905@gmail.com</sub>
</div>
