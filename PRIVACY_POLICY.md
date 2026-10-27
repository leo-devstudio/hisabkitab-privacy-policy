# Privacy Policy for HisabKitab

**Last updated:** October 27, 2026  
**Effective date:** October 27, 2026  
**Application ID:** `com.hisabkitab.application`  
**Contact:** [support@hisabkitab.app](mailto:support@hisabkitab.app)

---

## 1. Introduction

Welcome to **HisabKitab**. HisabKitab is an expense tracking, bill splitting, and group balance settlement application designed to help individuals, roommates, travel groups, and friends manage shared expenses transparently.

This Privacy Policy explains how your information is collected, used, shared, and safeguarded when you use our mobile application (Android), Progressive Web Application (PWA), and web services (collectively, the "Service").

By accessing or using HisabKitab, you consent to the practices described in this Privacy Policy. If you do not agree with any part of this policy, please do not use the Service.

---

## 2. Information We Collect

We only collect information necessary to provide, improve, and secure our expense-splitting and ledger calculation services.

### A. Personal Information You Provide
* **Account Information:** When you register or sign in via email or third-party authentication (e.g., Google OAuth via Supabase), we collect your name, email address, and profile avatar URL.
* **Guest Mode:** If you choose to use the app in "Guest Mode", your profile name and details are stored locally on your device and are not linked to a remote account until you explicitly sign up or sync.
* **UPI ID / Payment Identifier (Optional):** You may optionally provide a Virtual Payment Address (UPI ID) in your profile or settlement details to allow other group members to easily generate UPI payment links or QR codes to settle debts with you. **HisabKitab never asks for, stores, or processes UPI PINs, bank account passwords, or debit/credit card numbers.**

### B. Expense, Group & Financial Ledger Data
* **Groups & Memberships:** Group names, descriptions, categories (e.g., trip, home, couple, project), member lists, and join/invite codes.
* **Transaction Records:** Expenses added by you or other group members, including amounts, currency, descriptions, categories (food, travel, shopping, etc.), dates, receipts/notes, and split breakdowns (equal, exact, percentage, shares, or itemized).
* **Settlements & Balances:** Records of debt settlements entered between members, payment method tags (e.g., Cash, UPI, Bank Transfer), and computed balances.
* **Repayment Metrics & Scores:** In-app punctuality scores, badges, and repayment statistics derived strictly from settlement history within your groups.

### C. Automatically Collected & Technical Information
* **Device & Usage Data:** Operating system version, device model, app version, language settings, and general diagnostic information to troubleshoot bugs and improve app stability.
* **Push Notification Tokens:** If you grant permission for push notifications, we store a unique device token to send you alerts when expenses are added, edited, or settled.
* **Local Storage & Cache:** We use browser LocalStorage / IndexedDB to cache your active ledger data for offline usage, fast loading, and offline queue synchronization.

### D. Third-Party Webhook Data (Optional)
* **Discord Webhook URLs:** If a group administrator configures a Discord webhook to post expense notifications and weekly group summaries, that webhook URL is stored to dispatch message payloads to the specified Discord channel.

---

## 3. How We Use Your Information

We use the collected information for the following purposes:
1. **Core Functionality:** Calculating who owes whom, simplifying group debts, maintaining audit logs of expense edits, and computing repayment metrics.
2. **Collaboration:** Sharing transaction details, balances, and settlement history with verified members of the same group.
3. **Notifications & Reminders:** Sending push notifications or Discord webhook alerts regarding new expenses, debt settlements, and group activity.
4. **Offline Sync:** Synchronizing data between your local device cache and our cloud database when your internet connection is restored.
5. **Account Management & Security:** Authenticating users, maintaining session security, preventing abuse, and enforcing Row-Level Security (RLS) rules.
6. **Customer Support:** Diagnosing issues, answering technical questions, and resolving errors reported by users.

---

## 4. How Information Is Shared

We do **not** sell, rent, or trade your personal or financial data to data brokers, advertisers, or unaffiliated third parties. Information is only shared under the following conditions:

* **With Your Group Members:** Any expense, settlement, name, avatar, or UPI ID you post within a group is visible to other members of that specific group or anyone possessing that group’s invite link.
* **Service Providers & Infrastructure:** We utilize trusted third-party service providers who assist in operating our infrastructure:
  * **Supabase:** Cloud database hosting, database authentication, and real-time data sync with Row-Level Security.
  * **Firebase / Google Cloud:** Push notification delivery (FCM) and web hosting.
  * **Discord (Optional):** If a group administrator enables Discord integration, summary activity messages are transmitted to the administrator's designated Discord webhook.
* **Legal Requirements:** We may disclose your information if required to do so by applicable law, regulation, subpoena, or governmental request.

---

## 5. Financial Data & Payment Clarification

**HisabKitab is an accounting and debt-tracking utility, not a banking institution, digital wallet, or payment gateway.**
* HisabKitab does **not** process monetary transactions directly.
* HisabKitab does **not** initiate bank transfers or hold user funds.
* Any settlement via UPI or bank transfer is executed outside the app through third-party banking/UPI applications (e.g., Google Pay, PhonePe, Paytm, BHIM) on the user's device.
* We **never** access, collect, or store sensitive banking credentials, credit/debit card verification values (CVV/CVC), or UPI PINs.

---

## 6. Device Permissions (Android & Mobile)

HisabKitab may request the following permissions depending on your usage:
* **Internet / Network Access (`android.permission.INTERNET`):** Required to sync expenses, authenticate accounts, and communicate with the database.
* **Notifications (`android.permission.POST_NOTIFICATIONS`):** Optional permission to alert you when group members add expenses, make settlements, or send reminders.
* **Vibration / Haptics (`android.permission.VIBRATE`):** Used strictly for haptic feedback during interactive gestures and button presses.

You can grant or revoke these permissions at any time via your device settings.

---

## 7. Data Retention and Security

* **Security Measures:** We employ industry-standard security practices, including HTTPS/TLS encryption in transit, strict database Row-Level Security (RLS) policies in Supabase, and isolated tenant queries to protect your data from unauthorized access.
* **Retention:** We retain your account and transaction data for as long as your account is active or as necessary to provide services to your groups.

---

## 8. Your Data Rights & Deletion

Depending on your jurisdiction (such as GDPR, CCPA, or applicable regional data protection laws), you have rights regarding your personal information:
* **Access & Review:** You can view your profile, expenses, and group ledgers directly within the app at any time.
* **Update & Correction:** You can update your display name, UPI ID, and avatar in the Profile page.
* **Account Deletion:** You have the right to request permanent deletion of your account and associated personal data. When requested, your personal identifying records will be removed or anonymized from our database.
* **How to Request Deletion:** To request account deletion or data removal, submit a request via email to **support@hisabkitab.app** with the subject line *"Account Deletion Request"* from the email address linked to your account.

---

## 9. Children’s Privacy

HisabKitab does not knowingly collect or solicit personal information from children under the age of 13 (or under 16 where required by local law). If we become aware that we have collected personal data from a child without verified parental consent, we will promptly delete that data.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our app features, legal obligations, or technical infrastructure. Any revisions will be posted with an updated "Last updated" date. Continued use of the Service after changes are published constitutes your acceptance of the revised policy.

---

## 11. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact us at:

* **Email:** [support@hisabkitab.app](mailto:support@hisabkitab.app)
* **App Name:** HisabKitab
* **Package / App ID:** `com.hisabkitab.application`
