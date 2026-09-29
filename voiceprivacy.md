Privacy Policy for Voice Screen Lock & App Lock

Last Updated: September 29, 2026

1. Introduction
Welcome to Voice Screen Lock & App Lock ("Application," "App," "we," "our," or "us"). We are committed to safeguarding your privacy and ensuring you have complete transparency regarding how your data is handled. This Privacy Policy details the types of information processed by Voice Screen Lock, how it is used, and the choices you have regarding your personal data and device security.

By downloading, installing, or using Voice Screen Lock & App Lock, you agree to the practices described in this Privacy Policy. If you do not agree with this policy, please do not use our Application.

2. Core Privacy Principle: Local-First Data Processing
We firmly adhere to the principle of data minimization and privacy by design. All critical authentication information—including your voice commands, passcode, pattern, and security preferences—is stored and processed strictly LOCALLY on your device. We do not operate remote authentication servers, and we never upload, store, or transmit your voice recordings, passcodes, or patterns to external servers.

3. Information We Process and How It Is Used
Depending on the features you enable, the Application handles the following types of data:

a. Audio & Voice Data (Microphone)
- What is processed: Spoken voice phrases captured when you record your voice unlock password or speak to unlock your phone or apps.
- Purpose: Real-time biometric/voice recognition matching against your enrolled unlock phrase.
- Privacy Guarantee: Audio is analyzed strictly on-device in real-time. Audio recordings are NEVER uploaded to any cloud server, NEVER stored permanently as audio files, and NEVER shared with any third party. Once voice matching is evaluated, raw audio buffers are immediately discarded from memory.

b. Biometric Data (Fingerprint)
- What is processed: Biometric authentication status.
- Purpose: Quick and secure unlocking via your device's hardware fingerprint reader.
- Privacy Guarantee: The Application interfaces exclusively with Android's standard BiometricPrompt API. The App never accesses, reads, collects, or stores your raw fingerprint or biometric imagery. All biometric evaluation is conducted exclusively within your device's isolated hardware-level Trusted Execution Environment (TEE).

c. Passcode, Pattern, and Time Password Data
- What is processed: Your chosen numeric PIN, pattern gesture coordinates, or dynamic time-lock settings.
- Purpose: Alternate and emergency authentication methods to unlock your device or protected applications.
- Storage & Security: Passwords and patterns are cryptographically hashed and encrypted using Android Jetpack Security (MasterKey / EncryptedSharedPreferences) stored exclusively in private local app storage.

d. App Usage Statistics (Package Usage)
- What is processed: Detection of the currently active/foreground application package name.
- Purpose: Required exclusively for the "App Lock" feature to detect when you or someone else opens a locked app (e.g., WhatsApp, Gallery), allowing the App Lock overlay to prompt for authentication.
- Privacy Guarantee: App usage information is inspected in real-time on-device and is NEVER logged, aggregated, tracked, uploaded, or transmitted to any external server.

e. Device Information and Non-Personal Diagnostics
- What is collected: Device model, manufacturer, Android OS version, screen resolution, locale/language, battery status, and standard crash/performance logs.
- Purpose: To ensure compatibility, resolve application crashes, maintain foreground service stability, and optimize layout rendering across different screen sizes.

4. Device Permissions We Request
To deliver lock screen and app locker functionality, the Application requires specific Android runtime and special permissions:

- RECORD_AUDIO (Microphone): Required to capture your spoken voice passphrase for voice unlock and voice configuration.
- SYSTEM_ALERT_WINDOW (Display Over Other Apps): Required to display the Voice Lock Screen and App Lock verification windows over other apps and system interfaces.
- PACKAGE_USAGE_STATS (Usage Access): Required for the App Locker feature to detect when a protected application is launched.
- USE_BIOMETRIC / FINGERPRINT: Enables optional fingerprint unlock using standard Android security APIs.
- FOREGROUND_SERVICE & FOREGROUND_SERVICE_SPECIAL_USE: Ensures the security monitor remains active in the background without being prematurely terminated by Android's memory management, guaranteeing uninterrupted device protection.
- POST_NOTIFICATIONS: Displays a persistent status notification indicating that the Voice Lock security service is actively running and protecting your device.
- WAKE_LOCK & USE_FULL_SCREEN_INTENT: Allows the Application to awaken the display and instantly present the secure lock screen when you turn on your device.
- INTERNET & ACCESS_NETWORK_STATE: Required solely for third-party advertising delivery and consent management.

5. Third-Party Services and Advertising
We integrate trusted third-party SDKs to support our free application through advertising and ensure compliance with global privacy regulations:

a. Google AdMob (Google LLC)
We use Google AdMob to serve advertisements within the Application. Google AdMob may collect and use device identifiers (such as the Google Advertising ID / GAID), IP address, coarse device performance data, and app interaction data to serve ads. 
For more information about how Google collects and uses data, please review:
- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses information from apps: https://policies.google.com/technologies/partner-sites

b. Google User Messaging Platform (UMP)
We integrate Google's User Messaging Platform (UMP) SDK to comply with European Union General Data Protection Regulation (GDPR), UK Data Protection Act, and US State privacy laws (such as CCPA/CPRA). Through the UMP consent form, users in relevant jurisdictions can choose whether to allow personalized ads, non-personalized ads, or revoke consent at any time from within the App settings.

6. Data Storage, Encryption, and Security
We implement strict physical, electronic, and procedural safeguards to protect your information:
- Local Cryptographic Storage: All security settings, master switches, passcodes, and voice pattern models are stored using Android Jetpack Security cryptographic standards (`androidx.security.crypto.EncryptedSharedPreferences`).
- No Cloud Transmission: Because we do not upload authentication credentials to any cloud infrastructure, your personal credentials cannot be intercepted in transit or compromised via remote database breaches.
- Sandboxed App Environment: All data is saved inside Android's protected application sandbox, inaccessible to other installed applications on non-rooted devices.

7. Data Retention and Deletion (User Control)
You maintain total ownership and control over your data:
- Immediate Deletion on Reset: You can change or clear your voice passphrase, PIN, or pattern at any time directly in the Application settings.
- Complete Erasure: Clearing the Application's storage in Android Settings (`Settings > Apps > Voice Screen Lock > Storage > Clear Data`) or uninstalling the Application immediately and permanently erases all stored voice models, passwords, preferences, and cached configurations from your device.

8. Children's Privacy (COPPA Compliance)
Our Application is intended for general audiences and is not directed to children under the age of 13 (or under 16 in the EEA/UK). We do not knowingly collect, request, or solicit personal information from children under 13. If you believe that a child has provided personal information to us, please contact us immediately, and we will take prompt steps to delete any such data.

9. GDPR and European Privacy Rights (EEA/UK Users)
If you reside within the European Economic Area (EEA) or the United Kingdom (UK), you possess statutory rights under the General Data Protection Regulation (GDPR), including:
- The right to access, rectify, or erase your data.
- The right to withdraw consent for personalized advertising at any time via the Privacy Options / Consent dialog in the App.
- The right to lodge a complaint with your local Data Protection Authority.

10. California Privacy Rights (CCPA / CPRA)
If you are a California resident, you are protected under the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA).
- We do not sell your personal information.
- We do not share your biometric or voice data with third parties.
- Third-party advertising partners (Google AdMob) may collect device identifiers and usage metrics for targeted advertising if you have consented. You have the right to opt out of personalized advertising via your Android system settings (`Settings > Google > Ads > Delete Advertising ID / Reset Advertising ID`) or via our in-app Consent Manager.

11. Changes to This Privacy Policy
We may periodically update this Privacy Policy to reflect modifications in our features, operational practices, or applicable legal and regulatory standards. Any modifications will be posted within the Application and accompanied by an updated "Last Updated" date. We encourage you to review this Privacy Policy periodically.
