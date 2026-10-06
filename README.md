# 🐎 Ayyanar Sweets — Premium Android App

A premium Android application for **Ayyanar Sweets**, built around the existing
Ayyanar Sweets website with a mobile-first app shell.

> Traditional Madurai Sweets • Premium Experience • Easy WhatsApp Ordering

## ✨ Features

- 🏠 Home
- 🍬 Products
- ℹ️ About
- 📞 Contact
- 💬 WhatsApp quick-order
- 🔙 Android back navigation
- 🔄 Pull-to-refresh
- ⚡ Loading indicator
- 📱 Portrait mobile layout
- 🟣 Maroon + gold luxury branding
- 🌐 Existing website integration
- 🔗 WhatsApp, phone, email and UPI external-link handling
- 🤖 GitHub Actions Android build

## 🎨 Brand

**Ayyanar Sweets**

Traditional Madurai sweets with a premium royal visual identity.

Website:

https://ayyanar-sweets.web.app/

WhatsApp:

https://wa.me/919585846061

## 🧱 Project Structure

```text
AyyanarSweetsPremiumApp/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── workflows/
│       └── android.yml
├── app/
│   ├── src/main/
│   │   ├── java/com/ayyanarsweets/app/
│   │   │   └── MainActivity.kt
│   │   ├── res/
│   │   │   ├── color/
│   │   │   ├── drawable/
│   │   │   ├── layout/
│   │   │   ├── menu/
│   │   │   ├── values/
│   │   │   └── xml/
│   │   └── AndroidManifest.xml
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── .gitignore
├── LICENSE
├── README.md
├── build.gradle.kts
├── gradle.properties
└── settings.gradle.kts
```

## 🛠️ Tech Stack

- Kotlin
- Android SDK
- AndroidX
- Material Components
- WebView
- SwipeRefreshLayout
- Gradle
- GitHub Actions

## 🚀 Open in Android Studio

1. Download or clone this repository.
2. Open the project folder in Android Studio.
3. Allow Gradle synchronization.
4. Connect an Android device or start an emulator.
5. Press **Run ▶**.

### Requirements

- Android Studio
- JDK 17
- Android SDK 35
- Internet connection for the website

## 📦 Build APK locally

```bash
./gradlew assembleDebug
```

APK output:

```text
app/build/outputs/apk/debug/app-debug.apk
```

On Windows:

```powershell
gradlew.bat assembleDebug
```

## 🤖 GitHub Actions

Every push to `main` or `master` triggers the Android build workflow.

Workflow:

```text
.github/workflows/android.yml
```

After the build completes:

**GitHub → Actions → Android Build → Artifacts**

Download:

```text
AyyanarSweets-debug-apk
```

## 🔧 Main Configuration

Website URL:

```text
app/src/main/java/com/ayyanarsweets/app/MainActivity.kt
```

Currently:

```text
https://ayyanar-sweets.web.app/
```

WhatsApp number:

```text
919585846061
```

Brand colors:

```text
app/src/main/res/values/colors.xml
```

## 🔐 Security

Do not commit:

- `local.properties`
- keystore files
- passwords
- API keys
- Firebase private credentials
- signing credentials

The included `.gitignore` already excludes common Android local and signing files.

## 🗺️ Roadmap

### Version 1.0
- [x] Premium app shell
- [x] Website integration
- [x] Bottom navigation
- [x] WhatsApp order shortcut
- [x] Back navigation
- [x] GitHub Actions build

### Version 2.0
- [ ] Native product catalogue
- [ ] Product detail screen
- [ ] Quantity selector
- [ ] Shopping cart
- [ ] Order summary
- [ ] Native WhatsApp checkout
- [ ] Product image caching
- [ ] Offline product catalogue

### Version 3.0
- [ ] Firebase Cloud Messaging
- [ ] Order status notifications
- [ ] Admin/order management
- [ ] Customer order history
- [ ] Analytics

## 📄 License

MIT License.

## ❤️ Ayyanar Sweets

Made for a premium digital experience for Ayyanar Sweets.
