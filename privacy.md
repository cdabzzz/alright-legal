# Privacy Policy for Alright

**Last Updated:** February 14, 2026

## Overview

Alright is a mental health check-in app designed with privacy as a core principle. Most check-in data stays on your device and in your personal iCloud account.  
If you choose to use AI Insights, selected check-in data is sent to third-party AI services only after you grant consent in-app.

## What Data We Collect

### Data Stored on Your Device & iCloud (Not Accessible to Us)
- **Check-in data:** Your mood, energy, and anxiety ratings
- **Voice notes:** Audio recordings you create during check-ins
- **Text notes:** Written reflections you add to check-ins
- **Timestamps:** When you complete check-ins
- **Preferences:** Your name, wake time, bed time, and notification settings

This data syncs via Apple's iCloud if you have it enabled. We do not have access to your iCloud data.

### Data We Store on Our Servers
- **Push notification token:** A random identifier Apple assigns to your device so we can send you check-in reminders. This token cannot identify you personally.
- **Timezone and notification schedule:** So we send notifications at appropriate times for you.

That's it. We do not store your check-ins, mood data, notes, or any personal health information on our servers.

### Data Sent to Third-Party AI Services (Only with Your Consent)
When you use AI Insights and tap **"I Consent"** in the in-app disclosure, Alright sends the following data for insight generation:
- **Mood ratings** (1-5 scale)
- **Energy ratings** (1-5 scale)
- **Anxiety ratings** (1-5 scale)
- **Voice note transcriptions** (if you recorded voice notes)
- **Aggregated weekly patterns** derived from your check-ins

If you do not consent, this data is not sent for AI insight generation.

### Data Processed Temporarily (Not Stored by Alright)
- **AI insight request payloads:** Processed by third-party AI services and not stored by Alright's own backend.
- **Approximate location:** If you enable weather context, we use your approximate location to fetch weather data. Location is never stored.

## How We Use Your Data

- **Push notification tokens:** To send you scheduled check-in reminders
- **Schedule preferences:** To time notifications appropriately
- **AI insight data (with consent):** To generate AI-powered summaries and pattern insights
- **Weather context (optional):** To provide contextual weather information in the app

## Data Sharing

We do not sell, rent, or share your personal data with third parties.

We use the following third-party services:
- **Apple Push Notification Service (APNs):** Receives device push token data to deliver reminders.
- **OpenRouter:** Receives AI insight request data described above and routes requests to third-party AI model providers.
- **Third-party AI model providers via OpenRouter:** Process AI insight request data to generate responses.
- **Open-Meteo:** Receives approximate coordinates only (if weather context is enabled).

All third-party transmissions are encrypted via HTTPS.  
OpenRouter privacy details: [https://openrouter.ai/privacy](https://openrouter.ai/privacy)

## AI Consent and Control

- **Permission before sharing:** Alright asks for explicit consent before sending AI insight data to OpenRouter/model providers.
- **What you see before consent:** The app discloses what data is sent and who receives it.
- **Declining consent:** You can decline and continue using Alright without AI Insights.
- **Revoking consent:** You can revoke AI consent anytime in app Settings, which prevents future AI insight data transmission.

## Data Retention

- **On-device data:** Stored until you delete it or uninstall the app
- **iCloud data:** Managed by your iCloud settings
- **Push tokens:** Retained while you use the app; deleted when you uninstall or disable notifications
- **AI insight requests:** Alright does not retain AI request payloads on its own backend after processing. Third-party retention is governed by their policies.

## Your Rights

You can:
- **Export your data:** Download all your check-in data as a JSON file from Settings
- **Delete your data:** Remove all data from the app and our servers from Settings
- **Disable notifications:** Stop all push notifications at any time
- **Opt out of AI insights:** Use the app without consenting to AI data sharing
- **Revoke AI consent:** Turn off AI consent anytime in Settings

## Children's Privacy

Alright is not intended for children under 13. We do not knowingly collect data from children under 13.

## Security

- All data transmitted to our servers uses HTTPS encryption
- Push tokens are stored securely and cannot be used to identify you
- AI insight data is sent only after user consent and only for generating requested insights

## Changes to This Policy

We may update this policy occasionally. We'll notify you of significant changes through the app.

## Contact Us

Questions about privacy? Contact us at:
- **GitHub Issues:** https://github.com/cdabzzz/alright-legal/issues
- **Website:** https://cdabzzz.github.io/alright-legal/

---

*Alright is designed so your mental health data stays yours. We built it this way on purpose.*
