<!-- Header -->
<div align="center">

# Hi, I'm Gayathri Kolli 👋

**Android Engineer** · Kotlin · Jetpack Compose · Personalization · System-level APIs · Clean Architecture

[![Portfolio](https://img.shields.io/badge/Portfolio-gayathrikolliportfolio.netlify.app-4A90E2?style=flat-square&logo=google-chrome&logoColor=white)](https://gayathrikolliportfolio.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gayathri--k-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gayathri-k-45666a3ab/)
[![Medium](https://img.shields.io/badge/Medium-@gayathrikolli1905-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@gayathrikolli1905)
[![Email](https://img.shields.io/badge/Email-gayathrikolli1905%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gayathrikolli1905@gmail.com)

</div>

---

I build Android apps that ship to real users. Right now I'm the sole Android engineer on the **City of Philadelphia's 311 Resident App**, a civic-reporting app I'm taking from idea to release-ready. Before that I was at **Willow Laboratories** on [Nutu Wellness](https://play.google.com/store/apps/details?id=com.willow.nutu&hl=en_US), a health app with **40K+ users**. I care about offline-first architecture, testable code, and getting the details right.

- 🏛️ Owning a public-facing government app end to end: architecture, security, accessibility, and release decisions
- 🏗️ Building production Android with **Jetpack Compose, Coroutines, Room, Hilt, KMP**
- 🎯 Interested in **behavior-driven personalization**: interest scoring, adaptive UIs, contextual ads
- 🔧 Comfortable at the system level: **LauncherApps, AppWidgetHost, ShortcutManager, HOME intent**
- 🎓 M.S. Computer Science, University of Central Oklahoma (GPA 3.89)

---

> *"The best Android code is boring at the UI layer and interesting at the domain layer."*

---

## Featured projects

### 🌈 [Prism](https://github.com/gayathrikolli11/Prism) — behavioral personalization engine for content and ads
An Android app whose entire interface is a function of user behavior. Clicks, dwell time, shares, and dismissals feed an interest-scoring engine with exponential decay, and the dominant interest drives layout, theme, hero section, content source, and contextual ad category. A Jetpack Glance widget carries the personalization to the home screen.

`Jetpack Compose` · `Room + DataStore` · `Paging 3` · `Hilt` · `Jetpack Glance` · `AdMob` · `Firebase Analytics` · `Clean Architecture`

### 🚀 [NexusLaunch](https://github.com/gayathrikolli11/NexusLaunch) — context-aware Android home screen launcher
A fully functional home screen replacement using system-level Android APIs. Built a **weighted app-ranking engine** (recency decay + launch frequency + time-of-day affinity) as a standalone `:ranking-engine` library module with a clean public API. I wrote about the algorithm in depth: [read it here](https://medium.com/@gayathrikolli1905/i-got-tired-of-my-launcher-being-dumb-so-i-replaced-it-97132b63ba05).

`LauncherApps` · `AppWidgetHost` · `ShortcutManager` · `Jetpack Compose` · `Room + Flow` · `Hilt` · `MVVM`

### More projects

- 🔍 [SmartLens](https://github.com/gayathrikolli11/SmartLens): real-time object detection with TensorFlow Lite, MobileNet, and CameraX
- 🏃 [Health Mantra](https://github.com/gayathrikolli03/health-mantra-android): exercise scheduling with conflict detection and bidirectional Health Connect sync

---

## Tech stack

```
Languages       Kotlin · Java
UI              Jetpack Compose · Material Design 3 · Jetpack Glance
Architecture    MVVM · Clean Architecture · Repository Pattern · Offline-first
System-level    LauncherApps · AppWidgetHost · ShortcutManager · HOME intent
DI              Hilt · Dagger 2
Async           Coroutines · Flow
Storage         Room · DataStore
Background      WorkManager · Paging 3
Monetization    AdMob (native ads) · Google Play Billing
APIs            Health Connect · Google Maps SDK · Firebase (Analytics, Crashlytics) · AWS S3 · Retrofit
Testing         JUnit · Mockito
Cross-platform  Kotlin Multiplatform (KMP)
```

---

## How I approach architecture

- **Offline-first by default**, not as an afterthought. If the app breaks without internet, the design is wrong.
- **Domain logic belongs in its own module.** If your use case knows what a Composable is, something has gone wrong.
- **Tests should run in milliseconds.** If a test needs an emulator, it's testing the wrong thing.
- **Let data decide.** Log the behavior, measure it, and change the product based on what people actually do.

---

## What I'm currently exploring

Server-driven UI and experimentation for personalized apps: how layouts, scoring weights, and ad placement can change per user without shipping a new build. Also Kotlin Multiplatform for sharing business logic across Android and iOS without losing native feel, and open-source contributions to [Coil](https://github.com/coil-kt/coil) (pull requests in review).

---

## Latest writing

📝 [I Got Tired of My Launcher Being Dumb. So I Replaced It.](https://medium.com/@gayathrikolli1905/i-got-tired-of-my-launcher-being-dumb-so-i-replaced-it-97132b63ba05): a deep dive into building a custom Android launcher and the ranking algorithm behind it.

---

<div align="center">
<sub>Always happy to talk Android architecture · gayathrikolli1905@gmail.com</sub>
</div>
