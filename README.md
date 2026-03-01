# AppLock Pro — Privacy Policy

**Effective Date:** March 1, 2026
**Developer:** NextGenVerse Solutions
**Contact:** nextgenversesolutions@gmail.com

---

## 1. Introduction

AppLock Pro is an app locking application that protects your apps using PIN, password, pattern, or biometric authentication. This Privacy Policy explains what data we collect, how we use it, and your rights.

---

## 2. Data We Collect & Store

### 2.1 Data Stored Locally on Your Device

All the following data is stored **only on your device** and is never uploaded to our servers:

| Data | Purpose |
|------|---------|
| List of locked apps (package names) | To know which apps to protect |
| Your PIN / password / pattern (encrypted) | Authentication credential |
| Security question & answer | Account recovery |
| App settings (theme, language, auto-relock, etc.) | User preferences |
| Intruder photos (JPEG, stored in app-private folder) | Failed unlock attempt evidence |
| Intruder log (timestamp, app name, failed attempt) | Security history shown to you |

### 2.2 Data We Do NOT Collect

- We do **not** collect your name, email, or any personal identity
- We do **not** upload your photos, PINs, or locked app list to any server
- We do **not** read the content of your locked apps
- We do **not** record your screen or keystrokes

---

## 3. Permissions & Why We Need Them

| Permission | Why We Need It |
|-----------|----------------|
| **Usage Access (PACKAGE_USAGE_STATS)** | To detect which app is open so we can show the lock screen |
| **Draw Over Other Apps (SYSTEM_ALERT_WINDOW)** | To display the lock screen on top of protected apps |
| **Camera** | To capture a photo of anyone who fails to unlock your app (Intruder Selfie feature — you can disable this) |
| **Biometric / Fingerprint** | To allow fingerprint unlock as an alternative to PIN |
| **Boot on Startup (RECEIVE_BOOT_COMPLETED)** | To automatically restart the protection service after your device reboots |
| **Foreground Service** | To run the app monitoring service continuously in the background |
| **Notifications (POST_NOTIFICATIONS)** | To show a persistent notification while the protection service is running (required by Android) |
| **Read Media (Images/Videos)** | To display your photos/videos in the secure Vault feature |
| **Vibrate** | For haptic feedback on wrong unlock attempts |
| **Device Administrator** | To prevent AppLock Pro from being uninstalled without your PIN (optional — you can disable this) |

---

## 4. Intruder Selfie Feature

When the **Intruder Selfie** feature is enabled:
- The front camera automatically captures a photo after multiple failed unlock attempts
- The photo is saved **only on your device** in a private folder
- Photos are visible only to you in the Security section of the app
- Photos are **never uploaded** anywhere
- You can disable this feature anytime in Settings → Security

---

## 5. Third-Party Services

AppLock Pro uses the following third-party services. Each has its own privacy policy.

### 5.1 Google Firebase

We use Firebase for:
- **Firebase Analytics** — Anonymous usage analytics (which screens are visited, app version, language). No personal data.
- **Firebase Crashlytics** — Crash reports to help us fix bugs. Includes device model, Android version, and crash logs.
- **Firebase Remote Config** — To remotely configure app features without requiring an app update.
- **Firebase Cloud Messaging (FCM)** — To send push notifications.

Firebase Privacy Policy: https://firebase.google.com/support/privacy

### 5.2 Google AdMob

We display ads using **Google AdMob**. AdMob may collect:
- Device identifiers (Advertising ID)
- IP address (approximate location)
- Usage data for personalized ads (only with your consent via the consent dialog)

AdMob Privacy Policy: https://policies.google.com/privacy

### 5.3 Ad Mediation Networks

| Network | Privacy Policy |
|---------|---------------|
| **Meta Audience Network (Facebook)** | https://www.facebook.com/privacy/policy |
| **AppLovin MAX** | https://www.applovin.com/privacy |
| **Unity Ads** | https://unity.com/legal/privacy-policy |

You can opt out of personalized ads at any time through the **Privacy Settings** option in our app.

---

## 6. GDPR & Privacy Consent (EEA, UK, Switzerland)

If you are located in the European Economic Area (EEA), United Kingdom, or Switzerland:
- We show a **consent dialog** on first launch asking for your permission before showing personalized ads
- You can withdraw or change your consent at any time via **Settings → Privacy Settings**
- Without consent, only non-personalized ads are shown
- We use Google's **User Messaging Platform (UMP)** to manage consent

---

## 7. Children's Privacy

AppLock Pro is not directed to children under 13. We do not knowingly collect data from children.

---

## 8. Data Retention & Deletion

- All locally stored data (photos, logs, settings) can be deleted by uninstalling the app
- Intruder photos can be deleted individually from the Security screen
- Firebase analytics data is retained per Google's standard data retention policy (up to 14 months)
- Crashlytics reports are retained for 90 days

---

## 9. Security

- Your PIN/password is stored encrypted on your device
- Intruder photos are stored in the app's private directory, inaccessible to other apps
- Device Admin protection (optional) prevents unauthorized uninstallation

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. The "Effective Date" at the top will be updated. Continued use of the app after changes means you accept the updated policy.

---

## 11. Contact Us

**Email:** nextgenversesolutions@gmail.com
