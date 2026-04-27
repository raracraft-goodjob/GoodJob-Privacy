# Privacy Policy

**GoodJob** ("the App") takes your privacy seriously and is committed to complying with applicable data protection laws. This Privacy Policy explains what information the App collects and how it is used.

---

### 1. Purpose of Collection and Use

The App collects minimal information for the following purposes:

- **Service delivery:** Providing schedule and to-do list management features.
- **Notifications & reminders:** Sending alerts for user-configured schedules.
- **Place search:** Enabling map and place search when adding a location to a schedule.
- **AI schedule parsing:** Converting natural-language input into structured schedule data using an AI service.
- **Cloud backup / sync:** Backing up and restoring schedule data via Google Drive (optional, user-initiated).
- **Subscription & billing:** Verifying subscription status and managing billing through Google Play Billing.
- **Customer support:** Responding to inquiries and improving the service.

---

### 2. Information We Collect

The App does not store sensitive personal information on external servers as a matter of principle.

- **Device information:** Device model, OS version, and advertising identifier (ADID) for optimization and crash analysis.
- **Billing data:** Payment authorization tokens and subscription status via Google Play. Detailed payment method information (e.g., card numbers) is managed solely by Google and is never transmitted to the App.
- **User-generated data:** Schedule and to-do data entered by the user. This data is stored in a local on-device database by default. When Google Drive sync is enabled, an encrypted backup is uploaded to the user's app-specific Drive storage (`appDataFolder`), which is inaccessible to other apps.
- **AI-processed data:** When using the voice or natural-language schedule input feature, the entered text is sent to the Google Gemini API for processing. Google's Privacy Policy applies.

---

### 3. App Permissions

The App may request the following permissions:

| Permission | Purpose |
|---|---|
| **Notifications** | Send schedule reminders and alerts. |
| **Microphone** (`RECORD_AUDIO`) | Record voice input for AI-powered schedule entry. Audio is processed by Gemini AI and is not stored. |
| **Display over other apps** (`SYSTEM_ALERT_WINDOW`) | Show schedule information on the lock screen when the lock screen feature is enabled. |
| **Run at startup** (`RECEIVE_BOOT_COMPLETED`) | Restore scheduled alarms after a device reboot. |
| **Read phone state** (`READ_PHONE_STATE`) | Automatically dismiss the App's lock screen when an incoming call is detected, so calls are never blocked. No call content or personal identifiers are collected. |

---

### 4. Third-Party Services

The App uses the following third-party services to deliver and improve its features:

- **Google Play Services** — Core functionality and optional Google Sign-In.
- **Google Play Billing** — In-app purchases and recurring subscriptions.
- **Google Maps / Places API** — Map display and place search. [Google Privacy Policy](https://policies.google.com/privacy)
- **Google Calendar API** — Fetching public holiday data.
- **Google Drive API** — App-specific backup storage (`appDataFolder`). Inaccessible to other apps or third parties.
- **Google Gemini AI** — Natural-language and voice schedule parsing. [Google Privacy Policy](https://policies.google.com/privacy)
- **Kakao SDK** — Place search (REST API) and map display (WebView). [Kakao Privacy Policy](https://www.kakao.com/policy/privacy)
- **Firebase (Analytics / Crashlytics)** — Anonymized usage analytics and crash monitoring.

---

### 5. Data Security & Retention

- The App follows standard security practices including encrypted communication to protect user data.
- Google Drive backup data is removed from app-specific storage when the user disables sync or uninstalls the App.
- Upon app deletion or subscription cancellation, data is deleted without delay after any retention period required by applicable law.

---

### 6. Your Rights & Data Deletion

You have the right to manage your personal information and in-app data at any time:

- **On-device deletion:** Reset data in the App's settings or uninstall the App to remove all local data.
- **Cloud data deletion:** Disconnect Google Drive or delete app data through your Google account to remove backup data.
- **Deletion requests:** Contact us via the information below and we will respond promptly.

---

### 7. Changes to This Policy

This policy may be updated to reflect changes in law or service features. Any changes will be announced via in-app notice or the store listing.

---

### 8. Contact

- **Developer:** Raracraft
- **Email:** raracraft.goodjob@gmail.com
- **Package:** com.raracraft.todo.schedule.goodjob



---

# Data Deletion Policy

### How to delete your data from GoodJob
GoodJob stores your schedule and task data in your private Google Drive 'App Data Folder' to ensure security and privacy. Because this data is stored in your private storage, we (the developers) do not have direct access to delete your data on your behalf.

You can delete your data and revoke the app's access to your Google Drive by following these steps:

1. Go to [Google Drive (drive.google.com)](https://drive.google.com/).
2. Click on the **Settings (gear icon)** in the top right corner.
3. Select **"Manage Apps"**.
4. Find **"GoodJob"** in the list.
5. Click **"Options"** and select **"Disconnect from Drive"**.
6. This will permanently remove the app's access and the associated data from your Google Drive.

### Contact for Data Deletion
If you have any trouble with the process above or have further questions regarding your data, please feel free to contact us at:
- **Email:** [나현종 님의 이메일 주소]
- **Subject:** "Account Deletion Request - GoodJob"

We will respond to your request within 7 business days to assist you.
