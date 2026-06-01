# Privacy Policy for Havyu AI

**Last Updated:** 1 June 2026

## 1. Introduction
Welcome to Havyu AI. We are committed to protecting your privacy. This policy explains how our application collects, uses, and protects your information, including workout and habit data, authentication data, voice input, and technical diagnostics.

We are based in the UK and can be contacted at havyulabs@gmail.com.

## 2. Tracking
Havyu AI does **not** track you across other companies' apps or websites, and we do not use the App Tracking Transparency framework. We do not sell your data, and we do not use your data for third-party advertising. Our diagnostic tools are configured to strip personally identifiable information by default.

## 3. Voice Input (Microphone)
We use your microphone only when you choose to log workouts via voice commands. When you dictate a set, your speech is transmitted to your device's native operating system speech-recognition service (Apple or Google) to convert it to text. The resulting text is parsed to extract your sets and reps. We do not store or intercept raw audio on our own servers.

## 4. Camera (Future Feature)
A future version of Havyu AI may offer optional camera-based movement tracking to help count repetitions. This feature is **not active in the current version** of the app, and the app does not request camera access during normal use. If we introduce camera tracking in a future release, all visual processing is designed to happen locally on your device — we will not record, store, or transmit your video feed — and we will update this policy before the feature becomes available.

## 5. AI Coaching & Workout Data
Havyu AI uses Large Language Models (LLMs) to provide coaching insights. To generate your personalized coaching, we transmit your logged **habit and weightlifting data** to our AI provider, Google Gemini, through our own secure server.
* This data is used strictly to generate your in-app coaching experience.
* We do not transmit personally identifiable information (such as your name or email address) alongside this workout data to the LLM provider.
* You will be asked for explicit consent before any data is transmitted to our AI provider for the first time. You may withdraw this consent at any time in Settings, after which AI coaching features fall back to on-device computation only.
* Google Gemini's data handling is governed by Google's own terms; we have selected processing arrangements that commit not to use submitted data to train Google's public models.

## 6. Account and Authentication (Optional)
Havyu AI is fully usable without an account. However, you may optionally sign in using **Sign in with Apple** to enable subscription portability and (in a future version) cloud backup of your data.

If you choose to sign in:
* We receive your email address. If you use Apple's "Hide My Email" feature, we receive a private relay address rather than your real email.
* This authentication data is stored by our authentication provider, **Supabase**, on infrastructure located in the EU.
* Your user identifier is shared with our subscription processor, **RevenueCat**, so that your Pro subscription status follows you across devices.
* We do not store any payment information. All payments are processed by Apple.

You can sign out at any time from Settings, which removes your session from this device. You can also permanently delete your account and all associated authentication data directly in the app via **Settings → Account → Delete Account**. Alternatively, you may request deletion by contacting havyulabs@gmail.com from your registered email address. We process deletion requests promptly and within 30 days.

## 7. Workout and Habit Data Storage
Your workout sets, habit check-ins, body weight, sleep, mood, and other personal training data are stored **locally on your device** in an SQLite database. This data does not leave your device except:
* When transmitted to Google Gemini for AI coaching (with your consent — see Section 5); or
* When you explicitly use the Export Data feature in Settings to share a copy with yourself.

We do not currently sync your workout data to any cloud server. If we add cloud backup in a future version, we will update this policy and request your explicit opt-in before any sync occurs.

## 8. Subscriptions and Payments (Free / Pro Tiers)
Havyu AI offers both Free and Pro tiers. All payments and subscriptions are processed securely through the Apple App Store. We do not collect, process, or store your payment information on our servers. Subscription state is managed by **RevenueCat**, our subscription infrastructure provider.

## 9. Diagnostics and Crash Reporting
To ensure a stable experience, we use a third-party diagnostic service (**Sentry**) to capture crash reports and performance data. We configure our tools to strip personally identifiable information by default. This diagnostic data is used only to identify and fix problems and to improve app stability and performance. It is not used to track you and is not linked to your identity where technically avoidable; crash and performance data are associated only with an anonymous device identifier.

## 10. Third-Party Sub-Processors
We use the following sub-processors to operate Havyu AI:

| Provider | Purpose | Data shared |
|---|---|---|
| Google Gemini | AI coaching | Workout, nutrition, sleep, and mood data, without name or email (with consent) |
| Supabase | Authentication and (future) cloud sync | Email and user identifier (only if you sign in) |
| RevenueCat | Subscription management | User identifier and entitlement status |
| Sentry | Crash and performance diagnostics | Anonymous diagnostic data |
| Apple | App Store distribution and payments | Per Apple's privacy policy |

## 11. Your Rights (GDPR, UK GDPR, CCPA, and similar regulations)
You have the right to:
* **Access** the data we hold about you. Most of your data is on your device — use Settings → Export Data. For authentication data, contact us at havyulabs@gmail.com.
* **Delete** your data. Local data is deleted by uninstalling the app or using the relevant "Clear" options in Settings. Your account and authentication data can be deleted in-app via Settings → Account → Delete Account, or by contacting havyulabs@gmail.com.
* **Withdraw consent** for AI coaching at any time in Settings.
* **Object** to specific processing or request data portability — contact us.

## 12. Children's Privacy
**Age Requirement:** You must be at least 16 years of age to use Havyu AI. By downloading or using the app, you confirm that you meet this requirement. We do not knowingly collect data from anyone under 16. If you believe we may have collected data from someone under 16, please contact us at havyulabs@gmail.com so we can promptly delete it.

## 13. Changes to This Policy
We may update this policy from time to time. Material changes will be highlighted in-app on next launch, and the "Last Updated" date at the top of this document will reflect the change. Continued use of Havyu AI after a change constitutes acceptance of the updated policy.

## 14. Contact
If you have any questions regarding your data, please reach out to us at: **havyulabs@gmail.com**
