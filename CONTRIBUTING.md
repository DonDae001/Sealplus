# Contributing

Thank you for your interest in contributing to Seal Plus!

Seal Plus is an open-source Android application built on the foundation of [Seal](https://github.com/JunkFood02/Seal) and powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp), a command-line program written in Python that supports downloading media from [1000+ websites](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md).

Before submitting an issue or pull request, please search the existing issues first, including closed issues. If you can't find a duplicate, feel free to open a new issue using the appropriate issue template.

**Issues that do not use the appropriate template or do not contain enough information may be closed without further investigation.**

For questions, discussions, or ideas, you can join the Seal Plus community.


## 🐛 Bug Report

When submitting a bug report, please provide **enough information to reproduce the problem**.

Depending on the issue, this may include:

- Your device model
- Android version
- Seal Plus version
- Steps to reproduce the problem
- Relevant settings or options
- The URL involved, if applicable
- Screenshots or screen recordings
- Relevant logs or error messages

Please make sure to fill out all relevant fields in the issue template.

The more information you provide, the easier it is to investigate and fix the problem.


## 💡 Feature Request

Before submitting a feature request, please search the existing issues first to see whether the feature has already been requested.

When suggesting a new feature, please explain:

- What you would like to add or change
- What problem it would solve
- How you expect it to work
- Any examples or mockups that may help explain the idea

Seal Plus aims to remain a simple and focused GUI for yt-dlp. Not every feature request will necessarily be implemented.

For functionality already supported by yt-dlp, please also check whether it can be achieved through the existing options or Custom Command Mode before requesting a new dedicated GUI option.


## 🔀 Pull Request

If you wish to contribute code directly, please make sure your changes are related to an existing issue when appropriate, or open an issue first to discuss larger changes.

Before submitting a pull request:

1. **Fork** the repository.
2. **Clone** your fork.
3. **Create** a separate branch for your changes.
4. **Make** your changes.
5. **Test** your changes thoroughly.
6. **Commit** your changes with a clear message.
7. **Push** your branch to your fork.
8. **Open** a Pull Request with a detailed description.

Please keep pull requests focused on a specific change whenever possible.

When submitting a pull request, include:

- A clear description of what was changed
- The reason for the change
- How the changes were tested
- Screenshots or recordings for UI changes, when applicable
- Any known limitations or issues


## 🌱 New Contributors

New to the project? Welcome!

You don't need to be an experienced Android developer to contribute. You can start by looking through the [existing issues](https://github.com/MaheshTechnicals/Sealplus/issues) and finding something that interests you.

Issues that are small in scope can be a good way to become familiar with the codebase.

If you are unsure about an issue or need clarification, don't hesitate to ask before starting work.


## 🤝 Contributing to Seal Plus

We welcome contributions of all kinds. Whether you're a developer, designer, translator, tester, or regular user, there are many ways to help improve Seal Plus.


### 🌍 Translations

Help make Seal Plus accessible to users around the world.

Translations are managed through [Hosted Weblate](https://hosted.weblate.org/projects/seal/).

You can contribute by adding new translations or improving existing ones.

[![Translation Status](https://hosted.weblate.org/widgets/seal/-/strings/horizontal-auto.svg)](https://hosted.weblate.org/engage/seal/)


### 💻 Code Contributions

#### Getting Started

1. **Fork** the repository.
2. **Clone** your fork:

   `git clone https://github.com/YOUR_USERNAME/Sealplus.git`

3. **Create** a feature branch:

   `git checkout -b feature/amazing-feature`

4. **Make** your changes.
5. **Test** your changes thoroughly.
6. **Commit** with a clear message:

   `git commit -m "Add amazing feature"`

7. **Push** your branch:

   `git push origin feature/amazing-feature`

8. **Open** a Pull Request with a detailed description.


#### Development Environment

The project currently uses:

- Android Studio
- JDK 17 or later
- Android SDK
- Gradle 9.5.1
- Kotlin 2.3.21

The project currently targets Android API 37, with a minimum supported API level of 24.

To build the project:

```bash
./gradlew assembleRelease
````

For a debug build:

```bash
./gradlew assembleDebug
```

On Windows, you can use:

```powershell
.\gradlew.bat assembleRelease
```

or:

```powershell
.\gradlew.bat assembleDebug
```

### 📋 Contribution Guidelines

> [!IMPORTANT]
> Before contributing, please make sure your changes follow the project's existing code style and conventions.
>
> When opening a pull request, include a clear description of your changes and explain how you tested them.
>
> For bug reports and feature requests, please use the appropriate issue templates.

### 🏗️ Technology Stack

| Component         | Technology                | Version    |
| ----------------- | ------------------------- | ---------- |
| **Language**      | Kotlin                    | 2.3.21     |
| **UI Framework**  | Jetpack Compose           | 2026.05.01 |
| **Architecture**  | MVVM + Clean Architecture | -          |
| **Build System**  | Gradle (KTS)              | 9.5.1      |
| **Minimum SDK**   | Android 7.0               | API 24     |
| **Target SDK**    | Android 17                | API 37     |
| **Database**      | Room                      | 2.8.4      |
| **Async**         | Kotlin Coroutines         | 1.11.0     |
| **Networking**    | OkHttp                    | 4.12.0     |
| **Image Loading** | Coil 3                    | 3.4.0      |
| **DI**            | Koin                      | 4.2.1      |

## 🎨 UI Contributions

Seal Plus uses Jetpack Compose for its user interface.

When making UI changes:

* Follow the existing design and visual style.
* Make sure layouts work across different screen sizes.
* Consider both light and dark themes where applicable.
* Reuse existing components when possible.
* Include screenshots or recordings in your pull request when appropriate.

For larger UI changes, please explain the reasoning behind the change in your pull request.

## 🧪 Testing

Please test your changes before opening a pull request.

When possible, test on multiple Android versions and device configurations.

If your changes cannot be tested on multiple devices, mention the device and Android version you tested on in your pull request.

Make sure that changes to one part of the application do not unintentionally break existing functionality.

## 📝 Commit Messages

Please keep commit messages clear and descriptive.

Good examples:

```text
Fix download progress display
Add gradient theme option
Update yt-dlp
Fix subtitle selection
```

Avoid vague commit messages such as:

```text
stuff
changes
fix
update
```

## 🏗️ Building From Source

Fork the repository and clone your fork:

```bash
git clone https://github.com/YOUR_USERNAME/Sealplus.git
cd Sealplus
```

Open the project in Android Studio and allow Gradle to synchronize.

You can then build a debug version with:

```bash
./gradlew assembleDebug
```

Or build a release version with:

```bash
./gradlew assembleRelease
```

On Windows:

```powershell
.\gradlew.bat assembleDebug
```

or:

```powershell
.\gradlew.bat assembleRelease
```

## ❤️ Thank You

Whether you report a bug, improve a translation, contribute code, test a change, or suggest an idea, thank you for helping improve Seal Plus!

Every contribution is appreciated.
