# Business Card App

A simple, single-screen Android application built with Jetpack Compose to display a personal business card. This project was created as a learning exercise to practice fundamental Android development concepts, from UI layout to version control with Git.

![Business Card App Screenshot](https://i.imgur.com/uR1dOyr.png)

---

## 🚀 Key Concepts I Practiced

This project served as a hands-on lab for the following concepts:

### Jetpack Compose
* **Basic Layouts:** Understanding the fundamental difference and use cases for `Column` (for vertical arrangement), `Row` (for horizontal arrangement), and `Box` (for stacking elements).
* **Flexible Spacing with `Modifier.weight()`:** This was a key learning point. I used `Spacer` with `Modifier.weight(1f)` to create a flexible layout that pushes one block of content toward the center and another to the bottom of the screen, regardless of screen size.
* **Alignment and Arrangement:** Using `horizontalAlignment` and `verticalArrangement` to precisely position child elements within `Column` and `Row` containers.
* **Modifiers:** Applying modifiers correctly (e.g., `modifier = Modifier.padding(...)`) to change the size, padding, and layout of composables like `Image` and `Text`.
* **Theming:** Modifying the `ColorScheme` in the `ui.theme/Theme.kt` file to set a custom, app-wide background color and ensure text was readable.

### Git & GitHub
* **Complete Git Workflow:** Initializing a local repository (`git init`), staging files (`git add .`), committing changes (`git commit`), and pushing to a remote GitHub repository (`git push`).
* **Remote Management:** Linking a local repository to a GitHub remote with `git remote add origin`.
* **Troubleshooting:**
    * Solving permissions errors (`403 Forbidden`) by using a **Personal Access Token (PAT)**.
    * Clearing incorrect cached credentials on a public machine using the **Windows Credential Manager**.
    * Fixing network and proxy errors that prevented Git from connecting to GitHub.
    * Resolving `[rejected] (fetch first)` errors by resetting the remote repository for a clean push.

---

## 🛠️ Built With
* [Kotlin](https://kotlinlang.org/) - The primary programming language.
* [Android Studio](https://developer.android.com/studio) - The official IDE for Android development.
* [Jetpack Compose](https://developer.android.com/jetpack/compose) - Android's modern, declarative UI toolkit.
* [Material 3](https://m3.material.io/) - The latest version of Google's design system.
