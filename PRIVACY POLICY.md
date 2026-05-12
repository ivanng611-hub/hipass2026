
                          PRIVACY POLICY
                      HiPass Password Vault
                         Version 1.0.0


Last Updated: May 11, 2026

--------------------------------------------------------------------------------
1. INTRODUCTION
--------------------------------------------------------------------------------

HiPass Password Vault ("the App", "we", "our", or "us") is committed to
protecting your privacy. This Privacy Policy explains how we collect, use,
store, and protect your information when you use our mobile application.

HiPass Password Vault is a 100% offline password management application.
Your data never leaves your device and is never transmitted to any external
server or third party.

--------------------------------------------------------------------------------
2. INFORMATION WE COLLECT
--------------------------------------------------------------------------------

2.1 Information You Provide
  - Master Password: Stored as a salted SHA-256 hash only. The actual
    password is never stored.
  - Password Entries: Stored locally on your device in AES-256-CBC encrypted
    format. Each entry may include: website/app name, username, password,
    category, notes, TOTP secret keys, custom fields, and expiration dates.
  - Settings Preferences: Theme preference (light/dark/system), auto-lock
    timeout duration. Stored locally in app preferences.

2.2 Information Automatically Collected
  - In-App Activity Logs: Last accessed timestamp per entry (stored locally
    within the encrypted vault only, not transmitted externally).
  - App Performance Data: Basic crash diagnostics stored locally for
    debugging purposes only.

We do NOT collect:
  - Device identifiers
  - Location data
  - Cookies or tracking data
  - Any personal information beyond what you explicitly enter into the app

--------------------------------------------------------------------------------
3. HOW WE USE YOUR INFORMATION
--------------------------------------------------------------------------------

All collected information is used EXCLUSIVELY for the following purposes:

  - Encrypting and storing your password vault locally on your device
  - Generating TOTP (Time-based One-Time Password) codes when you enter
    TOTP secret keys
  - Providing password strength analysis
  - Auto-lock functionality based on inactivity timers
  - Backing up and restoring your encrypted vault data

--------------------------------------------------------------------------------
4. DATA ENCRYPTION AND SECURITY
--------------------------------------------------------------------------------

  - Master Password: Hashed with SHA-256 and a unique salt using PBKDF2
    (10,000 iterations) before any storage.
  - Vault Data: Encrypted with AES-256-CBC cipher, keyed to your master
    password via PBKDF2-derived encryption key.
  - Export Files: Encrypted with a separate user-provided password using
    PBKDF2 (10,000 iterations) + AES-256-CBC.
  - TOTP Secret Keys: Stored encrypted within your vault just like passwords.

Security Measures Implemented:
  - 100% offline operation — zero network communication
  - Auto-lock after configurable inactivity period (1-30 minutes)
  - No cloud sync, no remote servers, no third-party data sharing
  - All encryption/decryption performed locally on-device

--------------------------------------------------------------------------------
5. DATA SHARING AND DISCLOSURE
--------------------------------------------------------------------------------

We do NOT share, sell, trade, or transfer your personal information or
encrypted vault data to any third party, including:
  - Advertisers
  - Analytics providers
  - Cloud storage services
  - Any external servers

We do NOT have any third-party integrations that transmit user data.

We may disclose information ONLY if required by law, such as in response to
a valid legal request by a court or governmental authority.

--------------------------------------------------------------------------------
6. DATA STORAGE AND RETENTION
--------------------------------------------------------------------------------

  - All data is stored exclusively on your device's internal storage.
  - No data is stored on any external or cloud servers.
  - You may delete all your data at any time by uninstalling the app or
    using the in-app data clearing function.
  - Export backup files (.enc) remain your responsibility to store securely.

--------------------------------------------------------------------------------
7. YOUR RIGHTS
--------------------------------------------------------------------------------

As a user of HiPass Password Vault, you have the following rights regarding
your personal data:

  - Right to Access: You can view all entries stored in your vault at any time.
  - Right to Delete: You can delete any or all entries, or uninstall the app.
  - Right to Rectification: You can edit any entry in your vault at any time.
  - Right to Portability: You can export your vault to an encrypted .enc file
    and import it on another device.
  - Right to Object: You can opt out of any non-essential data collection
    (though the app collects minimal data by design).

--------------------------------------------------------------------------------
8. CHILDREN'S PRIVACY
--------------------------------------------------------------------------------

HiPass Password Vault is not intended for use by individuals under the age of 16.
We do not knowingly collect personal information from children. If we become
aware that a child under 16 has provided us with personal information, we will
take immediate steps to delete such information.

--------------------------------------------------------------------------------
9. INTERNATIONAL DATA TRANSFERS
--------------------------------------------------------------------------------

Since HiPass Password Vault operates 100% offline and does not transfer any
data across borders or to any external servers, this section does not apply.

--------------------------------------------------------------------------------
10. THIRD-PARTY SERVICES
--------------------------------------------------------------------------------

HiPass Password Vault does not use any third-party services, SDKs, or APIs
that collect or process user data. All functionality is self-contained
and operates entirely offline on your device.

The app uses the following open-source libraries (locally, not networked):
  - CryptoJS (AES-256-CBC encryption)
  - Capacitor (native mobile wrapper)
  - Ionic Framework (UI components)

--------------------------------------------------------------------------------
11. CHANGES TO THIS PRIVACY POLICY
--------------------------------------------------------------------------------

We may update this Privacy Policy from time to time to reflect changes in
our practices or legal requirements. Any updates will be communicated by
publishing a new version within the app and updating the "Last Updated"
date at the top of this policy.

We encourage you to review this Privacy Policy periodically.

--------------------------------------------------------------------------------
12. CONTACT US
--------------------------------------------------------------------------------

If you have any questions, concerns, or requests regarding this Privacy
Policy or our data practices, please contact us:

  App Name: HiPass Password Vault
  
  Email: ivanng611@gmail.com
  
  Version: 1.0.0


                         END OF PRIVACY POLICY


