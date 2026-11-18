# Privacy Policy — Daily MeMo

**Effective Date:** November 18, 2026
**Last Updated:** November 18, 2026

| | |
|---|---|
| **Application** | Daily MeMo (`com.dailymemo.app`) |
| **Developer** | Htein Lynn Aung |
| **Contact Email** | hteinlynnaung.1111@gmail.com |
| **Country / Region** | Thailand |

---

## Summary of Key Points

- Daily MeMo is an **offline-first** app. You can use it without creating an account, and your data stays on your device.
- We **do not** sell your data, run advertising, or use third-party analytics or tracking SDKs.
- We **do not** collect your location, contacts, SMS, call logs, camera, or microphone audio, and we do not access your advertising ID.
- If you create an account for cloud sync, we collect only your **email address**, an **optional display name**, and the **content you choose to sync**.
- You can **delete your account and all associated data in-app** at any time, or by email.
- This policy is written to meet **Google Play** privacy disclosure requirements and applicable data-protection law, including Thailand's **PDPA**.

---

## Table of Contents

1. [Who We Are and Scope](#1-who-we-are-and-scope)
2. [Information We Collect](#2-information-we-collect)
3. [Device Permissions We Request](#3-device-permissions-we-request)
4. [How We Use Your Information](#4-how-we-use-your-information)
5. [Legal Bases for Processing](#5-legal-bases-for-processing)
6. [Sharing and Disclosure](#6-sharing-and-disclosure)
7. [International Data Transfers](#7-international-data-transfers)
8. [Data Security](#8-data-security)
9. [Data Retention](#9-data-retention)
10. [Your Rights and Choices](#10-your-rights-and-choices)
11. [Account and Data Deletion](#11-account-and-data-deletion)
12. [Children's Privacy](#12-childrens-privacy)
13. [Cookies, Tracking, and Advertising](#13-cookies-tracking-and-advertising)
14. [Third-Party Links and Services](#14-third-party-links-and-services)
15. [Changes to This Privacy Policy](#15-changes-to-this-privacy-policy)
16. [Contact Us](#16-contact-us)

---

## 1. Who We Are and Scope

Daily MeMo ("the App") is a personal productivity application for managing notes, tasks, calendar events, alarms, focus sessions, and anniversaries.

This Privacy Policy explains what information is collected, how it is used and protected, and the rights available to you. It applies to the App on all supported platforms and to the optional cloud synchronization service.

By using Daily MeMo, you consent to the practices described here. If you do not agree, please discontinue use of the App.

---

## 2. Information We Collect

Daily MeMo operates in two modes. **Offline Mode** requires no account and sends no data to us. **Cloud Sync** is optional and activated only when you register or sign in.

### 2.1 Account Information (Optional — Cloud Sync Only)

If you choose to register or sign in for cloud synchronization, we collect the following through **Supabase Authentication**:

- **Email address** — required for account creation and sign-in.
- **Password** — hashed and managed by Supabase Auth; never stored or visible to us in plaintext.
- **Display name** — optional, used to label your profile.

### 2.2 User-Created Content

The following content is created by you and is stored locally on your device:

- **Notes**, including note folders, categories, and tags
- **Tasks and subtasks** — titles, priorities, categories, due dates and times, completion status
- **Calendar events** — titles, descriptions, locations, start and end times
- **Reminders and alarms** — titles, schedules, recurrence rules, and enabled status

In **Offline Mode**, this content remains solely in local SQLite storage on your device and is never transmitted to us.

When you sign in, this content is synchronized to our Supabase PostgreSQL database so that you can back it up and access it across your devices. Content you create while signed in is **linked to your account**.

### 2.3 Device-Local Data (Never Uploaded)

The following data is stored **only on your device** and is never uploaded to our servers:

- **Anniversary entries** — titles, names, dates, and colors (stored in local app storage on the device)
- **App preferences** — including workspace name, theme mode, English/Japanese language, week start day, alarm sound selection (built-in or custom file), notification enable/disable, notification detail-privacy setting, focus timer duration, and daily goal percentage
- **Custom alarm sound files** — copied into app storage when you select one through the device file picker
- **Authentication session tokens** — stored in platform-encrypted storage (see [Section 8](#8-data-security))

### 2.4 Information We Do Not Collect

Daily MeMo does **not**:

- Include third-party advertising SDKs or display advertising
- Use third-party behavioral analytics, attribution, or crash-reporting SDKs
- Collect, access, or transmit location data, contacts, SMS, call logs, photos, camera, or microphone audio
- Access or collect your Google Advertising ID or any device advertising identifier
- Process payments or make in-app purchases — the App is provided free of charge
- Collect any information automatically in the background without your action

---

## 3. Device Permissions We Request

Daily MeMo requests only the permissions required for its core functionality:

| Permission | Purpose |
|---|---|
| **Notifications** (`POST_NOTIFICATIONS`, Android 13+ runtime) | Deliver locally scheduled alarms and task reminders. |
| **Audio & Foreground Playback** (`MODIFY_AUDIO_SETTINGS`, `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK`) | Play alarm sounds reliably when an alarm triggers, including while the App is in the background. |
| **File Access (user-initiated only)** | Allow you to select a custom audio file for alarm sounds. Access occurs only when you open the file picker and choose a file. |

The App does **not** request `RECORD_AUDIO`, location, contacts, phone, SMS, camera, or calendar permissions.

---

## 4. How We Use Your Information

We use your information solely to:

- Create and maintain your account and keep you signed in
- Store your notes, tasks, events, and alarms locally, and synchronize them across your devices when you are signed in
- Deliver local scheduled notifications and alarms on your device
- Provide, maintain, and improve the App's functionality
- Respond to support, privacy, and data-deletion requests sent to **hteinlynnaung.1111@gmail.com**
- Comply with legal obligations

We do **not** sell, rent, trade, or lease your personal information to third parties, and we do not use it for targeted advertising.

---

## 5. Legal Bases for Processing

Where applicable law requires a legal basis for processing, we rely on:

- **Consent** — when you create an account, enable cloud sync, or grant a device permission. You may withdraw consent at any time by disabling the feature or deleting your account.
- **Performance of a contract** — to provide the synchronization and account functionality you request.
- **Legitimate interests** — to operate, secure, and improve the App, provided these interests do not override your rights.
- **Legal obligation** — where processing is required to comply with applicable law.

---

## 6. Sharing and Disclosure

We do not sell your personal information. We share it only in the following limited circumstances:

- **Service providers.** We use **Supabase** for authentication and PostgreSQL database hosting solely as our infrastructure provider. Supabase processes data on our behalf under its own security and privacy commitments and does not use it for its own purposes.
- **Legal requirements.** We may disclose information if required to do so by law, regulation, legal process, or enforceable governmental request, or where necessary to protect the rights, safety, or property of our users or the public.
- **Business transfers.** If the App is involved in a merger, acquisition, or sale of assets, your information may be transferred as part of that transaction. We would provide notice before your information becomes subject to a different privacy policy.

Other than as described above, your information is not shared with third parties.

---

## 7. International Data Transfers

Daily MeMo is operated from **Thailand**. When you use cloud sync, your data is processed by Supabase, whose servers may be located outside your country of residence.

Where personal information is transferred internationally, we take appropriate safeguards consistent with applicable data-protection law, including reliance on our service provider's contractual and technical protections and encryption in transit (see [Section 8](#8-data-security)).

By using cloud sync, you acknowledge that your information will be transferred to and processed in countries other than your own.

---

## 8. Data Security

We implement technical and organizational measures designed to protect your data:

- **Encrypted token storage.** Authentication session tokens are stored on your device using platform-encrypted storage (`expo-secure-store`), which relies on the operating system's secure enclave or keystore.
- **Encryption in transit.** All communication between the App and Supabase uses TLS/HTTPS encryption.
- **Database access controls.** Supabase PostgreSQL is protected by **Row Level Security (RLS)** policies that restrict every authenticated user to reading, creating, updating, or deleting only their own records.
- **Local isolation.** Offline data is stored in application-private SQLite storage, inaccessible to other apps on the device.

While we follow industry-standard security practices, no method of electronic storage or transmission is completely secure. We cannot guarantee absolute security, but we will notify affected users and relevant authorities of any personal-data breach as required by applicable law.

---

## 9. Data Retention

| Data | Retention |
|---|---|
| **Local data** (notes, tasks, events, alarms, anniversaries, preferences) | Retained on your device until you delete the individual items, sign out, uninstall the App, or clear App data. |
| **Cloud-synced data** | Retained while your account remains active, until you delete the individual items or delete your account. |
| **Account credentials** | Retained until your account is deleted. |
| **Support correspondence** | Retained for as long as necessary to resolve your request and to maintain a record of the request. |

When you delete your account, your cloud records are deleted immediately through a cascading database operation. Encrypted backup copies managed by our hosting provider may persist for a limited period before being overwritten or permanently removed.

Uninstalling the App does not delete your cloud account. To remove cloud data, delete your account in-app or contact us by email before uninstalling.

---

## 10. Your Rights and Choices

Subject to applicable law, including Thailand's Personal Data Protection Act (PDPA), you have the right to:

- **Access** the personal information we hold about you
- **Correct** inaccurate or incomplete information
- **Delete** your personal information and your account
- **Obtain a copy** of your personal information in a portable, machine-readable format
- **Withdraw consent** at any time where processing is based on consent, without affecting the lawfulness of prior processing
- **Object to** or restrict certain processing
- **Lodge a complaint** with a supervisory authority

You can exercise most of these rights directly in the App:

- **Correct or delete content** — edit or remove individual notes, tasks, events, alarms, and anniversaries at any time.
- **Delete your account** — see [Section 11](#11-account-and-data-deletion).

To exercise any other right, or to request a copy of your data, email **hteinlynnaung.1111@gmail.com** from your registered email address. We will respond within the timeframe required by applicable law.

---

## 11. Account and Data Deletion

You may permanently delete your account and all associated data at any time:

**In-app:** **Settings → Account & Cloud Sync → Delete Account**

This action:

1. Permanently deletes your authentication account and all user-owned cloud records in Supabase via a cascading deletion operation
2. Signs you out and clears local SQLite data (notes, tasks, events, alarms, categories, tags, and sync metadata) from your device
3. Removes locally stored anniversary entries from the device

Deletion is irreversible and cannot be undone.

**By email:** If you cannot access the App, request account and data deletion by emailing **hteinlynnaung.1111@gmail.com** from your registered email address. Verified requests are processed promptly, and within the timeframe required by applicable law.

**Signing out** clears local SQLite data and local anniversary records from the device. Note that signing out does not delete your cloud account; use account deletion for that purpose.

---

## 12. Children's Privacy

Daily MeMo is intended for users aged **16 and older** and is not directed at children under 16.

We do not knowingly collect personal information from children under 16, and we do not offer the App to children under 13 in any jurisdiction where parental consent is required (including under the U.S. Children's Online Privacy Protection Act, or COPPA).

If you believe a child under 16 has provided personal information through the App, contact us at **hteinlynnaung.1111@gmail.com** and we will delete it promptly.

---

## 13. Cookies, Tracking, and Advertising

- **Cookies.** Daily MeMo is a native application and does not use cookies or similar tracking technologies.
- **Analytics and tracking.** The App contains no analytics, attribution, crash-reporting, or behavioral-tracking SDKs.
- **Advertising.** The App contains no advertising and does not collect or use your advertising identifier.
- **No sale of data.** We do not sell, share, or disclose your personal information for cross-context behavioral advertising.

---

## 14. Third-Party Links and Services

The App may contain links to third-party websites or services, such as the Supabase privacy policy referenced in this document. We are not responsible for the privacy practices of third parties, and we encourage you to review their policies before providing any information.

---

## 15. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, technology, or legal requirements.

- The **Effective Date** at the top of this document will be revised when changes are made.
- Where required by law, we will provide additional notice of material changes within the App or by email.
- Continued use of the App after an update constitutes acceptance of the revised policy.

We encourage you to review this policy periodically.

---

## 16. Contact Us

For questions, concerns, or requests regarding this Privacy Policy or your personal data — including data access, correction, portability, or deletion — please contact:

- **Developer:** Htein Lynn Aung
- **Email:** hteinlynnaung.1111@gmail.com
- **Country:** Thailand

We will respond to your request within the timeframe required by applicable law.
