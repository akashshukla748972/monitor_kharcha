  # Privacy Policy for Monitor Kharcha

**Effective Date:** September 19, 2026  
**Application Name:** Monitor Kharcha - Money Manager  
**Package Name:** `com.monitorkharcha.app`  

---

## 1. Overview
Welcome to **Monitor Kharcha** ("we", "our", or "us"). We are committed to protecting your personal privacy. Monitor Kharcha is designed as an offline-first, local personal finance manager. Your financial data, transaction history, receipts, and security PINs are stored securely on your local device. 

We do not sell, rent, trade, or share your data with any third parties or advertising networks.

---

## 2. Information We Collect and Store

### A. Information You Provide
- **Financial Transactions:** Details regarding your expenses and incomes (amount, date, title, payment method, category, and optional notes).
- **Receipt Images:** Photos of bills or receipts that you photograph using your camera or upload from your device gallery.
- **Preferences:** Preferred currency symbol, monthly budget target, and account name.

All of the above information is stored in an encrypted local database (`SQLite`) on your device.

### B. Information We Do NOT Collect
- We do **NOT** collect bank account numbers, credit/debit card numbers, or online banking passwords.
- We do **NOT** track your GPS location.
- We do **NOT** integrate third-party advertising SDKs or data broker trackers.

---

## 3. Device Permissions and How They Are Used

Monitor Kharcha only requests permissions strictly necessary for user-initiated actions:

| Permission | Android Name | Purpose |
| :--- | :--- | :--- |
| **Camera** | `android.permission.CAMERA` | Used exclusively when you choose to take a photo of a receipt or bill to attach to a transaction. |
| **Storage / Media** | `READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE` | Used to select receipt images from your photo gallery and save exported PDF/Excel statements to your Downloads folder. |
| **Biometrics** | `android.permission.USE_BIOMETRIC` | Used to unlock the app using your device's fingerprint or face authentication via Android's secure `BiometricPrompt` framework. No biometric data is accessed or stored by the app. |
| **Vibration** | `android.permission.VIBRATE` | Used to provide subtle haptic feedback when tapping buttons and entering numeric amounts. |

---

## 4. Security & Biometrics
- **Biometric Data:** Fingerprint and Face Unlock use the native Android OS authentication system. The app receives only a cryptographic confirmation of successful authentication; biometric signatures never leave your device's hardware security module (TEE/SE).
- **Security PIN:** If you enable the 4-digit PIN lock, the PIN is validated locally against an encrypted hash stored on your device.

---

## 5. Third-Party Services & Data Sharing
- **Zero Advertising:** There are no advertisements in Monitor Kharcha.
- **Zero Third-Party Data Sharing:** We do not transfer, sell, or disclose your financial records to any third parties.
- **Optional Cloud Sync:** If you configure optional cloud synchronization, your encrypted ledger is transmitted solely between your verified devices over TLS/HTTPS encryption.

---

## 6. Data Deletion and User Rights
You have complete control over your data:
- **Transaction Deletion:** You can delete transactions individually. Deleted items are held in the in-app Recycle Bin for 24 hours before automatic permanent purge, or can be restored immediately.
- **Purge All Records:** You can reset and clear all data anytime in **Profile & Settings > Data Management**.
- **App Uninstallation:** Deleting the app from your device immediately erases the local database and all associated offline files.

---

## 7. Children's Privacy
Monitor Kharcha is intended for general audiences and does not knowingly collect information from children under the age of 13.

---

## 8. Updates to This Policy
We may update this Privacy Policy from time to time. Any changes will be published here with an updated "Effective Date".

---

## 9. Contact Us
If you have any questions or suggestions regarding this Privacy Policy, please contact us:
- **Email:** support@monitorkharcha.app
- **Developer:** Monitor Kharcha Team
