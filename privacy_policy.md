# Privacy Policy for FinSync

**Effective Date:** October 2024  
**App Name:** FinSync ("Log Split Track Analyse Grow")  
**Developer / Entity:** FinSync Personal Finance Solutions  

---

## 1. Overview
FinSync is an offline-first personal finance and investment tracker designed with privacy at its core. We believe that your financial data is strictly private and belongs only to you. This Privacy Policy explains how FinSync handles your information when you use our mobile application.

## 2. Data Collection & Local Storage
- **100% On-Device Storage:** All financial records, accounts, transactions, investments, and debts entered into FinSync are stored locally on your device (using IndexedDB and encrypted local storage).
- **No Developer Servers:** We do not operate central servers that collect, store, or view your financial transactions, balances, bank account details, or personal notes. Your data remains on your device under your sole control.

## 3. Optional Cloud Backup & Google Drive Integration
- **Personal Google Drive:** FinSync offers an optional cloud backup feature that allows you to back up your encrypted financial data (`.finsync.enc`) directly to your own personal Google Drive account.
- **Drive Scope Limitation:** When you connect Google Drive, FinSync requests the `https://www.googleapis.com/auth/drive.file` scope. This restricts our access *strictly* to the files created and used by FinSync. We cannot access, read, or modify any other files in your Google Drive.
- **AES-256 Encryption:** Before any backup is uploaded to your Google Drive, your data is encrypted on your device using military-grade AES-256 / PBKDF2 encryption. We do not possess your decryption keys.

## 4. Authentication & Firebase
- If you use Google Sign-In or Firebase Authentication to secure or sync your encrypted backup across devices, authentication is handled securely via Google Play Services and Firebase Auth. We only use your email address and profile information to link your encrypted vault across your devices.

## 5. Security Facilities
- FinSync provides local device security features including App Lock (4-digit PIN) and Biometric authentication (Fingerprint / Face ID) to prevent unauthorized access to your financial records on your device.

## 6. Third-Party Services
- FinSync does not sell, rent, or share any personal or financial data with third-party advertisers or data brokers.

## 7. Changes to This Privacy Policy
- We may update this Privacy Policy from time to time. Any changes will be posted within the application or repository.

## 8. Contact Us
- If you have any questions or concerns regarding this Privacy Policy or your data privacy, please contact us through our official support channels.
