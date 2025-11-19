# Privacy Policy — Paliy Widget App

_Last updated: 2025-11-19_

Paliy Widget is a private, non-government project. It is not affiliated with any government body, utility provider, or municipal organization in Ukraine.  
The app provides a convenient way to view publicly available outage schedules and related data.

This Privacy Policy describes how the app handles data on iOS and Android.

---

## 1. Overview

Paliy Widget:

- does **not** collect personal data
- does **not** create user accounts
- does **not** collect location
- does **not** use analytics or tracking
- does **not** serve ads
- does **not** process payments
- uses only publicly available data provided by the developer’s backend
- communicates only with its own API servers

Your data is never sold, shared, or used for tracking.

---

## 2. Data We Collect

### We do NOT collect:

- Personal information (name, email, phone)
- Identifiers (device ID, advertising ID)
- Location data
- Contacts, photos, media, files
- Usage analytics
- Any data that can identify you

### We DO handle:

#### 2.1. Technical Request Data (standard HTTP logs)

When the app or widget requests data from the backend, the server receives standard technical metadata automatically sent by your device:

- IP address
- User agent (device model, OS version)
- Timestamp of request

This information is used only for server security, availability, and rate limiting.  
It is **not** linked to a personal profile and **not** used for tracking.

#### 2.2. Publicly Available Outage Data

The app displays:

- electrical outage schedules
- lists of streets for manual search

These datasets are publicly available and do not contain personal information.

---

## 3. How the App Works

### 3.1. Backend Communication

The app uses the developer’s own backend to fetch:

- outage schedules
- street lists for searching
- widget update data

No private user data is transmitted.

### 3.2. Widget Behavior (iOS & Android)

The widget may:

- refresh periodically, based on OS rules
- perform background data fetches
- request updated schedule data from the backend
- display current outage information

All widget requests involve only publicly available data.  
Widgets do **not** collect or store personal information.

### 3.3. External Links

The app may provide links to external services such as the developer’s Telegram bot.  
Interactions with external services are governed by their respective privacy policies.

---

## 4. Push Notifications / Silent Background Messages

The app does **not** send visible notifications to users.  
However, both iOS and Android versions use **silent messages** to update widget data or trigger refreshes.

These messages:

- contain **no personal information**
- are **not** device-specific (topic-based)
- do **not** display alerts, badges, or sounds
- are used only to optimize widget refresh timing

### 4.1. iOS (APNs Silent Push)

The iOS app uses Apple Push Notification service (APNs) **only** for:

- receiving silent “content-available” updates
- refreshing widget data in the background

### 4.2. Android (FCM Silent Push)

The Android app uses Firebase Cloud Messaging (FCM) **only** for:

- receiving topic-based silent data updates
- refreshing widget content in the background

Neither platform shows any user-visible notifications.

---

## 5. Platform-Specific Information

### 5.1. iOS

The iOS version may use the following system features:

- **WidgetKit** — displays schedule data in a widget
- **Background app refresh** — for periodic schedule updates
- **Silent push notifications (APNs)** — to trigger widget refreshes
- **App Groups** — for storing widget shared settings (non-personal data only)

No personal data is stored in App Groups.

### 5.2. Android

The Android version may use:

- **App Widgets framework** — to display outage schedules
- **Background updates** — controlled by Android OS
- **Firebase Cloud Messaging (FCM)** — for silent background refreshes
- **SharedPreferences** — to store widget settings (non-personal data only)

No personal or device-identifiable data is stored.

---

## 6. Third-Party Services

### iOS
- Apple Push Notification service (APNs)

### Android
- Firebase Cloud Messaging (FCM)

No analytics or tracking services are used.

---

## 7. Data Storage

The app stores only:

- widget settings (language, or UI preferences)
- last retrieved schedule data

Stored locally on your device.  
Nothing is uploaded or shared with third parties.

---

## 8. Children's Privacy

The app does not target children and processes **no personal data of any kind**.

---

## 9. Data Security

All communication with the backend uses HTTPS.  
No personal data is transmitted or stored, but standard security measures are applied to server operations.

---

## 10. Your Rights

Because the app does not collect or store personal data:

- there is no data to request, export, delete, or modify
- there is no account to manage

If you uninstall the app, all local data (widget settings & cached schedule) is deleted automatically.

---

## 11. Changes to This Policy

This policy may be updated occasionally.  
The latest version will always be available at the same link.

---

## 12. Contact

If you have questions about this Privacy Policy, you may contact the developer:

**Email:** roman.kyzymenko@gmail.com  
**Developer:** Roman Kyzymenko, private independent developer  
**Location:** Poltava, Ukraine (non-government project)

---

# End of Privacy Policy
