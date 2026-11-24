# Terms of Service for FinSync Ji

**Effective Date:** 24 November 2026  
**Application Name:** FinSync Ji ("Log Split Track Analyse Grow")  
**Developer / Publisher:** FinSync Ji

---

## 1. Acceptance of Terms

By downloading, installing, accessing, or using FinSync Ji ("the App"), you agree to be bound by these Terms of Service ("Terms") and the associated Privacy Policy.

If you do not agree to these Terms, you must discontinue use of the App.

By using FinSync Ji, you confirm that you are legally capable of entering into these Terms or have obtained the necessary consent from your parent or legal guardian, where applicable.

## 2. Description of Service

FinSync Ji is a local-first personal finance, investment tracking, accounting, and collaborative expense management application.

Features may include:

- Daily banking and cash management with Indian bank passbooks and INR (₹) notation.
- Personal income, expense logging, budgeting, and financial reporting.
- Portfolio tracking for Indian equities, AMFI mutual funds, Sovereign Gold Bonds, and Provident Funds.
- Investment transaction recording and statutory charge calculations, including STT, Stamp Duty, and GST.
- Debt ledgers and loan amortization calculators.
- Net worth and financial performance analysis.
- Individual and multi-user Group Expenses management.
- Shared expense splitting, balance calculations, and settlement tracking.
- Cloud synchronization of shared Group Expenses across authorized devices.
- Secure local AES-256-GCM encrypted backups.
- Optional Google Drive backup and restoration.
- Google Sign-In and authenticated cloud functionality.

FinSync Ji may introduce, modify, improve, restrict, or discontinue features over time.

## 3. Privacy & Local-First Data Storage

### 3.1 Personal Financial Data

FinSync Ji follows a local-first architecture. Personal financial records are primarily stored on the user's device.

FinSync Ji does not automatically upload personal bank balances, individual financial transactions, investment portfolios, or unrelated personal financial records to developer-managed cloud databases.

Users retain control over their personal financial information, subject to any backup, export, or sharing actions they initiate.

### 3.2 Optional Cloud Services

FinSync Ji provides two distinct cloud-enabled services:

- Encrypted personal financial backups stored in the user's Google Drive account.
- Multi-user Group Expenses synchronization through Firebase Cloud Firestore.

Using Group Expenses cloud synchronization does not automatically upload unrelated personal financial records.

### 3.3 Backup Encryption

Personal financial backup files (`.finsync.enc`) are encrypted on the user's device using AES-256-GCM encryption with PBKDF2-based key derivation.

Backup encryption passwords and decryption keys are not stored on developer-managed cloud servers.

Users are responsible for retaining their encryption passwords. FinSync Ji may be unable to recover encrypted backups if the required credentials are lost.

### 3.4 Shared Group Data

Shared Group Expenses data may be stored and processed through Firebase Cloud Firestore to enable collaboration between authorized group members.

Shared Group Expenses data is protected through authenticated access, security rules, and cloud infrastructure encryption. It is not represented as end-to-end encrypted.

Further information regarding data collection, processing, storage, and deletion is available in the FinSync Ji Privacy Policy.

## 4. User Accounts & Responsibilities

Users may sign in using supported authentication methods, including Google Sign-In, to access cloud-enabled features.

Authentication may be used for:

- Group membership verification.
- Cross-device Group Expenses synchronization.
- Cloud backup functionality.
- License entitlement recovery.
- Account management.
- Security and access control.

Users are responsible for:

- Maintaining the confidentiality of their account credentials.
- Protecting their device, application PIN, and backup encryption passwords.
- Providing accurate account and membership information.
- Preventing unauthorized access to their accounts.
- Reviewing financial records and transactions entered into the App.
- Informing FinSync Ji of suspected account misuse or security concerns.

FinSync Ji is not responsible for unauthorized activity resulting from a user's failure to reasonably protect their account or device, except where otherwise required by applicable law.

## 5. Multi-User Group Expenses

### 5.1 Group Creation & Management

FinSync Ji allows users to create expense groups, add members, record shared expenses, calculate contributions, and maintain settlement records.

Groups may include both registered FinSync Ji users and individuals who do not currently use the App.

Users creating groups are responsible for ensuring that they have appropriate permission or another lawful basis to enter information relating to other individuals.

### 5.2 Group Sharing & Cloud Publication

Newly created, unshared groups are maintained locally until the user initiates the group-sharing process.

By initiating group sharing, users authorize FinSync Ji to transmit and store relevant group information through Firebase Cloud Firestore for the purpose of collaborative expense management.

Once a group becomes cloud-enabled, subsequent eligible changes may be synchronized automatically.

Users acknowledge that shared group information may become accessible to authorized participants.

### 5.3 Group Administrators & Permissions

Group creators and authorized administrators may exercise management permissions supported by the App, which may include:

- Managing group information.
- Adding or removing members.
- Generating group invitations.
- Reviewing or approving membership requests.
- Managing shared expense records.
- Managing group access and other supported administrative settings.

Group administrators must exercise their permissions responsibly and must not misuse administrative privileges to manipulate financial records, impersonate members, or cause harm to other participants.

### 5.4 Group Member Responsibilities

Group members are responsible for ensuring that information they submit is accurate, relevant, and lawful.

Users must not:

- Create fraudulent or misleading expenses.
- Falsely assign payments or debts to other members.
- Impersonate another group participant.
- Intentionally manipulate settlement records.
- Access groups without authorization.
- Interfere with synchronization or security mechanisms.
- Misuse another member's personal or financial information.

### 5.5 Shared Data Visibility

Authorized group members may view information associated with their group, including member names, expense records, payment contributions, splitting details, balances, settlements, and relevant activity history.

Group membership does not provide access to another user's private financial accounts, personal transactions, investments, Google Drive backups, or unrelated financial information.

FinSync Ji cannot prevent authorized members from independently copying, exporting, recording, or redistributing information they are permitted to access.

### 5.6 Financial Disputes Between Members

FinSync Ji provides tools for recording, calculating, and organizing shared financial obligations.

FinSync Ji does not act as a party to financial agreements between group members and does not guarantee that any participant will repay an outstanding balance.

Disputes concerning expense amounts, payment responsibility, repayment obligations, unauthorized entries, or settlements must be resolved directly between the relevant participants.

Records maintained within FinSync Ji do not independently establish the legal validity or enforceability of a financial obligation.

## 6. Group Invitations & Membership Security

FinSync Ji allows users to invite participants through shared invitation links or codes.

Invitation links or codes may contain security tokens or identifiers used to initiate the membership process.

Users agree to:

- Share invitations only with intended recipients.
- Avoid publishing private group invitations publicly without appropriate authorization.
- Protect invitation tokens against unauthorized distribution.
- Select the correct group member identity when joining a group.
- Obtain any required membership approval.

FinSync Ji may use Google account information to assist with membership identification.

A matching Google profile name alone does not establish ownership of a group member identity. Authentication, identity association, and applicable approval mechanisms may be required.

FinSync Ji may restrict, invalidate, or reject invitations or membership requests where necessary to protect group security.

## 7. Cloud Synchronization & Offline Functionality

### 7.1 Local-First Synchronization

Group Expenses are initially recorded in local device storage and synchronized with Firebase Cloud Firestore where applicable.

Synchronization may occur automatically, in batches, or following relevant user actions.

### 7.2 Offline Modifications

Users may create or modify supported financial records while offline.

Offline modifications may remain pending until:

- An internet connection becomes available.
- Authentication requirements are satisfied.
- Required synchronization dependencies are completed.
- Cloud services become available.

A change appearing on one device does not necessarily mean that it has already been synchronized to all other devices.

### 7.3 Synchronization Conflicts

Multiple users may modify shared records at overlapping times.

FinSync Ji uses mechanisms designed to maintain transaction integrity, including version-controlled records, duplicate prevention, synchronization validation, and conflict handling.

Nevertheless, synchronization delays, conflicting modifications, rejected operations, software errors, and temporary discrepancies may occur.

Users should review important shared records and verify that relevant changes have been successfully synchronized before relying upon them.

### 7.4 Pending Transactions & Data Loss

Users should avoid clearing application storage, uninstalling the App, or resetting their devices while important changes remain unsynchronized.

Locally stored changes that have not been successfully synchronized or backed up may be permanently lost.

### 7.5 Service Availability

Cloud synchronization depends on internet connectivity, authentication services, Firebase infrastructure, and other external systems.

FinSync Ji does not guarantee uninterrupted, immediate, or error-free synchronization.

Offline personal finance functionality may remain available during cloud service interruptions, subject to device and application limitations.

## 8. Settlements & Financial Transactions

FinSync Ji is a financial recordkeeping and expense management application.

The recording of an expense, repayment, settlement, or transfer within FinSync Ji does not itself initiate an actual movement of money.

Unless expressly introduced and disclosed as a separate service, FinSync Ji does not:

- Hold or custody user funds.
- Execute bank transfers.
- Process payments between group members.
- Execute securities trades.
- Provide banking or lending services.
- Guarantee repayment of debts or outstanding balances.

Users are responsible for completing actual financial transactions through their chosen banks, payment providers, brokers, or other financial institutions.

A settlement marked as completed within FinSync Ji is a record of a reported payment and does not independently verify that the funds have been transferred.

## 9. FinSync Ji Pro & Google Play Purchases

### 9.1 Free & Premium Features

FinSync Ji offers free and premium functionality.

Basic expense logging, budgeting, passbooks, and cash tracking are available without a premium license.

Certain advanced features, which may include investment management, Demat portfolio tracking, net worth analysis, and Google Drive Cloud Vault backups, may require a FinSync Ji Pro license.

Applicable premium features and pricing will be displayed within the App or the relevant purchase interface.

### 9.2 In-App Purchases

FinSync Ji Pro purchases are processed through Google Play Billing where applicable.

Purchase entitlements may be associated with the user's Google account and verified using official Google Play purchase information, purchase tokens, or transaction identifiers.

Users must not manipulate, forge, duplicate, or unlawfully transfer purchase entitlements.

### 9.3 Lifetime License

Where FinSync Ji Pro is offered as a lifetime license, it refers to a one-time purchase providing access to the applicable premium entitlement for as long as the relevant application and entitlement are supported.

A lifetime license does not guarantee perpetual operation of third-party cloud infrastructure, indefinite availability of external APIs, or the inclusion of every future feature or separately offered service.

Nothing in this provision limits mandatory consumer protection rights or commitments expressly made at the time of purchase.

### 9.4 Refunds & Purchase Management

Purchases, refunds, and payment disputes processed through Google Play are subject to applicable Google Play policies and consumer protection laws.

Users may manage purchases through their Google Play account.

## 10. Financial, Investment & Tax Disclaimer

### 10.1 No Financial Advice

FinSync Ji is a personal accounting, tracking, calculation, and financial organization tool.

The App does not provide personalized financial, investment, tax, legal, insurance, or other regulated professional advice.

FinSync Ji does not recommend the purchase or sale of specific securities or financial products.

### 10.2 Market Data & Valuation Accuracy

FinSync Ji may retrieve financial information, including mutual fund NAVs and market prices, through publicly available data sources or third-party APIs.

Market fluctuations, corporate actions, reporting delays, unavailable data, network interruptions, or calculation limitations may result in inaccurate or outdated valuations.

### 10.3 Tax & Statutory Calculations

Tax calculations, statutory charges, investment returns, loan calculations, and financial projections are provided for informational and recordkeeping purposes.

Users should independently verify important calculations and consult qualified professionals when making financial, investment, or tax-related decisions.

### 10.4 User Responsibility

All financial decisions made using information displayed by FinSync Ji remain the responsibility of the user.

Past investment performance does not guarantee future results.

## 11. Acceptable Use

Users agree to use FinSync Ji only for lawful and authorized purposes.

Users must not:

- Engage in fraud, impersonation, harassment, or unlawful activity.
- Attempt to gain unauthorized access to another user's account or group.
- Circumvent authentication, security rules, or access restrictions.
- Exploit software vulnerabilities to manipulate financial records.
- Intentionally overload or disrupt cloud infrastructure.
- Use unauthorized automated processes to extract private user data.
- Distribute malicious code through the App or associated services.
- Circumvent premium licensing or purchase verification mechanisms.
- Use FinSync Ji to facilitate unlawful financial activities.

FinSync Ji may restrict access to affected accounts or cloud functionality where reasonably necessary to prevent abuse, protect users, maintain service security, or comply with applicable law.

## 12. User Content & Data Ownership

Users retain ownership of the personal financial information and original content they enter into FinSync Ji, subject to the rights of other individuals and applicable law.

By enabling cloud synchronization, users grant FinSync Ji and its relevant service providers permission to store, process, transmit, synchronize, and display shared group information solely as necessary to provide the requested functionality, maintain security, and comply with applicable legal obligations.

This permission does not transfer ownership of user financial information to FinSync Ji.

FinSync Ji does not claim ownership of users' personal financial records and does not sell such information to advertisers or data brokers.

## 13. Intellectual Property

Application code, interface designs, icons, branding, original algorithms, documentation, and other proprietary materials associated with FinSync Ji are protected by applicable intellectual property laws.

Users are granted a limited, non-exclusive, non-transferable license to use the App for lawful purposes in accordance with these Terms.

Users may not unlawfully reproduce, redistribute, modify, commercialize, or misrepresent proprietary FinSync Ji materials.

Third-party libraries, services, trademarks, financial data, and open-source components remain subject to their respective ownership rights and license conditions.

## 14. Third-Party Services

FinSync Ji relies on certain third-party services, which may include:

- Google Firebase Authentication.
- Google Firebase Cloud Firestore.
- Google Sign-In.
- Google Play Services.
- Google Play Billing.
- Google Drive API.
- Public financial and market data providers.

The availability and operation of these services may be subject to their respective terms, privacy policies, technical limitations, usage restrictions, and pricing structures.

FinSync Ji is not responsible for interruptions or changes caused solely by third-party services, except where otherwise required by applicable law.

## 15. Account Termination & Data Deletion

### 15.1 Discontinuing Use

Users may discontinue using FinSync Ji at any time.

Users may remove locally stored data by deleting records, clearing application storage, or uninstalling the App.

### 15.2 Account Deletion

Users may request deletion of their FinSync Ji account and associated personal cloud data through the available account deletion mechanisms or by contacting the official support email.

Account deletion is subject to identity verification and applicable legal requirements.

### 15.3 Shared Group Records

Because shared groups contain information involving multiple participants, leaving a group or deleting an individual account may not automatically remove all historical shared financial records.

Certain records may need to be retained to protect the legitimate interests of other participants, preserve transaction consistency, or comply with applicable legal obligations.

Personal identifiers should be removed or anonymized where reasonably possible and consistent with applicable privacy requirements.

### 15.4 Independent Backups

Deleting a FinSync Ji account or uninstalling the App does not automatically delete independently stored Google Drive backups.

Users are responsible for managing and deleting their personal backup files and revoking Google Drive permissions where desired.

Further details are provided in the FinSync Ji Privacy Policy.

## 16. Service Modifications & Availability

FinSync Ji may release updates to improve functionality, security, performance, compatibility, and reliability.

FinSync Ji may modify or discontinue particular features where reasonably necessary due to:

- Security vulnerabilities.
- Technical limitations.
- Changes in third-party services.
- Infrastructure requirements.
- Legal or regulatory obligations.
- Operational sustainability.

Where reasonably practicable, significant changes affecting existing users or paid entitlements will be communicated appropriately.

Users are encouraged to maintain independent backups of important financial information.

## 17. Disclaimer of Warranties

To the maximum extent permitted by applicable law, FinSync Ji is provided on an "as is" and "as available" basis.

Although reasonable efforts are made to maintain accuracy, reliability, security, and functionality, FinSync Ji does not guarantee that:

- The App will operate without interruptions or errors.
- All calculations and financial records will be completely accurate.
- Cloud synchronization will always occur immediately or successfully.
- All data can be recovered following device failure or accidental deletion.
- Third-party services will remain continuously available.
- Shared expenses or settlement records will be accepted or honored by other group members.

Nothing in these Terms excludes warranties or consumer rights that cannot lawfully be excluded.

## 18. Limitation of Liability

To the maximum extent permitted by applicable law, FinSync Ji and its developers shall not be liable for indirect, incidental, special, consequential, or punitive damages arising from the use of or inability to use the App.

This may include losses arising from:

- Financial or investment decisions.
- Incorrect or outdated financial information.
- Loss of backup passwords.
- Accidental deletion of records.
- Device failures.
- Unsynchronized transactions.
- Cloud synchronization errors.
- Third-party service interruptions.
- Unauthorized account access resulting from compromised user credentials.
- Disputes between group members.
- Unpaid debts or outstanding settlements.
- Incorrect information submitted by other users.

Nothing in these Terms excludes or restricts liability for fraud, wilful misconduct, or other matters for which liability cannot lawfully be excluded or restricted.

## 19. Governing Law & Dispute Resolution

These Terms shall be governed by the applicable laws of India, subject to any mandatory consumer protection rights or other legal protections available to users.

Users are encouraged to first contact FinSync Ji support to seek an amicable resolution of concerns or disputes relating to the App.

Unresolved disputes may be referred to the appropriate courts, consumer dispute resolution authorities, or other competent authorities having jurisdiction under applicable law.

## 20. Modifications to These Terms

FinSync Ji reserves the right to update these Terms to reflect changes in features, cloud services, security practices, business operations, or applicable legal requirements.

Updated Terms will be made available through the App, official website, or associated repository.

Continued use of the App after revised Terms become effective constitutes acceptance where permitted by applicable law.

Where additional notice or consent is legally required, FinSync Ji will provide such notice or obtain such consent as applicable.

## 21. Severability

If any provision of these Terms is determined to be invalid, unlawful, or unenforceable, the remaining provisions shall continue in effect to the extent permitted by applicable law.

## 22. Contact Us

For questions, technical concerns, account deletion requests, or matters relating to these Terms of Service, please contact:

**Developer / Publisher:** FinSync Ji

**Application:** FinSync Ji — Log Split Track Analyse Grow

**Official Support Email:** [caricaturedlampoon@gmail.com](mailto:caricaturedlampoon@gmail.com)

---

**Last Updated:** 24 November 2026

**© 2026 FinSync Ji. All rights reserved.**
