# Privacy Policy for Alright

**Last updated: September 28, 2026.** Applies to Alright version 1.1.0,
being prepared for App Store review. This page does not announce that this
version is available to download. Earlier versions and test builds may behave
differently; this policy does not retroactively describe those builds.

## Overview

Alright is a personal check-in app. The app stores your check-ins and notes locally.
It does not operate an account system, advertising network, analytics service or
cloud AI backend for this version.

## Local Information

Your profile name, wake/bed schedule, check-in timestamps, mood/energy/anxiety
ratings, written notes and recorded audio are stored on your device. Standalone
thoughts, remembered-topic flags, session dates, saved therapy briefs, discussion
history and optional session takeaways are also stored locally. This version
does not implement iCloud synchronization. Device backups may include app data
according to your Apple device and backup settings; Alright does not access them.

Reminder notifications are scheduled locally. Alright does not send a push token,
location or notification schedule to a developer-operated server.

## On-Device AI Insights And Therapy Prep {#on-device-ai-insights}

AI Insights and therapy prep use Apple's on-device Foundation Models framework.
After you enable the feature, generation starts only when you tap Generate,
Regenerate, Prep for therapy or Update brief. Weekly Insights processes average
ratings, the selected period's check-in count, and up to six recent written notes
or voice-note transcriptions, shortened for the local model's context limit.

Therapy prep processes the written notes and available voice-note transcriptions
in the period since your last session. Long text is processed in bounded portions
and then grouped into themes. Missing or partial transcriptions and unsuccessful
portions are reported; original notes and recordings remain available. Notes hidden
from the current brief are excluded from new recap generation. Older unresolved
remembered items remain available as talking points. Ratings are calculated by the
app; the therapy model receives text and source identifiers. Your profile name,
raw audio and individual check-in dates are not model inputs.

This input and the generated summaries are not sent to Alright's developer,
OpenRouter, Novita or any other cloud AI service. There is no cloud fallback.
Weekly Insights summaries are held in memory. Therapy briefs, session history and
reusable note summaries are saved on your device. The reusable summary cache is
excluded from device backup and invalidated when a source is edited or deleted.
Saved session briefs are historical snapshots and are not silently rewritten when
an original entry changes.

An Apple Intelligence-compatible device with Apple Intelligence enabled and its
model ready is required. Availability also depends on language and region. Model
downloads are handled by Apple's system software. If unavailable, the app explains
why and leaves check-ins, notes, charts and exports available under the app's
access/subscription terms.

You can disable AI Insights in Settings > Privacy. This blocks further generation
and discards any in-progress result. Disabling AI also clears the reusable summary
cache; saved therapy briefs and original records remain available until deleted.
AI summaries may be inaccurate and are not
medical advice, diagnosis, treatment, or an emergency service.

## Voice Notes

Recording requires microphone permission. Transcription uses Apple's Speech
framework with on-device recognition required, not cloud speech fallback.
Availability depends on device and language support. Recorded audio stays in the
app's local storage; text transcriptions can be included in local AI generation.

## Purchases

Apple processes subscription payments. StoreKit retrieves product, introductory-offer
eligibility and subscription information from Apple; Alright does not receive your
payment-card details. Apple determines eligibility for the two-week introductory
free trial, which starts only after you confirm a subscription with Apple. Access
is based on the Apple subscription entitlement, including any active free trial,
rather than an app-managed timer starting at first launch.

Deleting personal app data does not reset Apple's introductory-offer eligibility,
cancel an Apple subscription, or delete Apple's transaction records. Manage
subscriptions through your Apple account. Existing personal history, export and
deletion controls remain accessible without an active subscription.

## Export, Deletion And Retention

- Local records and recordings remain until deleted or removed with app data.
- Deleting an individual note or check-in removes the live original, but saved
  session briefs retain their historical copies and any referenced recordings.
  Use Delete All Data to remove those saved histories and recordings as well.
- Settings > Export My Data creates JSON containing your profile, check-ins,
  standalone notes and therapy state, including saved session briefs and takeaways.
  It includes voice-file paths, not audio file contents. Sharing the export sends
  it to the destination you select, under that destination's privacy practices.
- Therapy prep offers a separate PDF or text export. You choose the included
  sections and topics and preview the result before opening the share sheet.
  Hiding a talking point excludes its linked generated themes from the brief.
  An edited recap may still mention that topic and requires explicit selection
  before sharing when a topic is hidden. Review the preview before sharing.
- Settings > Delete All Data deletes local database records, app-owned recordings,
  cached summaries and temporary JSON/PDF/text exports, disables AI, and clears
  reminder notifications.
  If deletion fails, the app reports an error so you can retry.
- Copies you export and device backups are managed separately by you and their
  providers; local deletion cannot recall those copies.
- No check-in content, AI requests or AI responses are retained on an Alright server.

## Tracking And External Services

This app has no advertising or analytics SDK and does not sell your information
or use it for cross-app tracking. On-device processing is not transmission to a
cloud AI service. Apple services, your chosen export destinations and links you
open, including the support website, have their own privacy policies.

## Contact

Visit [Alright Support](https://cdabzzz.github.io/alright-legal/#support).
Do not include health information, private notes, payment information or credentials
in public GitHub issues.
