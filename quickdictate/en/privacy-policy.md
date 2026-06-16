# Privacy Policy — QuickDictate

This document contains the privacy policy for the **QuickDictate** mobile application in English.
You can view the [French version (Version française)](../fr/privacy-policy.md).

---

**Last Updated: June 16, 2026**

Intelligence Industrielle ("we", "us", or "our") values the privacy of our users. This Privacy Policy outlines how the **QuickDictate** mobile application (the "Application") collects, uses, discloses, and safeguards your information when you use it on Apple iOS and Google Android platforms.

By installing and using the Application, you consent to the data practices described in this Privacy Policy.

---

### 1. General Application Information

QuickDictate is a voice dictation mobile application designed to record voice input, transcribe the audio into text using the secure Intelligence Industrielle gateway API, and automatically store, organize (via tags), and summarize these transcriptions as daily or weekly logs using Artificial Intelligence (AI).

---

### 2. Data We Collect and Purposes of Processing

To deliver the core functionality of the Application, we collect the following types of information:

- **Audio Data (Voice Recordings):** When you initiate a recording, the Application captures your voice using your device's microphone. These recordings are encrypted and securely sent to our gateway for transcription. The raw audio recordings are not stored permanently on our servers once transcription has succeeded.
- **Transcriptions and Generated Text:** The text transcripts of your dictations, classification tags (manually created or suggested by AI), and daily or weekly journal summaries are stored securely in our database to provide your history and logs.
- **Authentication Credentials:** Authentication is handled using secure OAuth 2.0 with PKCE. Access and refresh tokens are stored locally on your device in an encrypted form using the native secure storage API (`expo-secure-store`).
- **Offline Synchronization Queue:** If you dictate while offline, the pending audio recordings are queued locally on your device in encrypted storage and will automatically synchronize with our servers for transcription as soon as a connection is restored.
- **Technical and Diagnostic Data:** We may collect anonymized or pseudonymized technical information (such as device model, OS version, and crash logs) to diagnose application issues and optimize overall stability.

---

### 3. Required Application Permissions

The Application requires access to specific device features to function properly. You can enable or disable these permissions at any time via your device's system settings:

- **Microphone (`RECORD_AUDIO`, `FOREGROUND_SERVICE_MICROPHONE`):** Essential for capturing your voice. Microphone access is only active while you are actively recording a voice note.
- **Foreground Service & Background Audio (`FOREGROUND_SERVICE`, `UIBackgroundModes: audio`):** Allows the Application to record audio continuously and stably even if your screen turns off or you switch to another application.

---

### 4. How We Use Your Data

We process your data to:

- Provide and maintain the core voice dictation and transcription services.
- Suggest classification tags and generate productivity summaries (AI journal logs).
- Ensure real-time backup and synchronization of your dictation history across devices.
- Protect your account security and prevent unauthorized access.

---

### 5. Data Sharing and Third-Party Processors

We do not sell, rent, or trade your personal data to third parties for marketing or advertising purposes.

- **Intelligence Industrielle Gateway:** All communications are encrypted in transit using HTTPS/TLS protocols and routed to our official gateway (`https://gateway.intelligenceindustrielle.com`).
- **Technology Subprocessors (Transcription & AI):** In order to perform speech-to-text transcription and generate AI summaries/tags, required text and audio data may be securely processed by trusted third-party APIs (such as Google Cloud, OpenAI, or Anthropic). These subprocessors are bound by strict confidentiality agreements and are contractually prohibited from using your data to train their models.

---

### 6. Data Storage, Retention, and Security

- **Server-Side Security:** Data stored on our servers is protected by firewalls, encryption at rest and in transit, and strict authorization controls.
- **On-Device Security:** Sensitive authentication credentials are encrypted and stored within your device's secure storage enclave (`SecureStore` on iOS and Android KeyStore).
- **Data Retention:** We retain your data for as long as your account remains active. Upon requesting the deletion of your account, all associated data will be permanently deleted from our production databases within 30 days.

---

### 7. Your Rights and Data Deletion

In accordance with applicable data protection regulations (including Law 25 in Quebec, PIPEDA in Canada, and GDPR in Europe):

- You have the right to access, rectify, port, and delete your personal data.
- You can request the permanent deletion of your account and all historical dictation records by contacting us at the email address provided in Section 10.

---

### 8. Children's Privacy

The Application is not intended for use by individuals under the age of 13. We do not knowingly collect personal data from children. If we discover that a child has provided us with personal data without parental consent, we will delete such information immediately.

---

### 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect regulatory or technical changes. The "Last Updated" date at the top of the policy will be updated accordingly. We encourage you to review this policy periodically.

---

### 10. Contact and Data Protection Officer

If you have any questions about this Privacy Policy or wish to exercise your data protection rights, please contact our data protection representative at:

- **Intelligence Industrielle**
- **Email:** `support@intelligenceindustrielle.com`
- **Website:** [https://intelligenceindustrielle.com](https://intelligenceindustrielle.com)
