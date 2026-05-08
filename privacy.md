# Privacy Policy for Havyu AI

**Last Updated:** [08 May 2026]

## 1. Introduction
Welcome to Havyu AI. We are committed to protecting your privacy. This policy explains how our application collects, uses, and protects your information, including device sensors, workout data, authentication data, and technical analytics.

We are based in UK and can be contacted at havyulabs@gmail.com.

## 2. Device Sensor Data (Camera & Microphone)
To provide our core tracking features, Havyu AI requires access to certain device sensors:
* **Camera:** Havyu AI uses your camera to track your movements and automatically count your repetitions. **All visual processing happens locally on your device.** We do not record, store, or transmit your live video feed or photos to any external servers.
* **Microphone:** We use your microphone to allow you to log workouts via voice commands. Your audio data is transmitted securely to your device's native OS speech recognition services (Apple or Google). We do not store or intercept this audio data on our own servers.

## 3. AI Coaching & Workout Data
Havyu AI utilizes Large Language Models (LLMs) to provide coaching insights. To generate your personalized briefings, we transmit your logged **habit and weightlifting data** to our AI provider, Google Gemini.
* This data is used strictly to generate your in-app coaching experience.
* We do not transmit personally identifiable information (such as your name or email address) alongside this workout data to the LLM provider.
* You will be asked for explicit consent before any data is transmitted to our AI provider for the first time. You may withdraw this consent at any time in Settings, after which AI coaching features will fall back to on-device computation only.
* Google Gemini's data handling is governed by Google's own terms; we have selected providers that commit not to use submitted data to train their public models.

## 4. Account and Authentication (Optional)
Havyu AI is fully usable without an account. However, you may optionally sign in using **Sign in with Apple** or **Sign in with Google** to enable cross-device subscription portability and (in future versions) cloud backup of your data.

If you choose to sign in:
* We receive your email address and the name you provide. If you use Apple's "Hide My Email" feature, we receive a private relay address rather than your real email.
* This authentication data is stored by our authentication provider, **Supabase**, on infrastructure located in the EU West.
* Your user identifier is shared with our subscription processor, RevenueCat, so that your Pro subscription status follows you across devices.
* We do not store any payment information. All payments are processed by Apple or Google.

You can sign out at any time from Settings, which removes your session from this device. To request **deletion of your authentication record from Supabase**, contact havyulabs@gmail.com from your registered email address. We process deletion requests within 30 days.

## 5. Workout and Habit Data Storage
Your workout sets, habit check-ins, body weight, sleep, mood, and other personal training data are stored **locally on your device** in an SQLite database. This data does not leave your device except:
* When transmitted to Google Gemini for AI coaching (with your consent — see Section 3); or
* When you explicitly use the Export Data feature in Settings to share a copy with yourself.

We do not currently sync your workout data to any cloud server. If we add cloud backup in a future version, we will update this policy and request your explicit opt-in before any sync occurs.

## 6. Subscriptions and Payments (Free / Pro Tiers)
Havyu AI offers both Free and Pro tiers. All payments and subscriptions are processed securely through the Apple App Store or Google Play Store. We do not collect, process, or store your credit card or direct payment information on our servers. Subscription state is managed by **RevenueCat**, our subscription infrastructure provider.

## 7. Analytics and Crash Reporting
To ensure a stable experience, we utilize a third-party diagnostic service (**Sentry**) to capture crash reports. We configure our tools to strip Personally Identifiable Information (PII) by default. On iOS, we ask for your explicit permission via App Tracking Transparency (ATT) before collecting any non-essential analytics.

## 8. Third-Party Sub-Processors
We use the following sub-processors to operate Havyu AI:
| Provider | Purpose | Data shared |
|---|---|---|
| Google Gemini | AI coaching | Anonymised workout, nutrition, sleep, and mood data (with consent) |
| Supabase | Authentication and (future) cloud sync | Email, name, user identifier (only if you sign in) |
| RevenueCat | Subscription management | User identifier and entitlement status |
| Sentry | Crash reporting | Anonymised crash diagnostics |
| Apple / Google | App Store distribution and payments | Per their respective privacy policies |

## 9. Your Rights (GDPR, CCPA, and similar regulations)
You have the right to:
* **Access** the data we hold about you. Most of your data is on your device — use Settings → Export Data. For authentication data, contact us at havyulabs@gmail.com.
* **Delete** your data. Local data is deleted by uninstalling the app or using "Clear Workout History" / "Clear Habit Data" in Settings. Authentication data deletion requests can be sent to havyulabs@gmail.com.
* **Withdraw consent** for AI coaching at any time in Settings.
* **Object** to specific processing or request data portability — contact us.

## 10. Children's Privacy
**Age Requirement:** You must be at least 13 years of age to use Havyu AI; by downloading or using the app, you confirm that you meet this requirement. We do not knowingly collect data from children under 13. If you believe we may have collected data from a child under 13, please contact us at havyulabs@gmail.com so we can promptly delete it.

## 11. Changes to This Policy
We may update this policy from time to time. Material changes will be highlighted in-app on next launch, and the "Last Updated" date at the top of this document will reflect the change. Continued use of Havyu AI after a change constitutes acceptance of the updated policy.

## 12. Contact
If you have any questions regarding your data, please reach out to us at: **havyulabs@gmail.com**
