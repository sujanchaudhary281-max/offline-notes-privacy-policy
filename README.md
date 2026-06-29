# Privacy Policy

**App Name:** Offline Notes: No Cloud
**Package:** `com.sujan.offlinenotes`
**Developer:** Sujan Chaudhary
**Last updated:** June 29, 2026

---

## 1. Overview

Offline Notes: No Cloud is a private, fully offline note-taking application. Your notes never leave your device. We do not operate any servers, we do not collect any data, and we do not track you in any way.

---

## 2. Data We Collect

**We collect no personal data whatsoever.**

The app contains:

* No analytics
* No advertising SDKs
* No crash reporting services
* No third-party tracking

No information is ever transmitted to us or anyone else.

---

## 3. Data Stored on Your Device

The app stores the following data **locally on your device only**:

* Your notes, titles, and note content
* Folders and tags you create
* App settings and preferences (theme, font, auto-lock settings)
* A hashed version of your PIN (the actual PIN is never stored in plain text)
* An encrypted backup key used to encrypt backup files

All of this data is stored in a local SQLite database on your device and is never synced to any cloud service.

---

## 4. PIN & Lock Screen

The app allows you to protect your notes with a numeric PIN.

Your PIN is stored as a **one-way cryptographic hash (SHA-256)**, meaning it cannot be reversed or read.

After **5 incorrect PIN attempts**, the app enforces a timed lockout to help protect against brute-force attacks.

The app also supports a **Decoy PIN** feature. This separate PIN opens an empty or decoy vault, helping protect your real notes if you are ever forced to unlock the app.

---

## 5. Biometric Authentication

The app supports biometric authentication, including:

* Fingerprint
* Face Recognition (Face ID on iOS)
* Device biometrics on Android

Biometric verification is performed entirely by your device's operating system.

The app:

* Does **not** access biometric information
* Does **not** store biometric data
* Does **not** transmit biometric data

---

## 6. Backup & Export

The app can create encrypted backup files (`.vaultnote.enc`) saved to your device's local storage.

These files are encrypted using **AES** before being saved.

You can manually share or export these files using your device's share sheet. We do not receive copies of your backups.

Notes can also be exported as:

* Plain text (`.txt`)
* PDF (`.pdf`)

These exports are created only when you request them.

---

## 7. Pro Upgrade & In-App Purchases

The app offers an optional one-time **Pro Upgrade** that unlocks additional features, including:

* Unlimited notes
* Unlimited folders
* Note history
* Backup
* Export
* And more

Purchases are processed securely through **Google Play (Android)** or the **App Store (iOS)** using the `react-native-iap` library.

When you make a purchase or restore a previous purchase, your device communicates directly with Google Play or the App Store.

We do **not** receive, handle, or store any payment or billing information.

Your Pro status is stored locally on your device only.

---

## 8. Permissions

The app only requests the following permissions:

### Biometrics (USE_BIOMETRIC / Face ID)

Used to authenticate and unlock the app and vault.

Requested only when you choose to enable biometric unlock.

### In-App Purchases (BILLING)

Used to process the optional one-time Pro Upgrade through Google Play.

All transactions are handled by Google Play. We do not receive or store payment information.

### The app does **not** request access to:

* Camera
* Microphone
* Location
* Contacts
* Phone
* SMS
* Any other sensitive permissions

---

## 9. Note History

The app maintains a local history of previous versions of your notes.

This history:

* Is stored only on your device
* Allows restoring previous versions
* Is permanently deleted when the note is permanently deleted

---

## 10. Trash

Deleted notes are moved to a local Trash folder on your device.

Trash is never synced anywhere.

You may restore or permanently delete notes at any time.

---

## 11. Children's Privacy

This app does not knowingly collect data from anyone, including children under the age of 13.

The app is a general-purpose productivity tool and is not directed toward children.

---

## 12. Third-Party Services

Offline Notes: No Cloud does **not** use:

* Analytics services
* Advertising services
* Third-party tracking
* Data collection services

---

## 13. Security

We take security seriously.

Security measures include:

* Your notes are stored in a local SQLite database on your device.
* Backup files are AES-encrypted before being written to disk.
* PINs are hashed using SHA-256 and are never stored in plain text.
* All security operations happen locally on your device.

---

## 14. Changes to This Policy

If this Privacy Policy is updated, the latest version will be published at this URL.

Your continued use of the app after changes means you accept the updated Privacy Policy.

---

## 15. Contact

If you have any questions about this Privacy Policy, please contact us.

**Email:** [sujanchaudhary281@gmail.com](mailto:sujanchaudhary281@gmail.com)

---

© 2026 Offline Notes: No Cloud. All rights reserved.
