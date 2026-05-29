# 🌊 RepoFlow

**RepoFlow** is a lightweight, responsive, and elegant open-source GitHub repository management client, crafted entirely with native Kotlin and Jetpack Compose. Seamlessly track public and private repositories, explore comprehensive commit histories, and manage your GitHub projects from one central hub.

---

## ✨ Features

- **GitHub Authentication**: Securely log in using Personal Access Tokens (PAT).
- **Dashboard Hub**: Get an instant overview of your GitHub profile and repository statistics.
- **Repository List**: Browse through your public and private repositories seamlessly.
- **Detailed Insights**: Tap into any repository to view language breakdowns, descriptions, and current availability status.
- **Repository Explorer**: Explore files and repositories, opening individual code files to inspect their contents right on your mobile device.
- **Responsive Adaptive Design**: Looks fantastic and uses window size classes to stay responsive across phones, foldable devices, and tablets.
- **Modern Jetpack Compose Architecture**: Built with Material Design 3 guidelines for a clean, accessible mobile experience.

## 🛠 Tech Stack & Architecture

- **Language:** Kotlin
- **UI Toolkit:** Jetpack Compose & Material 3
- **Architecture:** MVVM (Model-View-ViewModel) + StateFlow + Clean Architecture guidelines
- **Networking:** Ktor / Retrofit, OkHttp, Moshi
- **Image Loading:** Coil
- **Local Database (Optional):** Room

## 🚀 Getting Started

### Prerequisites

Make sure you have Android Studio installed, or the Google AI Studio Android build ecosystem!

### Configuration

To fetch data from GitHub securely, RepoFlow operates using GitHub Personal Access Tokens.

1. Head to your [GitHub Settings - Personal Access Tokens (Classic)](https://github.com/settings/tokens).
2. Generate a new token with the `repo` scope securely granted.
3. Once running, paste this token directly into RepoFlow's login screen.

### Building Locally

```bash
git clone https://github.com/your-username/repoflow.git
cd repoflow
./gradlew assembleDebug
```

## 🎨 Theme & Accessibility

RepoFlow boasts a beautiful default Cosmic Dark/Ocean Blue adaptive theme taking advantage of Material 3's core dynamic and structured properties map. Adaptive icons and edge-to-edge content layers make sure it fits right at home on modern Android 12+ OS constraints. 

## 👨‍💻 Developer & Support

For issues or questions, you can contact the developer:
- Telegram: [@Vann759](https://t.me/Vann759)
- Email: ditoelvan2@gmail.com 

---

Made with ❤️ using Jetpack Compose + AI Studio.
