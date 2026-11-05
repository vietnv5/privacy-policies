# Privacy Policy for Piano Master Studio

**Last updated:** 2026-11-05

## Introduction

**Piano Master Studio** ("we", "our", or "us"), developed by **VSoft** (`com.vsoft.pianomaster`), respects your privacy.

This application is an interactive musical instrument and rhythm learning application designed to work **offline-first** with optional cloud synchronization features.
We do **not sell or trade your personal data** to any third parties.

---

## Data Collection & Local Storage

Piano Master Studio **does not require account registration** to play songs, use the synthesizer, or practice musical instruments.

By default, all user progress and preferences, including:

* Song high scores, star ratings, and accuracy statistics
* Audio synthesizer and visual preferences (selected instrument, speed, language, guide toggles)
* Custom imported or created songs

are stored **locally on the user's device** (`localStorage` / WebView storage), unless the user explicitly chooses to enable cloud synchronization.

---

## Optional Cloud Sync (Firebase Firestore)

Piano Master Studio provides an **optional cloud synchronization feature** powered by **Google Firebase Firestore** (`moblie-485713`).

* Cloud sync is used to back up and synchronize your song progress, high scores, and custom songs across sessions or devices.
* When you sign in with Google, your game progress and custom song data are stored securely in Google Firebase Firestore under your authenticated user profile.
* The developer does not use synced musical or gameplay data for profiling, marketing, or data selling.
* You can sign out at any time from the Settings panel and continue using the application locally offline.

---

## Google Sign-In

Google Sign-In is provided as an **optional authentication method** so users can link their progress to their Google account:

* Authentication is handled securely via **Google Firebase Authentication**.
* When you sign in with Google, basic profile identifiers (such as your Firebase User ID, display name, or email address) are used solely inside the app to display your signed-in account status and associate your cloud-saved scores.
* We do not share your Google account details with any external marketing or third-party organizations.

---

## Advertising (Google AdMob)

To support free development and maintenance, the mobile version of Piano Master Studio integrates **Google AdMob** to display banner and occasional interstitial advertisements (for example, after completing a song).

* Google AdMob may use device identifiers (such as the Android Advertising ID) and coarse diagnostic information to serve ads and measure ad performance in compliance with Google Play policies.
* Users can manage or reset their Advertising ID at any time in their Android device's system privacy settings (`Settings > Google > Ads`).
* No ads are shown while actively playing a musical song on stage so your performance is never interrupted.

---

## Permissions

Piano Master Studio requests minimal device permissions necessary for operation:

### Internet & Network State (`INTERNET`, `ACCESS_NETWORK_STATE`)

Used only to:

* Synchronize progress with Firebase Firestore when online
* Authenticate via Google Sign-In when requested by the user
* Load non-intrusive advertisements via Google AdMob

### Audio Synthesis

All musical notes (Piano, Guitar, Violin, Flute) are synthesized in real time using the device's audio output. The application does **not** access your microphone or record ambient audio.

---

## Third-Party Services

Piano Master Studio uses reputable third-party services provided by Google:

* **Google Firebase Authentication & Cloud Firestore** (for optional account sign-in and score synchronization)
* **Google AdMob / Google Play Services** (for displaying in-app advertisements)

Usage of these services is governed by [Google's Privacy Policy](https://policies.google.com/privacy).

---

## Children's Privacy

Piano Master Studio is a general-audience music education and rhythm game suitable for all ages. We do not knowingly collect personal identifiable information from children under the age of 13 without parental consent. Parents or guardians who believe that their child has provided personal information may contact us so we can promptly delete it.

---

## Data Security & Account Deletion

All cloud communication between the app and Google Firebase is encrypted in transit via HTTPS/TLS.
Users who have signed in with Google can sign out or request complete deletion of their cloud-synced score data at any time by contacting us via the support email below.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. Any updates will be published on this page with an updated revision date.

---

## Contact Us

If you have any questions or requests regarding this Privacy Policy or your data, please contact **VSoft**:

**Email:** [vsoft102@gmail.com](mailto:vsoft102@gmail.com)

