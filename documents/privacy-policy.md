# Privacy Policy — Keynotif

**Effective Date:** April 24, 2026
**Developer:** FlagoDNA
**Contact:** [flagodna.com@gmail.com](mailto:flagodna.com@gmail.com)

---

## 1. Introduction

Keynotif is a privacy-first Android application that helps users manage and summarize notifications.
We are committed to protecting your data through a **local-first architecture**, strict data minimization, and transparent processing.

By using Keynotif, you agree to the practices described in this Privacy Policy.

---

## 2. Data We Access

Keynotif requires access to **device notifications** to function.

This may include:

- App names
- Notification titles and content
- Timestamps

**Important:**

- This data is primarily processed **locally on your device**
- We do not collect or store raw notification data on our servers

---

## 3. How We Use Data

Notification data is used strictly to:

- Filter important vs non-important notifications
- Generate summaries (e.g., morning digest)
- Allow user-controlled filtering (ignored apps, etc.)

We do **not** use your data for:

- Advertising
- Profiling
- Behavioral tracking

---

## 4. AI Processing & Anonymization

If AI summarization is used:

Before any processing:

- Sensitive data is **automatically sanitized**

Examples:

- Emails → `[EMAIL-XXX]`
- Links → `[LINK-XXX]`
- Numbers (phone, OTP, IDs) → `[NUM-XXX]`

**Guarantee:**

- Raw personally identifiable information (PII) is never sent for processing
- Only anonymized, minimal data is used

---

## 5. Data Storage & Retention

We minimize how long data exists:

- All data is stored **locally on your device**
- Summaries are deleted automatically (daily)
- Notification data is deleted after **7 days**

We do not maintain long-term user data or history.

---

## 6. Data Sharing

We do **not**:

- Sell user data
- Share data with advertisers
- Use third-party analytics services

Any external processing (if applicable) is:

- Limited to anonymized data only
- Never includes raw personal information

---

## 7. Permissions

Keynotif requests only the permissions necessary for functionality:

### Core Permission

- **Notification Access** (`BIND_NOTIFICATION_LISTENER_SERVICE`)
  → Required to read and process notifications

---

### App Functionality

- `POST_NOTIFICATIONS` → Display summaries
- `FOREGROUND_SERVICE` → Run background processing
- `FOREGROUND_SERVICE_DATA_SYNC` → Reliable sync operations
- `FOREGROUND_SERVICE_REMOTE_MESSAGING` → Notification handling

---

### System Reliability

- `RECEIVE_BOOT_COMPLETED` → Restart after reboot
- `WAKE_LOCK` → Prevent interruption during processing
- `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` → Ensure stability

---

### Optional

- `com.android.vending.BILLING` → In-app purchases (if used)

---

## 8. Firebase Cloud Messaging (FCM)

Keynotif may use Firebase Cloud Messaging (FCM) for delivering system messages.

- No notification content is sent via FCM
- No analytics tracking is enabled
- FCM is used strictly for message delivery

---

## 9. Security

We prioritize device-level security:

- Data remains on-device by default
- No hidden data transmission
- Secure Android APIs are used

---

## 10. Your Control

You have full control over your data:

- Revoke notification access anytime via system settings
- Clear app data via Android settings
- Uninstall the app to remove all stored data

---

## 11. Children’s Privacy

Keynotif is not intended for children under 13.
We do not knowingly collect data from children.

---

## 12. Changes to This Policy

We may update this Privacy Policy periodically.
Updates will be reflected by revising the effective date.

---

## 13. Contact

For any privacy-related questions:

**Email:** [flagodna.com@gmail.com](mailto:flagodna.com@gmail.com)

---

## 14. Summary (Plain Language)

- Your data stays on your device
- Sensitive information is anonymized before processing
- No ads, no tracking, no selling data
- Data is automatically deleted after a short period

---

© 2026 FlagoDNA
