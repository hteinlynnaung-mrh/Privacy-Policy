# Privacy Policy for Daily MeMo

**Effective Date:** November 18, 2026  
**Developer:** Htein Lynn Aung  
**Application:** Daily MeMo (`com.dailymemo.app`)  
**Contact Email:** hteinlynnaung.1111@gmail.com  
**Country / Region:** Thailand  

---

## 1. Overview

Daily MeMo ("the App") is an offline-first personal productivity application for managing notes, tasks, calendar events, alarms, focus sessions, and anniversaries. This Privacy Policy explains what information is collected, how it is used and protected, and your rights regarding your data.

By using Daily MeMo, you agree to the practices described in this Privacy Policy.

---

## 2. Information We Collect and Process

### 2.1 Account Information (Optional — Cloud Sync Only)
You can use Daily MeMo in **Offline Mode** without creating an account. If you choose to register or sign in for cloud synchronization, we collect via **Supabase Authentication**:
- **Email address** (required for account creation and sign-in)
- **Password** (hashed and managed by Supabase Auth; never stored in plaintext)
- **Display name** (optional)

### 2.2 User-Created Productivity Content
- **Notes, Note Folders, Categories, and Tags**
- **Tasks and Subtasks** (titles, priorities, due dates/times, completion status)
- **Calendar Events** (titles, descriptions, locations, start/end times)
- **Reminders and Alarms** (titles, schedules, recurrence rules, enabled status)

When you use Offline Mode, this data stays solely in local SQLite storage on your device. When you sign in, this data is synchronized with our Supabase PostgreSQL database so you can back it up and access it across your devices.

### 2.3 Device-Local Only Data
The following data is stored **only on your device** and is not uploaded to our servers:
- **Anniversary entries** (titles, names, dates, and colors)
- **App preferences** (theme mode, English/Japanese language setting, focus timer duration, notification privacy setting)
- **Custom alarm sound files** selected manually by you through the device file picker

### 2.4 Data We Do Not Collect
Daily MeMo does **not**:
- Include third-party advertising SDKs or display ads
- Use third-party behavioral analytics or tracking SDKs
- Collect location data, contacts, SMS, call logs, camera, or microphone audio

---

## 3. Device Permissions Used

Daily MeMo requests only permissions needed for core productivity features:
- **Notifications (`POST_NOTIFICATIONS`):** To deliver local scheduled alarms and task reminders.
- **Audio & Foreground Playback (`MODIFY_AUDIO_SETTINGS`, `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`):** To play alarm sounds reliably when an alarm triggers.
- **File Picker Access (User-Initiated Only):** Only when you choose to select a custom audio file from your device for alarm sounds.

---

## 4. How We Use Your Information

We use your information strictly to:
- Authenticate your account and maintain your signed-in session
- Save your notes, tasks, events, and alarms locally and sync them across your devices when signed in
- Deliver local scheduled notifications and alarms on your device
- Respond to support or privacy requests sent to `hteinlynnaung.1111@gmail.com`

We do **not** sell, rent, or trade your personal information to third parties.

---

## 5. Third-Party Service Providers

For users who enable cloud sync, Daily MeMo uses **Supabase** (authentication and PostgreSQL cloud database hosting) solely as our infrastructure provider to store and synchronize your account and productivity data. Supabase processes this data in accordance with its security and privacy commitments.

---

## 6. Data Security

We implement technical safeguards to protect your data:
- **Encrypted Token Storage:** Authentication session tokens are stored on your device using platform-encrypted storage (`expo-secure-store`).
- **Encryption in Transit:** All communication between the App and Supabase uses HTTPS/TLS encryption.
- **Row Level Security (RLS):** Database access in Supabase PostgreSQL is enforced by Row Level Security policies so authenticated users can only read, create, update, or delete their own records.

While we follow industry-standard security practices, no method of electronic storage or transmission is 100% secure.

---

## 7. Data Retention and Account Deletion

- **Active Accounts:** Your synced data is retained for as long as your account remains active or until you delete individual items.
- **In-App Account Deletion:** You can permanently delete your account and all associated data at any time directly inside the App by going to **Home → Settings → Delete Account**. This action permanently deletes your authentication account and cascading cloud records from Supabase, and wipes local SQLite and anniversary data from your device.
- **Deletion Requests by Email:** If you cannot access the App, you may request account and data deletion by emailing **hteinlynnaung.1111@gmail.com** from your registered email address. Verified requests are processed promptly.
- **Sign-Out:** Signing out clears local SQLite data and local anniversary records from the device.

---

## 8. Age Requirement (16+)

Daily MeMo is intended for users aged **16 and older** and is not directed at children under 16. We do not knowingly collect personal information from children under 16. If you believe a child under 16 has provided personal information through the App, please contact us at **hteinlynnaung.1111@gmail.com** so we can delete it.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any updates will be reflected by revising the **Effective Date** at the top of this document.

---

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact:

- **Developer:** Htein Lynn Aung
- **Email:** hteinlynnaung.1111@gmail.com
- **Country:** Thailand
