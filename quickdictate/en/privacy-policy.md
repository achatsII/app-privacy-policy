# Privacy Policy — QuickDictate

This document contains the privacy policy for the **QuickDictate** mobile application in English.
You can view the [French version (Version française)](../fr/privacy-policy.md).

---

**Last Updated: July 24, 2026**

Intelligence Industrielle ("we", "us", or "our") values the privacy of our users. This Privacy Policy outlines how the **QuickDictate** mobile application (the "Application") collects, uses, discloses, and safeguards your information when you use it on Apple iOS and Google Android platforms.

By installing and using the Application, you consent to the data practices described in this Privacy Policy.

---

### 1. General Application Information

QuickDictate is a voice dictation mobile application designed to record voice input, transcribe the audio into text using the secure Intelligence Industrielle gateway API, and automatically store, organize (via tags), and summarize these transcriptions as daily or weekly logs using Artificial Intelligence (AI).

These features rely on third-party AI providers. **No data is sent to those providers without your explicit, prior consent**, which is collected directly inside the Application (see Section 6).

---

### 2. Data We Collect and Purposes of Processing

To deliver the core functionality of the Application, we collect the following types of information:

- **Audio Data (Voice Recordings):** When you initiate a recording, the Application captures your voice using your device's microphone. These recordings are encrypted and securely sent to our gateway for transcription, and only after you have agreed to share data with the AI services (Section 6). The raw audio recordings are not stored permanently on our servers once transcription has succeeded.
- **Transcriptions and Generated Text:** The text transcripts of your dictations, classification tags (manually created or suggested by AI), and daily or weekly journal summaries are stored securely in our database to provide your history and logs.
- **Authentication Credentials:** Authentication is handled using secure OAuth 2.0 with PKCE. Access and refresh tokens are stored locally on your device in an encrypted form using the native secure storage API (`expo-secure-store`).
- **Offline Synchronization Queue:** If saving a transcription to your history fails (no internet connection or a server error), the corresponding transcribed text is kept locally on your device in encrypted storage and is automatically re-sent to your history as soon as a connection is restored, so that no data is lost.
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

Your data is not used for any other purpose. It is never used for advertising, profiling, or for training artificial intelligence models.

---

### 5. Data Sharing and Third-Party Processors

We do not sell, rent, or trade your personal data to third parties for marketing or advertising purposes.

**Intelligence Industrielle Gateway**

All communications are encrypted in transit using HTTPS/TLS protocols and routed to our official gateway (`https://gateway.intelligenceindustrielle.com`), which then relays the data to the AI providers listed below.

**Third-Party AI Providers**

The Application shares your data with the following third-party AI providers, and with no others:

| Provider | Data sent to them | Purpose |
| --- | --- | --- |
| **OpenAI, L.L.C.** | The audio recording of your dictation | Speech-to-text conversion (transcription) |
| **Google LLC** | The transcribed text of your notes | Generating classification tags and daily/weekly summaries |

No other data is sent to these providers. Your name, email address, account identifiers, and authentication tokens are never shared with them.

**Equivalent Protection Provided by These Third Parties**

We have entered into data processing agreements with each of these providers that contractually require them to provide a level of protection for your data that is **equal to or greater than** the protection described in this Privacy Policy. In particular, they are prohibited from:

- using your data to train or improve their models;
- retaining your data beyond the time strictly required to process the request;
- selling, renting, sharing, or disclosing your data to anyone;
- using your data for any purpose other than performing the requested service.

**Changes to the List of Providers**

If we add, replace, or remove an AI provider, we will update this policy and the Application will **ask for your explicit consent again** before sending any data to the new provider.

---

### 6. Explicit Consent for Sharing With AI Services

In line with applicable privacy requirements, the Application does not transmit any data to a third-party AI service without your prior permission.

- **Before any transmission:** the first time you use an AI-powered feature (recording a dictation, creating a voice tag, or generating a journal), the Application displays a consent screen. That screen states exactly which data is sent, who receives it, and for what purpose.
- **Freely given consent:** no recording is started and no data is sent until you tap "I agree and continue". If you decline, the AI features simply remain inactive.
- **Withdraw at any time:** you can withdraw your consent at any time from **Settings → Privacy → Withdraw my consent to AI sharing**. After withdrawal, the Application immediately stops sending data to the AI services and will ask for your permission again before any new transcription.
- **Re-prompt on change:** if the nature of the data sent or the list of recipients changes, your previous consent is invalidated and the consent screen is presented to you again.

---

### 7. Data Storage, Retention, and Security

- **Server-Side Security:** Data stored on our servers is protected by firewalls, encryption at rest and in transit, and strict authorization controls.
- **On-Device Security:** Sensitive authentication credentials are encrypted and stored within your device's secure storage enclave (`SecureStore` on iOS and Android KeyStore).
- **Data Retention:** We retain your data for as long as your account remains active. Upon requesting the deletion of your account, all associated data will be permanently deleted from our production databases within 30 days.

---

### 8. Your Rights and Data Deletion

In accordance with applicable data protection regulations (including Law 25 in Quebec, PIPEDA in Canada, and GDPR in Europe):

- You have the right to access, rectify, port, and delete your personal data.
- You can withdraw your consent to share data with the AI services at any time, directly inside the Application (see Section 6).
- You can delete any individual transcription from your history within the Application.
- You can request the permanent deletion of your account and all historical dictation records by contacting us at the email address provided in Section 11.

---

### 9. Children's Privacy

The Application is not intended for use by individuals under the age of 13. We do not knowingly collect personal data from children. If we discover that a child has provided us with personal data without parental consent, we will delete such information immediately.

---

### 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect regulatory or technical changes. The "Last Updated" date at the top of the policy will be updated accordingly. We encourage you to review this policy periodically.

---

### 11. Contact and Data Protection Officer

If you have any questions about this Privacy Policy or wish to exercise your data protection rights, please contact our data protection representative at:

- **Intelligence Industrielle**
- **Email:** `support@intelligenceindustrielle.com`
- **Website:** [https://intelligenceindustrielle.com](https://intelligenceindustrielle.com)
