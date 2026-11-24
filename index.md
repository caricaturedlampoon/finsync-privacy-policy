# Privacy Policy for FinSync Ji

**Effective Date:** 24 November 2026  
**App Name:** FinSync Ji ("Log Split Track Analyse Grow")  
**Developer / Entity:** FinSync Personal Finance Solutions

---

## 1. Overview

FinSync Ji is a local-first personal finance, investment tracking, and group expense management application designed with privacy, security, and user control at its core.

FinSync allows users to manage their personal finances independently while offering optional cloud-based synchronization for collaborative Group Expenses.

This Privacy Policy explains what information we collect, how it is stored and processed, how it may be shared, and the controls available to users regarding their personal and financial data.

## 2. Personal Financial Data & Local Storage

### 2.1 On-Device Storage

Your personal financial information is stored locally on your device using IndexedDB and applicable local storage mechanisms.

This includes:

- Personal income and expenses.
- Bank accounts and account balances.
- Credit card records.
- Investment portfolios and holdings.
- Personal loans and debts.
- Net worth and financial reports.
- Personal financial notes and transaction history.
- Financial preferences and custom categories.

### 2.2 Personal Data Privacy

FinSync does not automatically upload your personal financial records to developer-managed cloud databases.

Your personal financial information remains under your control unless you explicitly choose to export, share, or back up such information.

The optional Group Expenses synchronization feature operates separately from your personal financial records.

## 3. Multi-User Group Expenses & Cloud Synchronization

### 3.1 Purpose of Cloud Synchronization

FinSync provides an optional multi-user Group Expenses feature that allows users to create groups, record shared expenses, split payments, manage settlements, and synchronize group information across multiple devices.

This functionality uses Google Firebase Cloud Firestore as its cloud database.

### 3.2 Information Stored in the Cloud

When you choose to share a group or participate in a cloud-synchronized group, the following information may be stored and processed through Firebase:

- Group names, identifiers, and settings.
- Group member names and identifiers.
- Authenticated user identifiers associated with group membership.
- Shared expense amounts, descriptions, categories, and dates.
- Expense payer and participant information.
- Expense splitting calculations and outstanding balances.
- Settlement and repayment records.
- Group invitation links, tokens, and membership requests.
- Group activity and modification history.
- Synchronization metadata, timestamps, record versions, operation identifiers, and technical device identifiers used for synchronization.

This information is used to enable collaborative expense management, maintain data consistency, prevent duplicate transactions, resolve synchronization conflicts, and protect against unauthorized modifications.

### 3.3 Local-First Architecture

FinSync follows a local-first architecture for Group Expenses.

- Group expenses and modifications are initially stored on the user's device.
- Newly created, unshared groups remain local until the user initiates the group-sharing process.
- Once a group is shared, eligible group information is synchronized with Firebase Cloud Firestore.
- Changes made while offline are retained locally and synchronized when an internet connection becomes available and the user is appropriately authenticated.
- Synchronization may occur in batches to improve performance and reduce unnecessary network usage.

Users can continue using supported offline functionality without an active internet connection.

### 3.4 Separation of Personal and Group Financial Data

Cloud synchronization of Group Expenses does not automatically synchronize your personal financial accounts, investment portfolios, personal transaction history, bank balances, or other unrelated financial records.

If a shared expense is linked to a personal financial transaction, the personal account information and unrelated personal financial records remain locally stored.

However, financial information that you explicitly enter into a shared expense becomes part of the shared group record and may be accessible to authorized group members.

## 4. Group Invitations, Membership & Data Visibility

### 4.1 Group Invitations

FinSync allows users to invite others to join shared expense groups through invitation links or invitation codes.

These invitations may contain unique identifiers or security tokens necessary to locate the group and initiate the membership process.

Users should share invitation links only with intended recipients.

### 4.2 Member Authentication

Users joining synchronized groups may be required to authenticate using Google Sign-In.

FinSync may use the authenticated user's Google profile name to assist with identifying the appropriate group member. Membership association and approval mechanisms help prevent unauthorized access or incorrect identity assignment.

### 4.3 Information Visible to Group Members

Authorized members of a shared group may access information associated with that group, including:

- Group member names.
- Shared expenses and payment contributions.
- Expense descriptions and amounts.
- Individual group balances.
- Expense splitting details.
- Settlement records.
- Relevant group activity and transaction history.

Access to a shared group does not grant other members access to your private financial accounts, investments, personal transactions, Google Drive backups, or other unrelated personal information.

### 4.4 User Responsibility

Users are responsible for the information they voluntarily enter into shared groups.

Users should avoid including passwords, banking credentials, card numbers, government identification numbers, or other unnecessary sensitive information in shared expense descriptions or group records.

FinSync cannot control information that authorized group members independently copy, export, screenshot, or redistribute.

## 5. Authentication & Account Information

FinSync Ji uses Google Sign-In and Firebase Authentication to support authenticated functionality, including multi-user Group Expenses.

Depending on the features used, the following information may be processed:

- Google account display name.
- Email address.
- Firebase Authentication user identifier (UID).
- Google profile information made available through authentication.
- Authentication and session-related information.

This information is used for:

- User authentication.
- Group membership identification.
- Secure access to synchronized group data.
- Prevention of unauthorized access.
- Association of cloud records with authenticated users.
- Account management and security.

FinSync Ji does not directly collect or store your Google account password.

Google Sign-In is not required for core offline personal finance functionality, but may be necessary for cloud-enabled features.

## 6. Optional Cloud Backup & Google Drive Integration

### 6.1 Personal Google Drive Backup

FinSync Ji offers an optional cloud backup feature that allows users to store encrypted financial backup files (`.finsync.enc`) directly in their personal Google Drive accounts.

Google Drive backups are separate from Firebase-based Group Expenses synchronization.

### 6.2 Google Drive Access Limitations

When connecting Google Drive, FinSync Ji requests the following limited permission:

`https://www.googleapis.com/auth/drive.file`

This permission limits access to files created through FinSync Ji or explicitly made available to FinSync Ji by the user.

FinSync Ji does not request unrestricted access to the contents of your Google Drive.

### 6.3 Backup Encryption

Financial backup files are encrypted on the user's device using AES-256 encryption with PBKDF2-based key derivation before being uploaded to Google Drive.

FinSync Ji does not retain the user's backup decryption password or encryption key on developer-managed cloud servers.

Users are responsible for securely retaining their backup credentials. Losing these credentials may prevent recovery of encrypted backups.

### 6.4 Google API Limited Use

FinSync Ji's use and transfer of information received from Google APIs will adhere to the Google API Services User Data Policy, including the Limited Use requirements.

Google Drive information is used only to provide and maintain the backup and restoration functionality requested by the user.

## 7. Data Security

FinSync Ji uses technical and organizational safeguards designed to protect user information against unauthorized access, modification, disclosure, and loss.

These safeguards include, where applicable:

- Local-first financial data storage.
- Encrypted personal financial backups.
- Secure network communication using HTTPS/TLS.
- Firebase Authentication.
- Firestore security rules and group-based access restrictions.
- Authenticated group membership verification.
- Version-controlled synchronization.
- Duplicate transaction prevention.
- Transaction integrity and conflict-handling mechanisms.
- Controlled group invitation and membership processes.

FinSync Ji also provides local device security features, including:

- Application Lock using a four-digit PIN.
- Biometric authentication using supported fingerprint or facial authentication mechanisms.

Biometric verification is handled through supported device and operating system security mechanisms.

### 7.1 Cloud Data Encryption

Group Expenses data stored through Firebase Cloud Firestore benefits from the encryption-in-transit and encryption-at-rest protections provided by Google Cloud infrastructure.

Shared Group Expenses data is not represented as end-to-end encrypted. It may be accessible to authorized group members and authorized service administrators where necessary for service operation, security, support, or legal compliance.

Although reasonable safeguards are implemented, no electronic storage or transmission system can guarantee absolute security.

## 8. Third-Party Services

FinSync Ji uses third-party services to provide authentication, cloud synchronization, and optional backup functionality.

These services include:

### Google Firebase Authentication

Used to authenticate users and manage account identities.

### Google Firebase Cloud Firestore

Used to store and synchronize shared Group Expenses and associated membership and synchronization records.

### Google Sign-In and Google Play Services

Used to facilitate authentication and supported device functionality.

### Google Drive API

Used to provide optional encrypted backup and restoration functionality.

These services may process information according to their respective privacy policies and service terms.

Users may review the following:

- Google Privacy Policy: https://policies.google.com/privacy
- Firebase Privacy and Security: https://firebase.google.com/support/privacy
- Google API Services User Data Policy: https://developers.google.com/terms/api-services-user-data-policy

FinSync Ji does not sell or rent personal or financial information to advertisers, data brokers, or other third parties.

## 9. How We Use Information

Information processed through FinSync Ji is used for purposes including:

- Providing personal finance management functionality.
- Authenticating users.
- Enabling shared Group Expenses.
- Synchronizing group information across authorized devices.
- Managing invitations and group membership.
- Calculating shared expenses and settlements.
- Maintaining transaction integrity and data consistency.
- Preventing unauthorized access and duplicate transactions.
- Providing optional backup and restoration functionality.
- Resolving technical issues and responding to support requests.
- Complying with applicable legal obligations.

FinSync Ji does not use personal financial information for targeted advertising or the sale of user profiles.

## 10. Data Retention

### 10.1 Local Financial Data

Personal financial records remain on the user's device until they are deleted, application storage is cleared, or the application is uninstalled, subject to any backups or copies retained by the user or operating system.

### 10.2 Google Drive Backups

Encrypted backup files remain in the user's Google Drive account until the user deletes them or they are otherwise removed under Google's storage policies.

### 10.3 Cloud-Synchronized Group Data

Shared Group Expenses data may remain in Firebase while the relevant group or associated records remain active.

Synchronization metadata, modification histories, and deletion records may be retained as necessary to maintain data consistency, prevent deleted records from reappearing, and support security and integrity.

Cloud data is subject to applicable deletion requests, retention requirements, and legal obligations.

## 11. Data Deletion & Account Deletion

### 11.1 Deleting Local Application Data

Users may remove locally stored financial information by:

- Deleting records within FinSync Ji.
- Clearing FinSync Ji's application storage through device settings.
- Uninstalling the application.

Users should ensure that any desired backups are created before deleting their local data.

Clearing application storage or uninstalling FinSync Ji does not automatically delete Google Drive backups, Firebase account information, or synchronized group records.

### 11.2 Deleting Google Drive Backups

Users may delete their encrypted backup files directly from their personal Google Drive accounts.

To revoke FinSync Ji's access to Google Drive, users may manage connected application permissions through their Google Account security settings:

https://myaccount.google.com/connections

Revoking access does not automatically delete existing backup files.

### 11.3 Deleting Shared Group Expenses Data

Users may manage or request deletion of shared group records, subject to applicable group permissions.

Because Group Expenses involve multiple participants, deleting a local copy of a group or removing an individual account may not automatically delete all shared records belonging to other participants.

Where shared records must legitimately be retained, personal identifiers should be removed or anonymized wherever reasonably possible.

### 11.4 Requesting Account & Cloud Data Deletion

Users may request deletion of their FinSync Ji account and associated personal cloud data by contacting:

**Email:** caricaturedlampoon@gmail.com

**Subject:** FinSync Ji Account and Data Deletion Request

Users should provide the email address associated with their FinSync Ji account to assist with identity verification.

Account deletion requests will be processed subject to identity verification and applicable legal requirements.

Where applicable, deletion will cover associated authentication records, personal profile information, membership associations, and other personal cloud data, except information that must legitimately be retained for legal, security, fraud prevention, or other disclosed lawful purposes.

Users will be informed of any applicable retention exceptions.

Deleting a FinSync Ji account does not delete the user's Google account or independently stored Google Drive backups.

## 12. User Rights & Controls

Depending on applicable laws and the features used, users may request to:

- Access their personal information.
- Correct inaccurate personal information.
- Delete their account and associated personal information.
- Withdraw permissions granted to FinSync Ji.
- Disconnect Google Drive integration.
- Stop participating in cloud-synchronized groups.
- Export or manage their locally stored financial records.
- Raise concerns regarding the processing of their personal information.

Users may contact FinSync Ji through the support email provided in this policy to exercise applicable rights.

## 13. Cloud Processing & International Data Transfers

FinSync Ji uses Google-operated cloud infrastructure for authentication and synchronized Group Expenses.

Depending on service configurations and Google infrastructure, information may be processed or stored in countries other than the user's country of residence.

Such processing is subject to applicable privacy laws and the safeguards provided by the relevant cloud service provider.

## 14. Changes to This Privacy Policy

FinSync Ji may update this Privacy Policy from time to time to reflect changes in application features, data processing practices, security measures, or applicable legal requirements.

Updated versions will be made available through the application, official privacy policy page, or associated repository.

The effective date at the beginning of this policy indicates when the latest version becomes applicable.

## 15. Contact Us

For questions, concerns, account deletion requests, or other matters relating to this Privacy Policy, please contact:

**Developer / Entity:** FinSync Ji Personal Finance Solutions

**Application:** FinSync Ji — Log Split Track Analyse Grow

**Support Email:** [caricaturedlampoon@gmail.com](mailto:caricaturedlampoon@gmail.com)

---

**Last Updated:** 24 November 2026

**FinSync Ji Personal Finance Solutions**
